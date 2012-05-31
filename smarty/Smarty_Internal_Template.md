- - -

**Smarty\Smarty_Internal_Template**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 22</div>
#Class Smarty_Internal_Template#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>
    *<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html">Smarty_Internal_TemplateBase</a>
        ***Smarty_Internal_Template**


- - -

<p class="signature">public  class **Smarty_Internal_Template**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html">Smarty_Internal_TemplateBase</a>

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
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#_capture_stack">$_capture_stack</a></p><p class="description">internal capture runtime stack</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#allow_relative_path">$allow_relative_path</a></p><p class="description">internal flag to allow relative path in child template blocks</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#block_data">$block_data</a></p><p class="description">blocks for template inheritance</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#cache_id">$cache_id</a></p><p class="description">cache_id</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#cache_lifetime">$cache_lifetime</a></p><p class="description">cache lifetime in seconds</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#caching">$caching</a></p><p class="description">caching enabled</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compile_id">$compile_id</a></p><p class="description">$compile_id</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#has_nocache_code">$has_nocache_code</a></p><p class="description">flag if template does contain nocache code sections</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#mustCompile">$mustCompile</a></p><p class="description">flag if compiled template is invalid and must be (re)compiled</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#properties">$properties</a></p><p class="description">special compiled and cached template properties</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#required_plugins">$required_plugins</a></p><p class="description">required plugins</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#smarty">$smarty</a></p><p class="description">Global smarty instance</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#template_resource">$template_resource</a></p><p class="description">Template resource</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#used_tags">$used_tags</a></p><p class="description">optional log of tag/attributes</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#variable_filters">$variable_filters</a></p><p class="description">variable filters</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string template_resource, <a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _parent, mixed _cache_id, mixed _compile_id, bool _caching, int _cache_lifetime)</p><p class="description">Create template data objectSome of the global Smarty settings copied to template scope
It load the required template resources and cacher plugins</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#mustCompile">mustCompile</a>()</p><p class="description">Returns if the current template must be compiled by the Smarty compilerIt does compare the timestamps of template source and the compiled templates and checks the force compile configuration</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#compileTemplateSource">compileTemplateSource</a>()</p><p class="description">Compiles the templateIf the template is not evaluated the compiled template is saved on disk</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#writeCachedContent">writeCachedContent</a>(mixed content)</p><p class="description">Writes the cached template output</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getSubTemplate">getSubTemplate</a>(string template, mixed cache_id, mixed compile_id, integer caching, integer cache_lifetime, array vars, int parent_scope, mixed data)</p><p class="description">Template code runtime function to get subtemplate content</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setupInlineSubTemplate">setupInlineSubTemplate</a>(string template, mixed cache_id, mixed compile_id, integer caching, integer cache_lifetime, array vars, int parent_scope, string hash, mixed data)</p><p class="description">Template code runtime function to set up an inline subtemplate</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#createTemplateCodeFrame">createTemplateCodeFrame</a>(string content, bool cache)</p><p class="description">Create code frame for compiled and cached templates</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#decodeProperties">decodeProperties</a>(array properties, bool cache)</p><p class="description">This function is executed automatically when a compiled or cached template file is included- Decode saved properties from compiled template and cache files
- Check if compiled or cache file is valid</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#createLocalArrayVariable">createLocalArrayVariable</a>(string tpl_var, bool nocache, int scope)</p><p class="description">Template code runtime function to create a local Smarty variable for array assignments</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getScope">getScope</a>(int scope)</p><p class="description">Template code runtime function to get pointer to template variable array of requested scope</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getScopePointer">getScopePointer</a>(int scope)</p><p class="description">Get parent or root of template parent chain</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#capture_error">capture_error</a>()</p><p class="description">runtime error not matching capture tags</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#clearCache">clearCache</a>(integer exp_time)</p><p class="description">Empty cache for this template</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_TemplateBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#createData()">createData</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#display()">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#fetch()">fetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#getRegisteredObject()">getRegisteredObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#isCached()">isCached</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#loadFilter()">loadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerCacheResource()">registerCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerClass()">registerClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultConfigHandler()">registerDefaultConfigHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultPluginHandler()">registerDefaultPluginHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultTemplateHandler()">registerDefaultTemplateHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerFilter()">registerFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerObject()">registerObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerPlugin()">registerPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerResource()">registerResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unloadFilter()">unloadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterCacheResource()">unregisterCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterFilter()">unregisterFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterObject()">unregisterObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterPlugin()">unregisterPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterResource()">unregisterResource</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#append()">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#appendByRef()">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assign()">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignByRef()">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignGlobal()">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAllAssign()">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAssign()">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearConfig()">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#configLoad()">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVariable()">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVars()">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getStreamVariable()">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getTemplateVars()">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getVariable()">getVariable</a></td></tr></table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 98</div>
<h3 id="_capture_stack">_capture_stack</h3>
```php
public  array **$_capture_stack** = array(0 =&gt; array())```
<div class="details">
<p>internal capture runtime stack</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 93</div>
<h3 id="allow_relative_path">allow_relative_path</h3>
```php
public  bool **$allow_relative_path** = false```
<div class="details">
<p>internal flag to allow relative path in child template blocks</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 78</div>
<h3 id="block_data">block_data</h3>
```php
public  array **$block_data** = array()```
<div class="details">
<p>blocks for template inheritance</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 28</div>
<h3 id="cache_id">cache_id</h3>
```php
public  string **$cache_id** = null```
<div class="details">
<p>cache_id</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 43</div>
<h3 id="cache_lifetime">cache_lifetime</h3>
```php
public  integer **$cache_lifetime** = null```
<div class="details">
<p>cache lifetime in seconds</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 38</div>
<h3 id="caching">caching</h3>
```php
public  boolean **$caching** = null```
<div class="details">
<p>caching enabled</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 33</div>
<h3 id="compile_id">compile_id</h3>
```php
public  string **$compile_id** = null```
<div class="details">
<p>$compile_id</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 58</div>
<h3 id="has_nocache_code">has_nocache_code</h3>
```php
public  bool **$has_nocache_code** = false```
<div class="details">
<p>flag if template does contain nocache code sections</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 53</div>
<h3 id="mustCompile">mustCompile</h3>
```php
public  bool **$mustCompile** = null```
<div class="details">
<p>flag if compiled template is invalid and must be (re)compiled</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 63</div>
<h3 id="properties">properties</h3>
```php
public  array **$properties** = array(...)```
<div class="details">
<p>special compiled and cached template properties</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 68</div>
<h3 id="required_plugins">required_plugins</h3>
```php
public  array **$required_plugins** = array(...)```
<div class="details">
<p>required plugins</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 73</div>
<h3 id="smarty">smarty</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **$smarty** = null```
<div class="details">
<p>Global smarty instance</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 48</div>
<h3 id="template_resource">template_resource</h3>
```php
public  string **$template_resource** = null```
<div class="details">
<p>Template resource</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 88</div>
<h3 id="used_tags">used_tags</h3>
```php
public  array **$used_tags** = array()```
<div class="details">
<p>optional log of tag/attributes</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 83</div>
<h3 id="variable_filters">variable_filters</h3>
```php
public  array **$variable_filters** = array()```
<div class="details">
<p>variable filters</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 114</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(string template_resource, <a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _parent, mixed _cache_id, mixed _compile_id, bool _caching, int _cache_lifetime)```
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
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 140</div>
<h3 id="mustCompile()">mustCompile</h3>
```php
public  boolean **mustCompile**()```
<div class="details">
<p>Returns if the current template must be compiled by the Smarty compiler</p><p>It does compare the timestamps of template source and the compiled templates and checks the force compile configuration</p><dl>
<dt>Returns:</dt>
<dd>true if the template must be compiled</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 162</div>
<h3 id="compileTemplateSource()">compileTemplateSource</h3>
```php
public  void **compileTemplateSource**()```
<div class="details">
<p>Compiles the template</p><p>If the template is not evaluated the compiled template is saved on disk</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 215</div>
<h3 id="writeCachedContent()">writeCachedContent</h3>
```php
public  bool **writeCachedContent**(mixed content)```
<div class="details">
<p>Writes the cached template output</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 243</div>
<h3 id="getSubTemplate()">getSubTemplate</h3>
```php
public  void **getSubTemplate**(string template, mixed cache_id, mixed compile_id, integer caching, integer cache_lifetime, array vars, int parent_scope, mixed data)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 299</div>
<h3 id="setupInlineSubTemplate()">setupInlineSubTemplate</h3>
```php
public  void **setupInlineSubTemplate**(string template, mixed cache_id, mixed compile_id, integer caching, integer cache_lifetime, array vars, int parent_scope, string hash, mixed data)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 333</div>
<h3 id="createTemplateCodeFrame()">createTemplateCodeFrame</h3>
```php
public  string **createTemplateCodeFrame**(string content, bool cache)```
<div class="details">
<p>Create code frame for compiled and cached templates</p><dl>
<dt>Parameters:</dt>
<dd>content - optional template content</dd>
<dd>cache - flag for cache file</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 415</div>
<h3 id="decodeProperties()">decodeProperties</h3>
```php
public  bool **decodeProperties**(array properties, bool cache)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 476</div>
<h3 id="createLocalArrayVariable()">createLocalArrayVariable</h3>
```php
public  void **createLocalArrayVariable**(string tpl_var, bool nocache, int scope)```
<div class="details">
<p>Template code runtime function to create a local Smarty variable for array assignments</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - tempate variable name</dd>
<dd>nocache - cache mode of variable</dd>
<dd>scope - scope of variable</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 497</div>
<h3 id="getScope()">getScope</h3>
```php
public  array **getScope**(int scope)```
<div class="details">
<p>Template code runtime function to get pointer to template variable array of requested scope</p><dl>
<dt>Parameters:</dt>
<dd>scope - requested variable scope</dd>
<dt>Returns:</dt>
<dd>array of template variables</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 520</div>
<h3 id="getScopePointer()">getScopePointer</h3>
```php
public  mixed **getScopePointer**(int scope)```
<div class="details">
<p>Get parent or root of template parent chain</p><dl>
<dt>Parameters:</dt>
<dd>scope - pqrent or root scope</dd>
<dt>Returns:</dt>
<dd>object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 568</div>
<h3 id="capture_error()">capture_error</h3>
```php
public  void **capture_error**()```
<div class="details">
<p>runtime error not matching capture tags</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_template.php at line 579</div>
<h3 id="clearCache()">clearCache</h3>
```php
public  integer **clearCache**(integer exp_time)```
<div class="details">
<p>Empty cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>exp_time - expiration time</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted</dd>
</dl>
</div>

- - -

