

- - -

**Smarty\Smarty**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L106" target='_blank'>framework\libs\smarty\Smarty.class.php at line 106</a>

#Class Smarty#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>
 &gt; <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md">Smarty_Internal_TemplateBase</a>
 &gt; **Smarty**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/SmartyBC.md">SmartyBC</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>Smarty</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md">Smarty_Internal_TemplateBase</a>

</p>

<div class="comment" id="overview_description"><p>This is the main Smarty class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_cacheresource_handlers"> $_cacheresource_handlers</a>
                                </p><p class="description">cache resource handler cache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#_current_file"> $_current_file</a>
                                </p><p class="description">required by the compiler for BC</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="#_dir_perms"> $_dir_perms</a>
                                </p><p class="description">default dir permissions</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="#_file_perms"> $_file_perms</a>
                                </p><p class="description">default file permissions</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#_parserdebug"> $_parserdebug</a>
                                </p><p class="description">internal flag to enable parser debugging</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_resource_handlers"> $_resource_handlers</a>
                                </p><p class="description">resource handler cache</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_smarty_vars"> $_smarty_vars</a>
                                </p><p class="description">global internal smarty vars</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_tag_stack"> $_tag_stack</a>
                                </p><p class="description">block tag hierarchy</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#autoload_filters"> $autoload_filters</a>
                                </p><p class="description">autoload filter</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#default_modifiers"> $default_modifiers</a>
                                </p><p class="description">default modifier</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#escape_html"> $escape_html</a>
                                </p><p class="description">autoescape variable output</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#merged_templates_func"> $merged_templates_func</a>
                                </p><p class="description">Saved parameter of merged templates during compilation</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#registered_cache_resources"> $registered_cache_resources</a>
                                </p><p class="description">registered cache resources</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#registered_classes"> $registered_classes</a>
                                </p><p class="description">registered classes</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#registered_filters"> $registered_filters</a>
                                </p><p class="description">registered filters</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#registered_objects"> $registered_objects</a>
                                </p><p class="description">registered objects</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#registered_resources"> $registered_resources</a>
                                </p><p class="description">registered resources</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#smarty'>Smarty</a></span></td>
<td class="description"><p class="name" ><a href="#smarty"> $smarty</a>
                                </p><p class="description">self pointer to Smarty object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="#start_time"> $start_time</a>
                                </p><p class="description">start time for execution time calculation</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Initialize new Smarty object</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#templateexists">templateExists</a>(string resource_name)</p><p class="description">Check if a template resource exists</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getglobal">getGlobal</a>(object smarty, string varname)</p><p class="description">Returns a single or all global  variables</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearallcache">clearAllCache</a>(integer exp_time, string type)</p><p class="description">Empty cache folder</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearcache">clearCache</a>(string template_name, string cache_id, string compile_id, integer exp_time, string type)</p><p class="description">Empty cache for a specific template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#enableSecurity>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#enablesecurity">enableSecurity</a>(string|Smarty_Security security_class)</p><p class="description">Loads security class and enables security</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#disableSecurity>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#disablesecurity">disableSecurity</a>()</p><p class="description">Disable security</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setTemplateDir>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#settemplatedir">setTemplateDir</a>(string|array template_dir)</p><p class="description">Set template directory</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addTemplateDir>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#addtemplatedir">addTemplateDir</a>(string|array template_dir, string key)</p><p class="description">Add template directory(s)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array|string</span></td>
<td class="description"><p class="name"><a href="#gettemplatedir">getTemplateDir</a>(mixed index)</p><p class="description">Get template directories</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setConfigDir>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#setconfigdir">setConfigDir</a>(string|array template_dir, mixed config_dir)</p><p class="description">Set config directory</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addConfigDir>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#addconfigdir">addConfigDir</a>(string|array config_dir, string key)</p><p class="description">Add config directory(s)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array|string</span></td>
<td class="description"><p class="name"><a href="#getconfigdir">getConfigDir</a>(mixed index)</p><p class="description">Get config directory</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setPluginsDir>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#setpluginsdir">setPluginsDir</a>(string|array plugins_dir)</p><p class="description">Set plugins directory</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addPluginsDir>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#addpluginsdir">addPluginsDir</a>(object smarty, string plugins_dir)</p><p class="description">Adds directory of plugin files</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getpluginsdir">getPluginsDir</a>()</p><p class="description">Get plugin directories</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setCompileDir>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#setcompiledir">setCompileDir</a>(string compile_dir)</p><p class="description">Set compile directory</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcompiledir">getCompileDir</a>()</p><p class="description">Get compiled directory</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setCacheDir>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#setcachedir">setCacheDir</a>(string cache_dir)</p><p class="description">Set cache directory</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcachedir">getCacheDir</a>()</p><p class="description">Get cache directory</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setDefaultModifiers>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#setdefaultmodifiers">setDefaultModifiers</a>(array|string modifiers)</p><p class="description">Set default modifiers</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addDefaultModifiers>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#adddefaultmodifiers">addDefaultModifiers</a>(array|string modifiers)</p><p class="description">Add default modifiers</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getdefaultmodifiers">getDefaultModifiers</a>()</p><p class="description">Get default modifiers</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setAutoloadFilters>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#setautoloadfilters">setAutoloadFilters</a>(array filters, string type)</p><p class="description">Set autoload filters</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addAutoloadFilters>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#addautoloadfilters">addAutoloadFilters</a>(array filters, string type)</p><p class="description">Add autoload filters</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getautoloadfilters">getAutoloadFilters</a>(string type)</p><p class="description">Get autoload filters</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getdebugtemplate">getDebugTemplate</a>()</p><p class="description">return name of debugging template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setDebugTemplate>Smarty</a></span></td>
<td class="description"><p class="name"><a href="#setdebugtemplate">setDebugTemplate</a>(string tpl_name)</p><p class="description">set the debug template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name"><a href="#createtemplate">createTemplate</a>(string template, mixed cache_id, mixed compile_id, object parent, boolean do_clone)</p><p class="description">creates a template object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#loadplugin">loadPlugin</a>(string plugin_name, bool check)</p><p class="description">Takes unknown classes and loads plugin files for them
class name format: Smarty_PluginType_PluginName
plugin filename format: plugintype.pluginname.php</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#compilealltemplates">compileAllTemplates</a>(string extension, bool force_compile, int time_limit, int max_errors, str extention)</p><p class="description">Compile all template files</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#compileallconfig">compileAllConfig</a>(string extension, bool force_compile, int time_limit, int max_errors, str extention)</p><p class="description">Compile all config files</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearcompiledtemplate">clearCompiledTemplate</a>(string resource_name, string compile_id, integer exp_time)</p><p class="description">Delete compiled template file</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#gettags">getTags</a>(object templae, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Return array of tag/attributes of all tags used by an template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#testinstall">testInstall</a>(array errors)</p><p class="description">Run installation test</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#mutingerrorhandler">mutingErrorHandler</a>(integer errno, mixed errstr, mixed errfile, mixed errline, mixed errcontext)</p><p class="description">Error Handler to mute expected messages</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#muteexpectederrors">muteExpectedErrors</a>()</p><p class="description">Enable error handler to mute expected messages</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unmuteexpectederrors">unmuteExpectedErrors</a>()</p><p class="description">Disable error handler muting expected messages</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_TemplateBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#createData">createData</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#fetch">fetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#getRegisteredObject">getRegisteredObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#isCached">isCached</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#loadFilter">loadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerCacheResource">registerCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerClass">registerClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerDefaultConfigHandler">registerDefaultConfigHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerDefaultPluginHandler">registerDefaultPluginHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerDefaultTemplateHandler">registerDefaultTemplateHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerFilter">registerFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerObject">registerObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerPlugin">registerPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#registerResource">registerResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unloadFilter">unloadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterCacheResource">unregisterCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterFilter">unregisterFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterObject">unregisterObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterPlugin">unregisterPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateBase.md#unregisterResource">unregisterResource</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#append">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#appendByRef">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignByRef">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignGlobal">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearAllAssign">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearAssign">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearConfig">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#configLoad">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getConfigVariable">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getConfigVars">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getStreamVariable">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getTemplateVars">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getVariable">getVariable</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L218" target='_blank'>framework\libs\smarty\Smarty.class.php at line 218</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Initialize new Smarty object</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L315" target='_blank'>framework\libs\smarty\Smarty.class.php at line 315</a>

<h3 id="templateExists()">templateExists</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>templateExists</span> (string resource_name)

<div class="details">
<p>Check if a template resource exists</p><dl>
<dt>Parameters:</dt>
<dd>resource_name - template name</dd>
<dt>Returns:</dt>
<dd>status</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L333" target='_blank'>framework\libs\smarty\Smarty.class.php at line 333</a>

<h3 id="getGlobal()">getGlobal</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getGlobal</span> (object smarty, string varname)

<div class="details">
<p>Returns a single or all global  variables</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>varname - variable name or null</dd>
<dt>Returns:</dt>
<dd>variable value or or array of variables</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L357" target='_blank'>framework\libs\smarty\Smarty.class.php at line 357</a>

<h3 id="clearAllCache()">clearAllCache</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clearAllCache</span> (integer exp_time, string type)

<div class="details">
<p>Empty cache folder</p><dl>
<dt>Parameters:</dt>
<dd>exp_time - expiration time</dd>
<dd>type - resource type</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L375" target='_blank'>framework\libs\smarty\Smarty.class.php at line 375</a>

<h3 id="clearCache()">clearCache</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clearCache</span> (string template_name, string cache_id, string compile_id, integer exp_time, string type)

<div class="details">
<p>Empty cache for a specific template</p><dl>
<dt>Parameters:</dt>
<dd>template_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>exp_time - expiration time</dd>
<dd>type - resource type</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L390" target='_blank'>framework\libs\smarty\Smarty.class.php at line 390</a>

<h3 id="enableSecurity()">enableSecurity</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#enableSecurity>Smarty</a></span> <span class='nf'>enableSecurity</span> (string|Smarty_Security security_class)

<div class="details">
<p>Loads security class and enables security</p><dl>
<dt>Parameters:</dt>
<dd>security_class - if a string is used, it must be class-name</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - when an invalid class name is provided</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L416" target='_blank'>framework\libs\smarty\Smarty.class.php at line 416</a>

<h3 id="disableSecurity()">disableSecurity</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#disableSecurity>Smarty</a></span> <span class='nf'>disableSecurity</span> ()

<div class="details">
<p>Disable security</p><dl>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L429" target='_blank'>framework\libs\smarty\Smarty.class.php at line 429</a>

<h3 id="setTemplateDir()">setTemplateDir</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setTemplateDir>Smarty</a></span> <span class='nf'>setTemplateDir</span> (string|array template_dir)

<div class="details">
<p>Set template directory</p><dl>
<dt>Parameters:</dt>
<dd>template_dir - directory(s) of template sources</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L448" target='_blank'>framework\libs\smarty\Smarty.class.php at line 448</a>

<h3 id="addTemplateDir()">addTemplateDir</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addTemplateDir>Smarty</a></span> <span class='nf'>addTemplateDir</span> (string|array template_dir, string key)

<div class="details">
<p>Add template directory(s)</p><dl>
<dt>Parameters:</dt>
<dd>template_dir - directory(s) of template sources</dd>
<dd>key - of the array element to assign the template dir to</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - when the given template directory is not valid</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L480" target='_blank'>framework\libs\smarty\Smarty.class.php at line 480</a>

<h3 id="getTemplateDir()">getTemplateDir</h3>
<span class='k'></span> <span class='nx'>array|string</span> <span class='nf'>getTemplateDir</span> (mixed index)

<div class="details">
<p>Get template directories</p><dl>
<dt>Parameters:</dt>
<dd>index - of directory to get, null to get all</dd>
<dt>Returns:</dt>
<dd>list of template directories, or directory of $index</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L495" target='_blank'>framework\libs\smarty\Smarty.class.php at line 495</a>

<h3 id="setConfigDir()">setConfigDir</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setConfigDir>Smarty</a></span> <span class='nf'>setConfigDir</span> (string|array template_dir, mixed config_dir)

<div class="details">
<p>Set config directory</p><dl>
<dt>Parameters:</dt>
<dd>template_dir - directory(s) of configuration sources</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L513" target='_blank'>framework\libs\smarty\Smarty.class.php at line 513</a>

<h3 id="addConfigDir()">addConfigDir</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addConfigDir>Smarty</a></span> <span class='nf'>addConfigDir</span> (string|array config_dir, string key)

<div class="details">
<p>Add config directory(s)</p><dl>
<dt>Parameters:</dt>
<dd>config_dir - directory(s) of config sources</dd>
<dd>key - of the array element to assign the config dir to</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L546" target='_blank'>framework\libs\smarty\Smarty.class.php at line 546</a>

<h3 id="getConfigDir()">getConfigDir</h3>
<span class='k'></span> <span class='nx'>array|string</span> <span class='nf'>getConfigDir</span> (mixed index)

<div class="details">
<p>Get config directory</p><dl>
<dt>Parameters:</dt>
<dd>index - of directory to get, null to get all</dd>
<dt>Returns:</dt>
<dd>configuration directory</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L561" target='_blank'>framework\libs\smarty\Smarty.class.php at line 561</a>

<h3 id="setPluginsDir()">setPluginsDir</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setPluginsDir>Smarty</a></span> <span class='nf'>setPluginsDir</span> (string|array plugins_dir)

<div class="details">
<p>Set plugins directory</p><dl>
<dt>Parameters:</dt>
<dd>plugins_dir - directory(s) of plugins</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L578" target='_blank'>framework\libs\smarty\Smarty.class.php at line 578</a>

<h3 id="addPluginsDir()">addPluginsDir</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addPluginsDir>Smarty</a></span> <span class='nf'>addPluginsDir</span> (object smarty, string plugins_dir)

<div class="details">
<p>Adds directory of plugin files</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd> - |array $ plugins folder</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L607" target='_blank'>framework\libs\smarty\Smarty.class.php at line 607</a>

<h3 id="getPluginsDir()">getPluginsDir</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getPluginsDir</span> ()

<div class="details">
<p>Get plugin directories</p><dl>
<dt>Returns:</dt>
<dd>list of plugin directories</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L618" target='_blank'>framework\libs\smarty\Smarty.class.php at line 618</a>

<h3 id="setCompileDir()">setCompileDir</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setCompileDir>Smarty</a></span> <span class='nf'>setCompileDir</span> (string compile_dir)

<div class="details">
<p>Set compile directory</p><dl>
<dt>Parameters:</dt>
<dd>compile_dir - directory to store compiled templates in</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L632" target='_blank'>framework\libs\smarty\Smarty.class.php at line 632</a>

<h3 id="getCompileDir()">getCompileDir</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getCompileDir</span> ()

<div class="details">
<p>Get compiled directory</p><dl>
<dt>Returns:</dt>
<dd>path to compiled templates</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L643" target='_blank'>framework\libs\smarty\Smarty.class.php at line 643</a>

<h3 id="setCacheDir()">setCacheDir</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setCacheDir>Smarty</a></span> <span class='nf'>setCacheDir</span> (string cache_dir)

<div class="details">
<p>Set cache directory</p><dl>
<dt>Parameters:</dt>
<dd>cache_dir - directory to store cached templates in</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L657" target='_blank'>framework\libs\smarty\Smarty.class.php at line 657</a>

<h3 id="getCacheDir()">getCacheDir</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getCacheDir</span> ()

<div class="details">
<p>Get cache directory</p><dl>
<dt>Returns:</dt>
<dd>path of cache directory</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L668" target='_blank'>framework\libs\smarty\Smarty.class.php at line 668</a>

<h3 id="setDefaultModifiers()">setDefaultModifiers</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setDefaultModifiers>Smarty</a></span> <span class='nf'>setDefaultModifiers</span> (array|string modifiers)

<div class="details">
<p>Set default modifiers</p><dl>
<dt>Parameters:</dt>
<dd>modifiers - modifier or list of modifiers to set</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L680" target='_blank'>framework\libs\smarty\Smarty.class.php at line 680</a>

<h3 id="addDefaultModifiers()">addDefaultModifiers</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addDefaultModifiers>Smarty</a></span> <span class='nf'>addDefaultModifiers</span> (array|string modifiers)

<div class="details">
<p>Add default modifiers</p><dl>
<dt>Parameters:</dt>
<dd>modifiers - modifier or list of modifiers to add</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L696" target='_blank'>framework\libs\smarty\Smarty.class.php at line 696</a>

<h3 id="getDefaultModifiers()">getDefaultModifiers</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getDefaultModifiers</span> ()

<div class="details">
<p>Get default modifiers</p><dl>
<dt>Returns:</dt>
<dd>list of default modifiers</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L709" target='_blank'>framework\libs\smarty\Smarty.class.php at line 709</a>

<h3 id="setAutoloadFilters()">setAutoloadFilters</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setAutoloadFilters>Smarty</a></span> <span class='nf'>setAutoloadFilters</span> (array filters, string type)

<div class="details">
<p>Set autoload filters</p><dl>
<dt>Parameters:</dt>
<dd>filters - filters to load automatically</dd>
<dd>type - "pre", "output", … specify the filter type to set. Defaults to none treating $filters' keys as the appropriate types</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L727" target='_blank'>framework\libs\smarty\Smarty.class.php at line 727</a>

<h3 id="addAutoloadFilters()">addAutoloadFilters</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#addAutoloadFilters>Smarty</a></span> <span class='nf'>addAutoloadFilters</span> (array filters, string type)

<div class="details">
<p>Add autoload filters</p><dl>
<dt>Parameters:</dt>
<dd>filters - filters to load automatically</dd>
<dd>type - "pre", "output", … specify the filter type to set. Defaults to none treating $filters' keys as the appropriate types</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L754" target='_blank'>framework\libs\smarty\Smarty.class.php at line 754</a>

<h3 id="getAutoloadFilters()">getAutoloadFilters</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getAutoloadFilters</span> (string type)

<div class="details">
<p>Get autoload filters</p><dl>
<dt>Parameters:</dt>
<dd>type - type of filter to get autoloads for. Defaults to all autoload filters</dd>
<dt>Returns:</dt>
<dd>array( 'type1' => array( 'filter1', 'filter2', … ) ) or array( 'filter1', 'filter2', …) if $type was specified</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L768" target='_blank'>framework\libs\smarty\Smarty.class.php at line 768</a>

<h3 id="getDebugTemplate()">getDebugTemplate</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getDebugTemplate</span> ()

<div class="details">
<p>return name of debugging template</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L780" target='_blank'>framework\libs\smarty\Smarty.class.php at line 780</a>

<h3 id="setDebugTemplate()">setDebugTemplate</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md#setDebugTemplate>Smarty</a></span> <span class='nf'>setDebugTemplate</span> (string tpl_name)

<div class="details">
<p>set the debug template</p><dl>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if file is not readable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L800" target='_blank'>framework\libs\smarty\Smarty.class.php at line 800</a>

<h3 id="createTemplate()">createTemplate</h3>
<span class='k'></span> <span class='nx'>object</span> <span class='nf'>createTemplate</span> (string template, mixed cache_id, mixed compile_id, object parent, boolean do_clone)

<div class="details">
<p>creates a template object</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>parent - next higher level of Smarty variables</dd>
<dd>do_clone - flag is Smarty object shall be cloned</dd>
<dt>Returns:</dt>
<dd>template object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L866" target='_blank'>framework\libs\smarty\Smarty.class.php at line 866</a>

<h3 id="loadPlugin()">loadPlugin</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>loadPlugin</span> (string plugin_name, bool check)

<div class="details">
<p>Takes unknown classes and loads plugin files for them
class name format: Smarty_PluginType_PluginName
plugin filename format: plugintype.pluginname.php</p><dl>
<dt>Parameters:</dt>
<dd>plugin_name - class plugin name to load</dd>
<dd>check - check if already loaded</dd>
<dt>Returns:</dt>
<dd>|boolean filepath of loaded file or false</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L934" target='_blank'>framework\libs\smarty\Smarty.class.php at line 934</a>

<h3 id="compileAllTemplates()">compileAllTemplates</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>compileAllTemplates</span> (string extension, bool force_compile, int time_limit, int max_errors, str extention)

<div class="details">
<p>Compile all template files</p><dl>
<dt>Parameters:</dt>
<dd>extension - file extension</dd>
<dd>force_compile - force all to recompile</dd>
<dd></dd>
<dd></dd>
<dt>Returns:</dt>
<dd>number of template files recompiled</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L948" target='_blank'>framework\libs\smarty\Smarty.class.php at line 948</a>

<h3 id="compileAllConfig()">compileAllConfig</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>compileAllConfig</span> (string extension, bool force_compile, int time_limit, int max_errors, str extention)

<div class="details">
<p>Compile all config files</p><dl>
<dt>Parameters:</dt>
<dd>extension - file extension</dd>
<dd>force_compile - force all to recompile</dd>
<dd></dd>
<dd></dd>
<dt>Returns:</dt>
<dd>number of template files recompiled</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L961" target='_blank'>framework\libs\smarty\Smarty.class.php at line 961</a>

<h3 id="clearCompiledTemplate()">clearCompiledTemplate</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clearCompiledTemplate</span> (string resource_name, string compile_id, integer exp_time)

<div class="details">
<p>Delete compiled template file</p><dl>
<dt>Parameters:</dt>
<dd>resource_name - template name</dd>
<dd>compile_id - compile id</dd>
<dd>exp_time - expiration time</dd>
<dt>Returns:</dt>
<dd>number of template files deleted</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L973" target='_blank'>framework\libs\smarty\Smarty.class.php at line 973</a>

<h3 id="getTags()">getTags</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getTags</span> (object templae, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Return array of tag/attributes of all tags used by an template</p><dl>
<dt>Parameters:</dt>
<dd>templae - template object</dd>
<dt>Returns:</dt>
<dd>of tag/attributes</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L984" target='_blank'>framework\libs\smarty\Smarty.class.php at line 984</a>

<h3 id="testInstall()">testInstall</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>testInstall</span> (array errors)

<div class="details">
<p>Run installation test</p><dl>
<dt>Parameters:</dt>
<dd>errors - Array to write errors into, rather than outputting them</dd>
<dt>Returns:</dt>
<dd>true if setup is fine, false if something is wrong</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L996" target='_blank'>framework\libs\smarty\Smarty.class.php at line 996</a>

<h3 id="mutingErrorHandler()">mutingErrorHandler</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>mutingErrorHandler</span> (integer errno, mixed errstr, mixed errfile, mixed errline, mixed errcontext)

<div class="details">
<p>Error Handler to mute expected messages</p><dl>
<dt>See Also:</dt>
<dd><code><a href="http://php.net/set_error_handler">http://php.net/set_error_handler</a></code></dd>
<dt>Parameters:</dt>
<dd>errno - Error level</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L1041" target='_blank'>framework\libs\smarty\Smarty.class.php at line 1041</a>

<h3 id="muteExpectedErrors()">muteExpectedErrors</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>muteExpectedErrors</span> ()

<div class="details">
<p>Enable error handler to mute expected messages</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L1073" target='_blank'>framework\libs\smarty\Smarty.class.php at line 1073</a>

<h3 id="unmuteExpectedErrors()">unmuteExpectedErrors</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>unmuteExpectedErrors</span> ()

<div class="details">
<p>Disable error handler muting expected messages</p>
</div>

- - -

