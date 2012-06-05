

- - -

**Smarty\Smarty_Internal_TemplateBase**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 18</a>

#Class Smarty_Internal_TemplateBase#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>
 &gt; **Smarty_Internal_TemplateBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>Smarty_Internal_TemplateBase</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>

</p>

<div class="comment" id="overview_description"><p>Class with shared template methodes</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#config_vars">config_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#parent">parent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#template_class">template_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#tpl_vars">tpl_vars</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#fetch">fetch</a>(string template, mixed cache_id, mixed compile_id, object parent, bool display, bool merge_tpl_vars, bool no_output_filter)</p><p class="description">fetches a rendered Smarty template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#display">display</a>(string template, mixed cache_id, mixed compile_id, object parent)</p><p class="description">displays a Smarty template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#iscached">isCached</a>(string|object template, mixed cache_id, mixed compile_id, object parent)</p><p class="description">test if cache is valid</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#createdata">createData</a>(object parent)</p><p class="description">creates a data object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registerplugin">registerPlugin</a>(string type, string tag, callback callback, boolean cacheable, array cache_attr)</p><p class="description">Registers plugin to be used in templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#unregisterplugin">unregisterPlugin</a>(string type, string tag)</p><p class="description">Unregister Plugin</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registerresource">registerResource</a>(string type, Smarty_Resource|array callback)</p><p class="description">Registers a resource to fetch a template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#unregisterresource">unregisterResource</a>(string type)</p><p class="description">Unregisters a resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registercacheresource">registerCacheResource</a>(string type, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_CacheResource.md">Smarty_CacheResource</a> callback)</p><p class="description">Registers a cache resource to cache a template's output</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#unregistercacheresource">unregisterCacheResource</a>(string type)</p><p class="description">Unregisters a cache resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registerobject">registerObject</a>(string object, object object_impl, array allowed, boolean smarty_args, array block_methods, array block_functs, mixed object_name)</p><p class="description">Registers object to be used in templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name"><a href="#getregisteredobject">getRegisteredObject</a>(string name)</p><p class="description">return a reference to a registered object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#unregisterobject">unregisterObject</a>(string name)</p><p class="description">unregister an object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registerclass">registerClass</a>(string class, string class_impl, mixed class_name)</p><p class="description">Registers static classes to be used in templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registerdefaultpluginhandler">registerDefaultPluginHandler</a>(callable callback)</p><p class="description">Registers a default plugin handler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registerdefaulttemplatehandler">registerDefaultTemplateHandler</a>(callable callback)</p><p class="description">Registers a default template handler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registerdefaultconfighandler">registerDefaultConfigHandler</a>(callable callback)</p><p class="description">Registers a default template handler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#registerfilter">registerFilter</a>(string type, callback callback)</p><p class="description">Registers a filter function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#unregisterfilter">unregisterFilter</a>(string type, callback callback)</p><p class="description">Unregisters a filter function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadfilter">loadFilter</a>(string type, string name)</p><p class="description">load a filter of specified type and name</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span></td>
<td class="description"><p class="name"><a href="#unloadfilter">unloadFilter</a>(string type, string name)</p><p class="description">unload a filter of specified type and name</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#append">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#appendbyref">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignbyref">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignglobal">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearallassign">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearassign">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearconfig">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#configload">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getconfigvariable">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getconfigvars">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getstreamvariable">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#gettemplatevars">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getvariable">getVariable</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L32" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 32</a>

<h3 id="fetch()">fetch</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>fetch</span> (string template, mixed cache_id, mixed compile_id, object parent, bool display, bool merge_tpl_vars, bool no_output_filter)

<div class="details">
<p>fetches a rendered Smarty template</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file or template object</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>parent - next higher level of Smarty variables</dd>
<dd>display - true: display, false: fetch</dd>
<dd>merge_tpl_vars - if true parent template variables merged in to local scope</dd>
<dd>no_output_filter - if true do not run output filter</dd>
<dt>Returns:</dt>
<dd>rendered template output</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L371" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 371</a>

<h3 id="display()">display</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>display</span> (string template, mixed cache_id, mixed compile_id, object parent)

<div class="details">
<p>displays a Smarty template</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file or template object</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>parent - next higher level of Smarty variables</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L386" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 386</a>

<h3 id="isCached()">isCached</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isCached</span> (string|object template, mixed cache_id, mixed compile_id, object parent)

<div class="details">
<p>test if cache is valid</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file or template object</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>parent - next higher level of Smarty variables</dd>
<dt>Returns:</dt>
<dd>cache status</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L407" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 407</a>

<h3 id="createData()">createData</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>createData</span> (object parent)

<div class="details">
<p>creates a data object</p><dl>
<dt>Parameters:</dt>
<dd>parent - next higher level of Smarty variables</dd>
<dt>Returns:</dt>
<dd>Smarty_Data data object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L423" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 423</a>

<h3 id="registerPlugin()">registerPlugin</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerPlugin</span> (string type, string tag, callback callback, boolean cacheable, array cache_attr)

<div class="details">
<p>Registers plugin to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>type - plugin type</dd>
<dd>tag - name of template tag</dd>
<dd>callback - PHP callback to register</dd>
<dd>cacheable - if true (default) this fuction is cachable</dd>
<dd>cache_attr - caching attributes if any</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - when the plugin tag is invalid</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L443" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 443</a>

<h3 id="unregisterPlugin()">unregisterPlugin</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>unregisterPlugin</span> (string type, string tag)

<div class="details">
<p>Unregister Plugin</p><dl>
<dt>Parameters:</dt>
<dd>type - of plugin</dd>
<dd>tag - name of plugin</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L459" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 459</a>

<h3 id="registerResource()">registerResource</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerResource</span> (string type, Smarty_Resource|array callback)

<div class="details">
<p>Registers a resource to fetch a template</p><dl>
<dt>Parameters:</dt>
<dd>type - name of resource type</dd>
<dd>callback - or instance of Smarty_Resource, or array of callbacks to handle resource (deprecated)</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L471" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 471</a>

<h3 id="unregisterResource()">unregisterResource</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>unregisterResource</span> (string type)

<div class="details">
<p>Unregisters a resource</p><dl>
<dt>Parameters:</dt>
<dd>type - name of resource type</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L487" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 487</a>

<h3 id="registerCacheResource()">registerCacheResource</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerCacheResource</span> (string type, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_CacheResource.md">Smarty_CacheResource</a> callback)

<div class="details">
<p>Registers a cache resource to cache a template's output</p><dl>
<dt>Parameters:</dt>
<dd>type - name of cache resource type</dd>
<dd>callback - instance of Smarty_CacheResource to handle output caching</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L499" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 499</a>

<h3 id="unregisterCacheResource()">unregisterCacheResource</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>unregisterCacheResource</span> (string type)

<div class="details">
<p>Unregisters a cache resource</p><dl>
<dt>Parameters:</dt>
<dd>type - name of cache resource type</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L520" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 520</a>

<h3 id="registerObject()">registerObject</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerObject</span> (string object, object object_impl, array allowed, boolean smarty_args, array block_methods, array block_functs, mixed object_name)

<div class="details">
<p>Registers object to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>object - name of template object</dd>
<dd>object_impl - the referenced PHP object to register</dd>
<dd>allowed - list of allowed methods (empty = all)</dd>
<dd>smarty_args - smarty argument format, else traditional</dd>
<dd>block_methods - list of block-methods</dd>
<dd>block_functs - list of methods that are block format</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if any of the methods in $allowed or $block_methods are invalid</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L551" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 551</a>

<h3 id="getRegisteredObject()">getRegisteredObject</h3>
<span class='k'></span> <span class='nx'>object</span> <span class='nf'>getRegisteredObject</span> (string name)

<div class="details">
<p>return a reference to a registered object</p><dl>
<dt>Parameters:</dt>
<dd>name - object name</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if no such object is found</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L568" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 568</a>

<h3 id="unregisterObject()">unregisterObject</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>unregisterObject</span> (string name)

<div class="details">
<p>unregister an object</p><dl>
<dt>Parameters:</dt>
<dd>name - object name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L585" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 585</a>

<h3 id="registerClass()">registerClass</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerClass</span> (string class, string class_impl, mixed class_name)

<div class="details">
<p>Registers static classes to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>class - name of template class</dd>
<dd>class_impl - the referenced PHP class to register</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if $class_impl does not refer to an existing class</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L603" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 603</a>

<h3 id="registerDefaultPluginHandler()">registerDefaultPluginHandler</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerDefaultPluginHandler</span> (callable callback)

<div class="details">
<p>Registers a default plugin handler</p><dl>
<dt>Parameters:</dt>
<dd>callback - class/method name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if $callback is not callable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L621" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 621</a>

<h3 id="registerDefaultTemplateHandler()">registerDefaultTemplateHandler</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerDefaultTemplateHandler</span> (callable callback)

<div class="details">
<p>Registers a default template handler</p><dl>
<dt>Parameters:</dt>
<dd>callback - class/method name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if $callback is not callable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L639" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 639</a>

<h3 id="registerDefaultConfigHandler()">registerDefaultConfigHandler</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerDefaultConfigHandler</span> (callable callback)

<div class="details">
<p>Registers a default template handler</p><dl>
<dt>Parameters:</dt>
<dd>callback - class/method name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if $callback is not callable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L657" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 657</a>

<h3 id="registerFilter()">registerFilter</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>registerFilter</span> (string type, callback callback)

<div class="details">
<p>Registers a filter function</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd></dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L670" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 670</a>

<h3 id="unregisterFilter()">unregisterFilter</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>unregisterFilter</span> (string type, callback callback)

<div class="details">
<p>Unregisters a filter function</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd></dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L704" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 704</a>

<h3 id="loadFilter()">loadFilter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>loadFilter</span> (string type, string name)

<div class="details">
<p>load a filter of specified type and name</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd>name - filter name</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if filter could not be loaded</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatebase.php#L727" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 727</a>

<h3 id="unloadFilter()">unloadFilter</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Templatebase</span> <span class='nf'>unloadFilter</span> (string type, string name)

<div class="details">
<p>unload a filter of specified type and name</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd>name - filter name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -

