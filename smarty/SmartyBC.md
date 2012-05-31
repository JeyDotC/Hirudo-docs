- - -

**Smarty\SmartyBC**
<div class="location">framework\libs\smarty\SmartyBC.class.php at line 42</div>
#Class SmartyBC#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>
    *<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html">Smarty_Internal_TemplateBase</a>
        *<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html">Smarty</a>
            ***SmartyBC**


- - -

<p class="signature">public  class **SmartyBC**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html">Smarty</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Backward Compatability Wrapper Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#_version">$_version</a></p><p class="description">Smarty 2 BC</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#_cacheresource_handlers">_cacheresource_handlers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#_current_file">_current_file</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#_dir_perms">_dir_perms</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#_file_perms">_file_perms</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#_parserdebug">_parserdebug</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#_resource_handlers">_resource_handlers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#_smarty_vars">_smarty_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#_tag_stack">_tag_stack</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#autoload_filters">autoload_filters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#default_modifiers">default_modifiers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#escape_html">escape_html</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#merged_templates_func">merged_templates_func</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#registered_cache_resources">registered_cache_resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#registered_classes">registered_classes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#registered_filters">registered_filters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#registered_objects">registered_objects</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#registered_resources">registered_resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#smarty">smarty</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#start_time">start_time</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array options)</p><p class="description">Initialize new SmartyBC object</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#assign_by_ref">assign_by_ref</a>(string tpl_var, mixed &$value, mixed value)</p><p class="description">wrapper for assign_by_ref</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#append_by_ref">append_by_ref</a>(string tpl_var, mixed &$value, boolean merge, mixed value)</p><p class="description">wrapper for append_by_ref</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#clear_assign">clear_assign</a>(string tpl_var)</p><p class="description">clear the given assigned template variable.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_function">register_function</a>(string function, string function_impl, bool cacheable, mixed cache_attrs)</p><p class="description">Registers custom function to be used in templates</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_function">unregister_function</a>(string function)</p><p class="description">Unregisters custom function</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_object">register_object</a>(string object, object object_impl, array allowed, boolean smarty_args, array block_functs, mixed block_methods)</p><p class="description">Registers object to be used in templates</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_object">unregister_object</a>(string object)</p><p class="description">Unregisters object</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_block">register_block</a>(string block, string block_impl, bool cacheable, mixed cache_attrs)</p><p class="description">Registers block function to be used in templates</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_block">unregister_block</a>(string block)</p><p class="description">Unregisters block function</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_compiler_function">register_compiler_function</a>(string function, string function_impl, bool cacheable)</p><p class="description">Registers compiler function</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_compiler_function">unregister_compiler_function</a>(string function)</p><p class="description">Unregisters compiler function</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_modifier">register_modifier</a>(string modifier, string modifier_impl)</p><p class="description">Registers modifier to be used in templates</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_modifier">unregister_modifier</a>(string modifier)</p><p class="description">Unregisters modifier</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_resource">register_resource</a>(string type, array functions)</p><p class="description">Registers a resource to fetch a template</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_resource">unregister_resource</a>(string type)</p><p class="description">Unregisters a resource</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_prefilter">register_prefilter</a>(callable function)</p><p class="description">Registers a prefilter function to apply
to a template before compiling</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_prefilter">unregister_prefilter</a>(callable function)</p><p class="description">Unregisters a prefilter function</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_postfilter">register_postfilter</a>(callable function)</p><p class="description">Registers a postfilter function to apply
to a compiled template after compilation</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_postfilter">unregister_postfilter</a>(callable function)</p><p class="description">Unregisters a postfilter function</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#register_outputfilter">register_outputfilter</a>(callable function)</p><p class="description">Registers an output filter function to apply
to a template output</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#unregister_outputfilter">unregister_outputfilter</a>(callable function)</p><p class="description">Unregisters an outputfilter function</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#load_filter">load_filter</a>(string type, string name)</p><p class="description">load a filter of specified type and name</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#clear_cache">clear_cache</a>(string tpl_file, string cache_id, string compile_id, string exp_time)</p><p class="description">clear cached content for the given template and cache id</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#clear_all_cache">clear_all_cache</a>(string exp_time)</p><p class="description">clear the entire contents of cache (all templates)</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#is_cached">is_cached</a>(string tpl_file, string cache_id, string compile_id)</p><p class="description">test to see if valid cache exists for this template</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#clear_all_assign">clear_all_assign</a>()</p><p class="description">clear all the assigned template variables.</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#clear_compiled_tpl">clear_compiled_tpl</a>(string tpl_file, string compile_id, string exp_time)</p><p class="description">clears compiled version of specified template resource,
or all compiled template files if one is not specified.
</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#template_exists">template_exists</a>(string tpl_file)</p><p class="description">Checks whether requested template exists.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#get_template_vars">get_template_vars</a>(string name)</p><p class="description">Returns an array containing template variables</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#get_config_vars">get_config_vars</a>(string name)</p><p class="description">Returns an array containing config variables</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#config_load">config_load</a>(string file, string section, string scope)</p><p class="description">load configuration values</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#get_registered_object">get_registered_object</a>(string name)</p><p class="description">return a reference to a registered object</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#clear_config">clear_config</a>(string var)</p><p class="description">clear configuration values</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#trigger_error">trigger_error</a>(string error_msg, integer error_type)</p><p class="description">trigger Smarty error</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#addAutoloadFilters()">addAutoloadFilters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#addConfigDir()">addConfigDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#addDefaultModifiers()">addDefaultModifiers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#addPluginsDir()">addPluginsDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#addTemplateDir()">addTemplateDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#clearAllCache()">clearAllCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#clearCache()">clearCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#clearCompiledTemplate()">clearCompiledTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#compileAllConfig()">compileAllConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#compileAllTemplates()">compileAllTemplates</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#createTemplate()">createTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#disableSecurity()">disableSecurity</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#enableSecurity()">enableSecurity</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getAutoloadFilters()">getAutoloadFilters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getCacheDir()">getCacheDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getCompileDir()">getCompileDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getConfigDir()">getConfigDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getDebugTemplate()">getDebugTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getDefaultModifiers()">getDefaultModifiers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getGlobal()">getGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getPluginsDir()">getPluginsDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getTags()">getTags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#getTemplateDir()">getTemplateDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#loadPlugin()">loadPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#muteExpectedErrors()">muteExpectedErrors</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#mutingErrorHandler()">mutingErrorHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#setAutoloadFilters()">setAutoloadFilters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#setCacheDir()">setCacheDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#setCompileDir()">setCompileDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#setConfigDir()">setConfigDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#setDebugTemplate()">setDebugTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#setDefaultModifiers()">setDefaultModifiers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#setPluginsDir()">setPluginsDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#setTemplateDir()">setTemplateDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#templateExists()">templateExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#testInstall()">testInstall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html#unmuteExpectedErrors()">unmuteExpectedErrors</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_TemplateBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#createData()">createData</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#display()">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#fetch()">fetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#getRegisteredObject()">getRegisteredObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#isCached()">isCached</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#loadFilter()">loadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerCacheResource()">registerCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerClass()">registerClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultConfigHandler()">registerDefaultConfigHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultPluginHandler()">registerDefaultPluginHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultTemplateHandler()">registerDefaultTemplateHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerFilter()">registerFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerObject()">registerObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerPlugin()">registerPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerResource()">registerResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unloadFilter()">unloadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterCacheResource()">unregisterCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterFilter()">unregisterFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterObject()">unregisterObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterPlugin()">unregisterPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterResource()">unregisterResource</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#append()">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#appendByRef()">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assign()">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignByRef()">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignGlobal()">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAllAssign()">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAssign()">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearConfig()">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#configLoad()">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVariable()">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVars()">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getStreamVariable()">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getTemplateVars()">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getVariable()">getVariable</a></td></tr></table>

##Field Detail##
<div class="location">framework\libs\smarty\SmartyBC.class.php at line 48</div>
<h3 id="_version">_version</h3>

```php
public  string$_version = self::SMARTY_VERSION
```
<div class="details">
<p>Smarty 2 BC</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\SmartyBC.class.php at line 55</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(array options)
```
<div class="details">
<p>Initialize new SmartyBC object</p><dl>
<dt>Parameters:</dt>
<dd>options - options to set during initialization, e.g. array( 'forceCompile' => false )</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\SmartyBC.class.php at line 68</div>
<h3 id="assign_by_ref()">assign_by_ref</h3>

```php
public  void **assign_by_ref**(string tpl_var, mixed &$value, mixed value)
```
<div class="details">
<p>wrapper for assign_by_ref</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable name</dd>
<dd>&$value - the referenced value to assign</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 80</div>
<h3 id="append_by_ref()">append_by_ref</h3>

```php
public  void **append_by_ref**(string tpl_var, mixed &$value, boolean merge, mixed value)
```
<div class="details">
<p>wrapper for append_by_ref</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable name</dd>
<dd>&$value - the referenced value to append</dd>
<dd>merge - flag if array elements shall be merged</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 90</div>
<h3 id="clear_assign()">clear_assign</h3>

```php
public  void **clear_assign**(string tpl_var)
```
<div class="details">
<p>clear the given assigned template variable.</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable to clear</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 103</div>
<h3 id="register_function()">register_function</h3>

```php
public  void **register_function**(string function, string function_impl, bool cacheable, mixed cache_attrs)
```
<div class="details">
<p>Registers custom function to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>function - the name of the template function</dd>
<dd>function_impl - the name of the PHP function to register</dd>
<dd></dd>
<dd></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 113</div>
<h3 id="unregister_function()">unregister_function</h3>

```php
public  void **unregister_function**(string function)
```
<div class="details">
<p>Unregisters custom function</p><dl>
<dt>Parameters:</dt>
<dd>function - name of template function</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 127</div>
<h3 id="register_object()">register_object</h3>

```php
public  void **register_object**(string object, object object_impl, array allowed, boolean smarty_args, array block_functs, mixed block_methods)
```
<div class="details">
<p>Registers object to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>object - name of template object</dd>
<dd>object_impl - the referenced PHP object to register</dd>
<dd>allowed - list of allowed methods (empty = all)</dd>
<dd>smarty_args - smarty argument format, else traditional</dd>
<dd>block_functs - list of methods that are block format</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 139</div>
<h3 id="unregister_object()">unregister_object</h3>

```php
public  void **unregister_object**(string object)
```
<div class="details">
<p>Unregisters object</p><dl>
<dt>Parameters:</dt>
<dd>object - name of template object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 152</div>
<h3 id="register_block()">register_block</h3>

```php
public  void **register_block**(string block, string block_impl, bool cacheable, mixed cache_attrs)
```
<div class="details">
<p>Registers block function to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>block - name of template block</dd>
<dd>block_impl - PHP function to register</dd>
<dd></dd>
<dd></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 162</div>
<h3 id="unregister_block()">unregister_block</h3>

```php
public  void **unregister_block**(string block)
```
<div class="details">
<p>Unregisters block function</p><dl>
<dt>Parameters:</dt>
<dd>block - name of template function</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 174</div>
<h3 id="register_compiler_function()">register_compiler_function</h3>

```php
public  void **register_compiler_function**(string function, string function_impl, bool cacheable)
```
<div class="details">
<p>Registers compiler function</p><dl>
<dt>Parameters:</dt>
<dd>function - name of template function</dd>
<dd>function_impl - name of PHP function to register</dd>
<dd></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 184</div>
<h3 id="unregister_compiler_function()">unregister_compiler_function</h3>

```php
public  void **unregister_compiler_function**(string function)
```
<div class="details">
<p>Unregisters compiler function</p><dl>
<dt>Parameters:</dt>
<dd>function - name of template function</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 195</div>
<h3 id="register_modifier()">register_modifier</h3>

```php
public  void **register_modifier**(string modifier, string modifier_impl)
```
<div class="details">
<p>Registers modifier to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>modifier - name of template modifier</dd>
<dd>modifier_impl - name of PHP function to register</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 205</div>
<h3 id="unregister_modifier()">unregister_modifier</h3>

```php
public  void **unregister_modifier**(string modifier)
```
<div class="details">
<p>Unregisters modifier</p><dl>
<dt>Parameters:</dt>
<dd>modifier - name of template modifier</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 216</div>
<h3 id="register_resource()">register_resource</h3>

```php
public  void **register_resource**(string type, array functions)
```
<div class="details">
<p>Registers a resource to fetch a template</p><dl>
<dt>Parameters:</dt>
<dd>type - name of resource</dd>
<dd>functions - array of functions to handle resource</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 226</div>
<h3 id="unregister_resource()">unregister_resource</h3>

```php
public  void **unregister_resource**(string type)
```
<div class="details">
<p>Unregisters a resource</p><dl>
<dt>Parameters:</dt>
<dd>type - name of resource</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 237</div>
<h3 id="register_prefilter()">register_prefilter</h3>

```php
public  void **register_prefilter**(callable function)
```
<div class="details">
<p>Registers a prefilter function to apply
to a template before compiling</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 247</div>
<h3 id="unregister_prefilter()">unregister_prefilter</h3>

```php
public  void **unregister_prefilter**(callable function)
```
<div class="details">
<p>Unregisters a prefilter function</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 258</div>
<h3 id="register_postfilter()">register_postfilter</h3>

```php
public  void **register_postfilter**(callable function)
```
<div class="details">
<p>Registers a postfilter function to apply
to a compiled template after compilation</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 268</div>
<h3 id="unregister_postfilter()">unregister_postfilter</h3>

```php
public  void **unregister_postfilter**(callable function)
```
<div class="details">
<p>Unregisters a postfilter function</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 279</div>
<h3 id="register_outputfilter()">register_outputfilter</h3>

```php
public  void **register_outputfilter**(callable function)
```
<div class="details">
<p>Registers an output filter function to apply
to a template output</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 289</div>
<h3 id="unregister_outputfilter()">unregister_outputfilter</h3>

```php
public  void **unregister_outputfilter**(callable function)
```
<div class="details">
<p>Unregisters an outputfilter function</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 300</div>
<h3 id="load_filter()">load_filter</h3>

```php
public  void **load_filter**(string type, string name)
```
<div class="details">
<p>load a filter of specified type and name</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd>name - filter name</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 314</div>
<h3 id="clear_cache()">clear_cache</h3>

```php
public  boolean **clear_cache**(string tpl_file, string cache_id, string compile_id, string exp_time)
```
<div class="details">
<p>clear cached content for the given template and cache id</p><dl>
<dt>Parameters:</dt>
<dd>tpl_file - name of template file</dd>
<dd>cache_id - name of cache_id</dd>
<dd>compile_id - name of compile_id</dd>
<dd>exp_time - expiration time</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 325</div>
<h3 id="clear_all_cache()">clear_all_cache</h3>

```php
public  boolean **clear_all_cache**(string exp_time)
```
<div class="details">
<p>clear the entire contents of cache (all templates)</p><dl>
<dt>Parameters:</dt>
<dd>exp_time - expire time</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 338</div>
<h3 id="is_cached()">is_cached</h3>

```php
public  boolean **is_cached**(string tpl_file, string cache_id, string compile_id)
```
<div class="details">
<p>test to see if valid cache exists for this template</p><dl>
<dt>Parameters:</dt>
<dd>tpl_file - name of template file</dd>
<dd></dd>
<dd></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 346</div>
<h3 id="clear_all_assign()">clear_all_assign</h3>

```php
public  void **clear_all_assign**()
```
<div class="details">
<p>clear all the assigned template variables.</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 361</div>
<h3 id="clear_compiled_tpl()">clear_compiled_tpl</h3>

```php
public  boolean **clear_compiled_tpl**(string tpl_file, string compile_id, string exp_time)
```
<div class="details">
<p>clears compiled version of specified template resource,
or all compiled template files if one is not specified.
This function is for advanced use only, not normally needed.</p><dl>
<dt>Returns:</dt>
<dd>results of {@link smarty_core_rm_auto()}</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 372</div>
<h3 id="template_exists()">template_exists</h3>

```php
public  boolean **template_exists**(string tpl_file)
```
<div class="details">
<p>Checks whether requested template exists.</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 383</div>
<h3 id="get_template_vars()">get_template_vars</h3>

```php
public  array **get_template_vars**(string name)
```
<div class="details">
<p>Returns an array containing template variables</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 394</div>
<h3 id="get_config_vars()">get_config_vars</h3>

```php
public  array **get_config_vars**(string name)
```
<div class="details">
<p>Returns an array containing config variables</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 406</div>
<h3 id="config_load()">config_load</h3>

```php
public  void **config_load**(string file, string section, string scope)
```
<div class="details">
<p>load configuration values</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 417</div>
<h3 id="get_registered_object()">get_registered_object</h3>

```php
public  object **get_registered_object**(string name)
```
<div class="details">
<p>return a reference to a registered object</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 427</div>
<h3 id="clear_config()">clear_config</h3>

```php
public  void **clear_config**(string var)
```
<div class="details">
<p>clear configuration values</p></div>

- - -

<div class="location">framework\libs\smarty\SmartyBC.class.php at line 438</div>
<h3 id="trigger_error()">trigger_error</h3>

```php
public  void **trigger_error**(string error_msg, integer error_type)
```
<div class="details">
<p>trigger Smarty error</p></div>

- - -

