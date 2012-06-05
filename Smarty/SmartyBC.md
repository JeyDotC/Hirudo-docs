

- - -

**Smarty\SmartyBC**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L42" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 42</a>

#Class SmartyBC#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>
 &gt; <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md">Smarty_Internal_TemplateBase</a>
 &gt; <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a>
 &gt; **SmartyBC**




- - -

<p><strong>public  class</strong> <span>SmartyBC</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Backward Compatability Wrapper Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/SmartyBC.md#_version"> $_version</a>
                                </p><p class="description">Smarty 2 BC</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#_cacheresource_handlers">_cacheresource_handlers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#_current_file">_current_file</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#_dir_perms">_dir_perms</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#_file_perms">_file_perms</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#_parserdebug">_parserdebug</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#_resource_handlers">_resource_handlers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#_smarty_vars">_smarty_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#_tag_stack">_tag_stack</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#autoload_filters">autoload_filters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#default_modifiers">default_modifiers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#escape_html">escape_html</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#merged_templates_func">merged_templates_func</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#registered_cache_resources">registered_cache_resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#registered_classes">registered_classes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#registered_filters">registered_filters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#registered_objects">registered_objects</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#registered_resources">registered_resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#smarty">smarty</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#start_time">start_time</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array options)</p><p class="description">Initialize new SmartyBC object</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#assign_by_ref">assign_by_ref</a>(string tpl_var, mixed &$value, mixed value)</p><p class="description">wrapper for assign_by_ref</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#append_by_ref">append_by_ref</a>(string tpl_var, mixed &$value, boolean merge, mixed value)</p><p class="description">wrapper for append_by_ref</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#clear_assign">clear_assign</a>(string tpl_var)</p><p class="description">clear the given assigned template variable.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_function">register_function</a>(string function, string function_impl, bool cacheable, mixed cache_attrs)</p><p class="description">Registers custom function to be used in templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_function">unregister_function</a>(string function)</p><p class="description">Unregisters custom function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_object">register_object</a>(string object, object object_impl, array allowed, boolean smarty_args, array block_functs, mixed block_methods)</p><p class="description">Registers object to be used in templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_object">unregister_object</a>(string object)</p><p class="description">Unregisters object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_block">register_block</a>(string block, string block_impl, bool cacheable, mixed cache_attrs)</p><p class="description">Registers block function to be used in templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_block">unregister_block</a>(string block)</p><p class="description">Unregisters block function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_compiler_function">register_compiler_function</a>(string function, string function_impl, bool cacheable)</p><p class="description">Registers compiler function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_compiler_function">unregister_compiler_function</a>(string function)</p><p class="description">Unregisters compiler function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_modifier">register_modifier</a>(string modifier, string modifier_impl)</p><p class="description">Registers modifier to be used in templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_modifier">unregister_modifier</a>(string modifier)</p><p class="description">Unregisters modifier</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_resource">register_resource</a>(string type, array functions)</p><p class="description">Registers a resource to fetch a template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_resource">unregister_resource</a>(string type)</p><p class="description">Unregisters a resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_prefilter">register_prefilter</a>(callable function)</p><p class="description">Registers a prefilter function to apply
to a template before compiling</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_prefilter">unregister_prefilter</a>(callable function)</p><p class="description">Unregisters a prefilter function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_postfilter">register_postfilter</a>(callable function)</p><p class="description">Registers a postfilter function to apply
to a compiled template after compilation</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_postfilter">unregister_postfilter</a>(callable function)</p><p class="description">Unregisters a postfilter function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register_outputfilter">register_outputfilter</a>(callable function)</p><p class="description">Registers an output filter function to apply
to a template output</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister_outputfilter">unregister_outputfilter</a>(callable function)</p><p class="description">Unregisters an outputfilter function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load_filter">load_filter</a>(string type, string name)</p><p class="description">load a filter of specified type and name</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#clear_cache">clear_cache</a>(string tpl_file, string cache_id, string compile_id, string exp_time)</p><p class="description">clear cached content for the given template and cache id</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#clear_all_cache">clear_all_cache</a>(string exp_time)</p><p class="description">clear the entire contents of cache (all templates)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#is_cached">is_cached</a>(string tpl_file, string cache_id, string compile_id)</p><p class="description">test to see if valid cache exists for this template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#clear_all_assign">clear_all_assign</a>()</p><p class="description">clear all the assigned template variables.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#clear_compiled_tpl">clear_compiled_tpl</a>(string tpl_file, string compile_id, string exp_time)</p><p class="description">clears compiled version of specified template resource,
or all compiled template files if one is not specified.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#template_exists">template_exists</a>(string tpl_file)</p><p class="description">Checks whether requested template exists.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#get_template_vars">get_template_vars</a>(string name)</p><p class="description">Returns an array containing template variables</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#get_config_vars">get_config_vars</a>(string name)</p><p class="description">Returns an array containing config variables</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#config_load">config_load</a>(string file, string section, string scope)</p><p class="description">load configuration values</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name"><a href="#get_registered_object">get_registered_object</a>(string name)</p><p class="description">return a reference to a registered object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#clear_config">clear_config</a>(string var)</p><p class="description">clear configuration values</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#trigger_error">trigger_error</a>(string error_msg, integer error_type)</p><p class="description">trigger Smarty error</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addautoloadfilters">addAutoloadFilters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addconfigdir">addConfigDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#adddefaultmodifiers">addDefaultModifiers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addpluginsdir">addPluginsDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addtemplatedir">addTemplateDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#clearallcache">clearAllCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#clearcache">clearCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#clearcompiledtemplate">clearCompiledTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#compileallconfig">compileAllConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#compilealltemplates">compileAllTemplates</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#createtemplate">createTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#disablesecurity">disableSecurity</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#enablesecurity">enableSecurity</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#getautoloadfilters">getAutoloadFilters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#getcachedir">getCacheDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#getcompiledir">getCompileDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#getconfigdir">getConfigDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#getdebugtemplate">getDebugTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#getdefaultmodifiers">getDefaultModifiers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#getglobal">getGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#getpluginsdir">getPluginsDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#gettags">getTags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#gettemplatedir">getTemplateDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#loadplugin">loadPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#muteexpectederrors">muteExpectedErrors</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#mutingerrorhandler">mutingErrorHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setautoloadfilters">setAutoloadFilters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setcachedir">setCacheDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setcompiledir">setCompileDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setconfigdir">setConfigDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setdebugtemplate">setDebugTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setdefaultmodifiers">setDefaultModifiers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setpluginsdir">setPluginsDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#settemplatedir">setTemplateDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#templateexists">templateExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#testinstall">testInstall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#unmuteexpectederrors">unmuteExpectedErrors</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_TemplateBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#createdata">createData</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#fetch">fetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#getregisteredobject">getRegisteredObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#iscached">isCached</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#loadfilter">loadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registercacheresource">registerCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerclass">registerClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerdefaultconfighandler">registerDefaultConfigHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerdefaultpluginhandler">registerDefaultPluginHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerdefaulttemplatehandler">registerDefaultTemplateHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerfilter">registerFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerobject">registerObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerplugin">registerPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerresource">registerResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unloadfilter">unloadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregistercacheresource">unregisterCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterfilter">unregisterFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterobject">unregisterObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterplugin">unregisterPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterresource">unregisterResource</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#append">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#appendbyref">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignbyref">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignglobal">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearallassign">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearassign">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearconfig">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#configload">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getconfigvariable">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getconfigvars">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getstreamvariable">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#gettemplatevars">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getvariable">getVariable</a></td></tr></table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L48" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 48</a>

<h3 id="_version">_version</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $_version</span><span class='o'> = self::SMARTY_VERSION</span>

<div class="details">
<p>Smarty 2 BC</p>
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L55" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 55</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (array options)

<div class="details">
<p>Initialize new SmartyBC object</p><dl>
<dt>Parameters:</dt>
<dd>options - options to set during initialization, e.g. array( 'forceCompile' => false )</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L68" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 68</a>

<h3 id="assign_by_ref()">assign_by_ref</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>assign_by_ref</span> (string tpl_var, mixed &$value, mixed value)

<div class="details">
<p>wrapper for assign_by_ref</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable name</dd>
<dd>&$value - the referenced value to assign</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L80" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 80</a>

<h3 id="append_by_ref()">append_by_ref</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>append_by_ref</span> (string tpl_var, mixed &$value, boolean merge, mixed value)

<div class="details">
<p>wrapper for append_by_ref</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable name</dd>
<dd>&$value - the referenced value to append</dd>
<dd>merge - flag if array elements shall be merged</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L90" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 90</a>

<h3 id="clear_assign()">clear_assign</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>clear_assign</span> (string tpl_var)

<div class="details">
<p>clear the given assigned template variable.</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable to clear</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L103" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 103</a>

<h3 id="register_function()">register_function</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_function</span> (string function, string function_impl, bool cacheable, mixed cache_attrs)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L113" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 113</a>

<h3 id="unregister_function()">unregister_function</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_function</span> (string function)

<div class="details">
<p>Unregisters custom function</p><dl>
<dt>Parameters:</dt>
<dd>function - name of template function</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L127" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 127</a>

<h3 id="register_object()">register_object</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_object</span> (string object, object object_impl, array allowed, boolean smarty_args, array block_functs, mixed block_methods)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L139" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 139</a>

<h3 id="unregister_object()">unregister_object</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_object</span> (string object)

<div class="details">
<p>Unregisters object</p><dl>
<dt>Parameters:</dt>
<dd>object - name of template object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L152" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 152</a>

<h3 id="register_block()">register_block</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_block</span> (string block, string block_impl, bool cacheable, mixed cache_attrs)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L162" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 162</a>

<h3 id="unregister_block()">unregister_block</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_block</span> (string block)

<div class="details">
<p>Unregisters block function</p><dl>
<dt>Parameters:</dt>
<dd>block - name of template function</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L174" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 174</a>

<h3 id="register_compiler_function()">register_compiler_function</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_compiler_function</span> (string function, string function_impl, bool cacheable)

<div class="details">
<p>Registers compiler function</p><dl>
<dt>Parameters:</dt>
<dd>function - name of template function</dd>
<dd>function_impl - name of PHP function to register</dd>
<dd></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L184" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 184</a>

<h3 id="unregister_compiler_function()">unregister_compiler_function</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_compiler_function</span> (string function)

<div class="details">
<p>Unregisters compiler function</p><dl>
<dt>Parameters:</dt>
<dd>function - name of template function</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L195" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 195</a>

<h3 id="register_modifier()">register_modifier</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_modifier</span> (string modifier, string modifier_impl)

<div class="details">
<p>Registers modifier to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>modifier - name of template modifier</dd>
<dd>modifier_impl - name of PHP function to register</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L205" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 205</a>

<h3 id="unregister_modifier()">unregister_modifier</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_modifier</span> (string modifier)

<div class="details">
<p>Unregisters modifier</p><dl>
<dt>Parameters:</dt>
<dd>modifier - name of template modifier</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L216" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 216</a>

<h3 id="register_resource()">register_resource</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_resource</span> (string type, array functions)

<div class="details">
<p>Registers a resource to fetch a template</p><dl>
<dt>Parameters:</dt>
<dd>type - name of resource</dd>
<dd>functions - array of functions to handle resource</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L226" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 226</a>

<h3 id="unregister_resource()">unregister_resource</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_resource</span> (string type)

<div class="details">
<p>Unregisters a resource</p><dl>
<dt>Parameters:</dt>
<dd>type - name of resource</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L237" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 237</a>

<h3 id="register_prefilter()">register_prefilter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_prefilter</span> (callable function)

<div class="details">
<p>Registers a prefilter function to apply
to a template before compiling</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L247" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 247</a>

<h3 id="unregister_prefilter()">unregister_prefilter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_prefilter</span> (callable function)

<div class="details">
<p>Unregisters a prefilter function</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L258" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 258</a>

<h3 id="register_postfilter()">register_postfilter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_postfilter</span> (callable function)

<div class="details">
<p>Registers a postfilter function to apply
to a compiled template after compilation</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L268" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 268</a>

<h3 id="unregister_postfilter()">unregister_postfilter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_postfilter</span> (callable function)

<div class="details">
<p>Unregisters a postfilter function</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L279" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 279</a>

<h3 id="register_outputfilter()">register_outputfilter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register_outputfilter</span> (callable function)

<div class="details">
<p>Registers an output filter function to apply
to a template output</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L289" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 289</a>

<h3 id="unregister_outputfilter()">unregister_outputfilter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>unregister_outputfilter</span> (callable function)

<div class="details">
<p>Unregisters an outputfilter function</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L300" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 300</a>

<h3 id="load_filter()">load_filter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>load_filter</span> (string type, string name)

<div class="details">
<p>load a filter of specified type and name</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd>name - filter name</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L314" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 314</a>

<h3 id="clear_cache()">clear_cache</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>clear_cache</span> (string tpl_file, string cache_id, string compile_id, string exp_time)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L325" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 325</a>

<h3 id="clear_all_cache()">clear_all_cache</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>clear_all_cache</span> (string exp_time)

<div class="details">
<p>clear the entire contents of cache (all templates)</p><dl>
<dt>Parameters:</dt>
<dd>exp_time - expire time</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L338" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 338</a>

<h3 id="is_cached()">is_cached</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>is_cached</span> (string tpl_file, string cache_id, string compile_id)

<div class="details">
<p>test to see if valid cache exists for this template</p><dl>
<dt>Parameters:</dt>
<dd>tpl_file - name of template file</dd>
<dd></dd>
<dd></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L346" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 346</a>

<h3 id="clear_all_assign()">clear_all_assign</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>clear_all_assign</span> ()

<div class="details">
<p>clear all the assigned template variables.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L361" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 361</a>

<h3 id="clear_compiled_tpl()">clear_compiled_tpl</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>clear_compiled_tpl</span> (string tpl_file, string compile_id, string exp_time)

<div class="details">
<p>clears compiled version of specified template resource,
or all compiled template files if one is not specified.
This function is for advanced use only, not normally needed.</p><dl>
<dt>Returns:</dt>
<dd>results of {@link smarty_core_rm_auto()}</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L372" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 372</a>

<h3 id="template_exists()">template_exists</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>template_exists</span> (string tpl_file)

<div class="details">
<p>Checks whether requested template exists.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L383" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 383</a>

<h3 id="get_template_vars()">get_template_vars</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>get_template_vars</span> (string name)

<div class="details">
<p>Returns an array containing template variables</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L394" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 394</a>

<h3 id="get_config_vars()">get_config_vars</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>get_config_vars</span> (string name)

<div class="details">
<p>Returns an array containing config variables</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L406" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 406</a>

<h3 id="config_load()">config_load</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>config_load</span> (string file, string section, string scope)

<div class="details">
<p>load configuration values</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L417" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 417</a>

<h3 id="get_registered_object()">get_registered_object</h3>
<span class='k'></span> <span class='nx'>object</span> <span class='nf'>get_registered_object</span> (string name)

<div class="details">
<p>return a reference to a registered object</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L427" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 427</a>

<h3 id="clear_config()">clear_config</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>clear_config</span> (string var)

<div class="details">
<p>clear configuration values</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L438" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 438</a>

<h3 id="trigger_error()">trigger_error</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>trigger_error</span> (string error_msg, integer error_type)

<div class="details">
<p>trigger Smarty error</p>
</div>

- - -

