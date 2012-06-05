

- - -

**Smarty\Smarty_Internal_Template**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L22" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 22</a>

#Class Smarty_Internal_Template#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>
    * <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md">Smarty_Internal_TemplateBase</a>
        * **Smarty_Internal_Template**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Template</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md">Smarty_Internal_TemplateBase</a>

</p>

<div class="comment" id="overview_description"><p>Main class with template data structures and methods</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
<dt>Property:</dt>
<dd>Smarty_Template_Source $source</dd>
<dd>Smarty_Template_Compiled $compiled</dd>
<dd>Smarty_Template_Cached $cached</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_capture_stack"> $_capture_stack</a>
                                </p><p class="description">internal capture runtime stack</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#allow_relative_path"> $allow_relative_path</a>
                                </p><p class="description">internal flag to allow relative path in child template blocks</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#block_data"> $block_data</a>
                                </p><p class="description">blocks for template inheritance</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#cache_id"> $cache_id</a>
                                </p><p class="description">cache_id</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name" ><a href="#cache_lifetime"> $cache_lifetime</a>
                                </p><p class="description">cache lifetime in seconds</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#caching"> $caching</a>
                                </p><p class="description">caching enabled</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#compile_id"> $compile_id</a>
                                </p><p class="description">$compile_id</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#has_nocache_code"> $has_nocache_code</a>
                                </p><p class="description">flag if template does contain nocache code sections</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#mustCompile"> $mustCompile</a>
                                </p><p class="description">flag if compiled template is invalid and must be (re)compiled</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#properties"> $properties</a>
                                </p><p class="description">special compiled and cached template properties</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#required_plugins"> $required_plugins</a>
                                </p><p class="description">required plugins</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md#smarty'>Smarty</a></span></td>
<td class="description"><p class="name" ><a href="#smarty"> $smarty</a>
                                </p><p class="description">Global smarty instance</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#template_resource"> $template_resource</a>
                                </p><p class="description">Template resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#used_tags"> $used_tags</a>
                                </p><p class="description">optional log of tag/attributes</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#variable_filters"> $variable_filters</a>
                                </p><p class="description">variable filters</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string template_resource, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _parent, mixed _cache_id, mixed _compile_id, bool _caching, int _cache_lifetime)</p><p class="description">Create template data objectSome of the global Smarty settings copied to template scope
It load the required template resources and cacher plugins</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#mustcompile">mustCompile</a>()</p><p class="description">Returns if the current template must be compiled by the Smarty compilerIt does compare the timestamps of template source and the compiled templates and checks the force compile configuration</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#compiletemplatesource">compileTemplateSource</a>()</p><p class="description">Compiles the templateIf the template is not evaluated the compiled template is saved on disk</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#writecachedcontent">writeCachedContent</a>(mixed content)</p><p class="description">Writes the cached template output</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getsubtemplate">getSubTemplate</a>(string template, mixed cache_id, mixed compile_id, integer caching, integer cache_lifetime, array vars, int parent_scope, mixed data)</p><p class="description">Template code runtime function to get subtemplate content</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setupinlinesubtemplate">setupInlineSubTemplate</a>(string template, mixed cache_id, mixed compile_id, integer caching, integer cache_lifetime, array vars, int parent_scope, string hash, mixed data)</p><p class="description">Template code runtime function to set up an inline subtemplate</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#createtemplatecodeframe">createTemplateCodeFrame</a>(string content, bool cache)</p><p class="description">Create code frame for compiled and cached templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#decodeproperties">decodeProperties</a>(array properties, bool cache)</p><p class="description">This function is executed automatically when a compiled or cached template file is included- Decode saved properties from compiled template and cache files
- Check if compiled or cache file is valid</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#createlocalarrayvariable">createLocalArrayVariable</a>(string tpl_var, bool nocache, int scope)</p><p class="description">Template code runtime function to create a local Smarty variable for array assignments</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getscope">getScope</a>(int scope)</p><p class="description">Template code runtime function to get pointer to template variable array of requested scope</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getscopepointer">getScopePointer</a>(int scope)</p><p class="description">Get parent or root of template parent chain</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#capture_error">capture_error</a>()</p><p class="description">runtime error not matching capture tags</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearcache">clearCache</a>(integer exp_time)</p><p class="description">Empty cache for this template</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_TemplateBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#createData">createData</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#fetch">fetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#getRegisteredObject">getRegisteredObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#isCached">isCached</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#loadFilter">loadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerCacheResource">registerCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerClass">registerClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerDefaultConfigHandler">registerDefaultConfigHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerDefaultPluginHandler">registerDefaultPluginHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerDefaultTemplateHandler">registerDefaultTemplateHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerFilter">registerFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerObject">registerObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerPlugin">registerPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerResource">registerResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unloadFilter">unloadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterCacheResource">unregisterCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterFilter">unregisterFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterObject">unregisterObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterPlugin">unregisterPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterResource">unregisterResource</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#append">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#appendByRef">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignByRef">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignGlobal">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearAllAssign">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearAssign">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearConfig">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#configLoad">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getConfigVariable">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getConfigVars">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getStreamVariable">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getTemplateVars">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getVariable">getVariable</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L114" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 114</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string template_resource, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _parent, mixed _cache_id, mixed _compile_id, bool _caching, int _cache_lifetime)

<div class="details">
<p>Create template data object</p><p>Some of the global Smarty settings copied to template scope
It load the required template resources and cacher plugins</p><dl>
<dt>Parameters:</dt>
<dd>template_resource - template resource string</dd>
<dd>smarty - Smarty instance</dd>
<dd>_parent - back pointer to parent object with variables or null</dd>
<dd>_cache_id - cache id or null</dd>
<dd>_compile_id - compile id or null</dd>
<dd>_caching - use caching?</dd>
<dd>_cache_lifetime - cache life-time in seconds</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L140" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 140</a>

<h3 id="mustCompile()">mustCompile</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>mustCompile</span> ()

<div class="details">
<p>Returns if the current template must be compiled by the Smarty compiler</p><p>It does compare the timestamps of template source and the compiled templates and checks the force compile configuration</p><dl>
<dt>Returns:</dt>
<dd>true if the template must be compiled</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L162" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 162</a>

<h3 id="compileTemplateSource()">compileTemplateSource</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>compileTemplateSource</span> ()

<div class="details">
<p>Compiles the template</p><p>If the template is not evaluated the compiled template is saved on disk</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L215" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 215</a>

<h3 id="writeCachedContent()">writeCachedContent</h3>
<span class='k'></span> <span class='nx'>bool</span> <span class='nf'>writeCachedContent</span> (mixed content)

<div class="details">
<p>Writes the cached template output</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L243" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 243</a>

<h3 id="getSubTemplate()">getSubTemplate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getSubTemplate</span> (string template, mixed cache_id, mixed compile_id, integer caching, integer cache_lifetime, array vars, int parent_scope, mixed data)

<div class="details">
<p>Template code runtime function to get subtemplate content</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>caching - cache mode</dd>
<dd>cache_lifetime - life time of cache data</dd>
<dd>vars - optional variables to assign</dd>
<dd>parent_scope - scope in which {include} should execute</dd>
<dt>Returns:</dt>
<dd>string template content</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L299" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 299</a>

<h3 id="setupInlineSubTemplate()">setupInlineSubTemplate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setupInlineSubTemplate</span> (string template, mixed cache_id, mixed compile_id, integer caching, integer cache_lifetime, array vars, int parent_scope, string hash, mixed data)

<div class="details">
<p>Template code runtime function to set up an inline subtemplate</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>caching - cache mode</dd>
<dd>cache_lifetime - life time of cache data</dd>
<dd>vars - optional variables to assign</dd>
<dd>parent_scope - scope in which {include} should execute</dd>
<dd>hash - nocache hash code</dd>
<dt>Returns:</dt>
<dd>string template content</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L333" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 333</a>

<h3 id="createTemplateCodeFrame()">createTemplateCodeFrame</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>createTemplateCodeFrame</span> (string content, bool cache)

<div class="details">
<p>Create code frame for compiled and cached templates</p><dl>
<dt>Parameters:</dt>
<dd>content - optional template content</dd>
<dd>cache - flag for cache file</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L415" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 415</a>

<h3 id="decodeProperties()">decodeProperties</h3>
<span class='k'></span> <span class='nx'>bool</span> <span class='nf'>decodeProperties</span> (array properties, bool cache)

<div class="details">
<p>This function is executed automatically when a compiled or cached template file is included</p><p>- Decode saved properties from compiled template and cache files
- Check if compiled or cache file is valid</p><dl>
<dt>Parameters:</dt>
<dd>properties - special template properties</dd>
<dd>cache - flag if called from cache file</dd>
<dt>Returns:</dt>
<dd>flag if compiled or cache file is valid</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L476" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 476</a>

<h3 id="createLocalArrayVariable()">createLocalArrayVariable</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>createLocalArrayVariable</span> (string tpl_var, bool nocache, int scope)

<div class="details">
<p>Template code runtime function to create a local Smarty variable for array assignments</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - tempate variable name</dd>
<dd>nocache - cache mode of variable</dd>
<dd>scope - scope of variable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L497" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 497</a>

<h3 id="getScope()">getScope</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getScope</span> (int scope)

<div class="details">
<p>Template code runtime function to get pointer to template variable array of requested scope</p><dl>
<dt>Parameters:</dt>
<dd>scope - requested variable scope</dd>
<dt>Returns:</dt>
<dd>array of template variables</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L520" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 520</a>

<h3 id="getScopePointer()">getScopePointer</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getScopePointer</span> (int scope)

<div class="details">
<p>Get parent or root of template parent chain</p><dl>
<dt>Parameters:</dt>
<dd>scope - pqrent or root scope</dd>
<dt>Returns:</dt>
<dd>object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L568" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 568</a>

<h3 id="capture_error()">capture_error</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>capture_error</span> ()

<div class="details">
<p>runtime error not matching capture tags</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_template.php#L579" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_template.php at line 579</a>

<h3 id="clearCache()">clearCache</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clearCache</span> (integer exp_time)

<div class="details">
<p>Empty cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>exp_time - expiration time</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted</dd>
</dl>

</div>

- - -

