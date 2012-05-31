- - -

**Smarty\Smarty**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line106" class="location">framework\libs\smarty\Smarty.class.php at line 106</a>

# Class Smarty #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>\n    *<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html">Smarty_Internal_TemplateBase</a>\n        *** Smarty **\n</pre>

<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smartybc.html">SmartyBC</a> </dd>
</dl>

- - -

<p class="signature">public  class **Smarty**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html">Smarty_Internal_TemplateBase</a>

</p>

<div class="comment" id="overview_description"><p>This is the main Smarty class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#_cacheresource_handlers">$_cacheresource_handlers</a></p><p class="description">cache resource handler cache</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#_current_file">$_current_file</a></p><p class="description">required by the compiler for BC</p></td>
</tr>
<tr>
<td class="type"> int</td>
<td class="description"><p class="name"><a href="#_dir_perms">$_dir_perms</a></p><p class="description">default dir permissions</p></td>
</tr>
<tr>
<td class="type"> int</td>
<td class="description"><p class="name"><a href="#_file_perms">$_file_perms</a></p><p class="description">default file permissions</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#_parserdebug">$_parserdebug</a></p><p class="description">internal flag to enable parser debugging</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#_resource_handlers">$_resource_handlers</a></p><p class="description">resource handler cache</p></td>
</tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#_smarty_vars">$_smarty_vars</a></p><p class="description">global internal smarty vars</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#_tag_stack">$_tag_stack</a></p><p class="description">block tag hierarchy</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#autoload_filters">$autoload_filters</a></p><p class="description">autoload filter</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#default_modifiers">$default_modifiers</a></p><p class="description">default modifier</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#escape_html">$escape_html</a></p><p class="description">autoescape variable output</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#merged_templates_func">$merged_templates_func</a></p><p class="description">Saved parameter of merged templates during compilation</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#registered_cache_resources">$registered_cache_resources</a></p><p class="description">registered cache resources</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#registered_classes">$registered_classes</a></p><p class="description">registered classes</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#registered_filters">$registered_filters</a></p><p class="description">registered filters</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#registered_objects">$registered_objects</a></p><p class="description">registered objects</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#registered_resources">$registered_resources</a></p><p class="description">registered resources</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#smarty">$smarty</a></p><p class="description">self pointer to Smarty object</p></td>
</tr>
<tr>
<td class="type"> int</td>
<td class="description"><p class="name"><a href="#start_time">$start_time</a></p><p class="description">start time for execution time calculation</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>()</p><p class="description">Initialize new Smarty object</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#templateExists()">templateExists</a>(string resource_name)</p><p class="description">Check if a template resource exists</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getGlobal()">getGlobal</a>(object smarty, string varname)</p><p class="description">Returns a single or all global  variables</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#clearAllCache()">clearAllCache</a>(integer exp_time, string type)</p><p class="description">Empty cache folder</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#clearCache()">clearCache</a>(string template_name, string cache_id, string compile_id, integer exp_time, string type)</p><p class="description">Empty cache for a specific template</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#enableSecurity()">enableSecurity</a>(string|Smarty_Security security_class)</p><p class="description">Loads security class and enables security</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#disableSecurity()">disableSecurity</a>()</p><p class="description">Disable security</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#setTemplateDir()">setTemplateDir</a>(string|array template_dir)</p><p class="description">Set template directory</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#addTemplateDir()">addTemplateDir</a>(string|array template_dir, string key)</p><p class="description">Add template directory(s)</p></td>
</tr>
<tr>
<td class="type"> array|string</td>
<td class="description"><p class="name"><a href="#getTemplateDir()">getTemplateDir</a>(mixed index)</p><p class="description">Get template directories</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#setConfigDir()">setConfigDir</a>(string|array template_dir, mixed config_dir)</p><p class="description">Set config directory</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#addConfigDir()">addConfigDir</a>(string|array config_dir, string key)</p><p class="description">Add config directory(s)</p></td>
</tr>
<tr>
<td class="type"> array|string</td>
<td class="description"><p class="name"><a href="#getConfigDir()">getConfigDir</a>(mixed index)</p><p class="description">Get config directory</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#setPluginsDir()">setPluginsDir</a>(string|array plugins_dir)</p><p class="description">Set plugins directory</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#addPluginsDir()">addPluginsDir</a>(object smarty, string plugins_dir)</p><p class="description">Adds directory of plugin files</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getPluginsDir()">getPluginsDir</a>()</p><p class="description">Get plugin directories</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#setCompileDir()">setCompileDir</a>(string compile_dir)</p><p class="description">Set compile directory</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getCompileDir()">getCompileDir</a>()</p><p class="description">Get compiled directory</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#setCacheDir()">setCacheDir</a>(string cache_dir)</p><p class="description">Set cache directory</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getCacheDir()">getCacheDir</a>()</p><p class="description">Get cache directory</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#setDefaultModifiers()">setDefaultModifiers</a>(array|string modifiers)</p><p class="description">Set default modifiers</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#addDefaultModifiers()">addDefaultModifiers</a>(array|string modifiers)</p><p class="description">Add default modifiers</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getDefaultModifiers()">getDefaultModifiers</a>()</p><p class="description">Get default modifiers</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#setAutoloadFilters()">setAutoloadFilters</a>(array filters, string type)</p><p class="description">Set autoload filters</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#addAutoloadFilters()">addAutoloadFilters</a>(array filters, string type)</p><p class="description">Add autoload filters</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getAutoloadFilters()">getAutoloadFilters</a>(string type)</p><p class="description">Get autoload filters</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getDebugTemplate()">getDebugTemplate</a>()</p><p class="description">return name of debugging template</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#setDebugTemplate()">setDebugTemplate</a>(string tpl_name)</p><p class="description">set the debug template</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#createTemplate()">createTemplate</a>(string template, mixed cache_id, mixed compile_id, object parent, boolean do_clone)</p><p class="description">creates a template object</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#loadPlugin()">loadPlugin</a>(string plugin_name, bool check)</p><p class="description">Takes unknown classes and loads plugin files for them
class name format: Smarty_PluginType_PluginName
plugin filename format: plugintype.pluginname.php</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#compileAllTemplates()">compileAllTemplates</a>(string extension, bool force_compile, int time_limit, int max_errors, str extention)</p><p class="description">Compile all template files</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#compileAllConfig()">compileAllConfig</a>(string extension, bool force_compile, int time_limit, int max_errors, str extention)</p><p class="description">Compile all config files</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#clearCompiledTemplate()">clearCompiledTemplate</a>(string resource_name, string compile_id, integer exp_time)</p><p class="description">Delete compiled template file</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getTags()">getTags</a>(object templae, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)</p><p class="description">Return array of tag/attributes of all tags used by an template</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#testInstall()">testInstall</a>(array errors)</p><p class="description">Run installation test</p></td>
</tr>
<tr>
<td class="type">static  boolean</td>
<td class="description"><p class="name"><a href="#mutingErrorHandler()">mutingErrorHandler</a>(integer errno, mixed errstr, mixed errfile, mixed errline, mixed errcontext)</p><p class="description">Error Handler to mute expected messages</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#muteExpectedErrors()">muteExpectedErrors</a>()</p><p class="description">Enable error handler to mute expected messages</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#unmuteExpectedErrors()">unmuteExpectedErrors</a>()</p><p class="description">Disable error handler muting expected messages</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_TemplateBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#createData()">createData</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#display()">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#fetch()">fetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#getRegisteredObject()">getRegisteredObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#isCached()">isCached</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#loadFilter()">loadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerCacheResource()">registerCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerClass()">registerClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultConfigHandler()">registerDefaultConfigHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultPluginHandler()">registerDefaultPluginHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerDefaultTemplateHandler()">registerDefaultTemplateHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerFilter()">registerFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerObject()">registerObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerPlugin()">registerPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#registerResource()">registerResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unloadFilter()">unloadFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterCacheResource()">unregisterCacheResource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterFilter()">unregisterFilter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterObject()">unregisterObject</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterPlugin()">unregisterPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html#unregisterResource()">unregisterResource</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#append()">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#appendByRef()">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assign()">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignByRef()">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignGlobal()">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAllAssign()">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAssign()">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearConfig()">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#configLoad()">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVariable()">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVars()">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getStreamVariable()">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getTemplateVars()">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getVariable()">getVariable</a></td></tr></table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line150" class="location">framework\libs\smarty\Smarty.class.php at line 150</a>

<h3 id="_cacheresource_handlers">_cacheresource_handlers</h3>
```php
public  array **$_cacheresource_handlers** = array()```
<div class="details">
<p>cache resource handler cache</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line200" class="location">framework\libs\smarty\Smarty.class.php at line 200</a>

<h3 id="_current_file">_current_file</h3>
```php
public  string **$_current_file** = null```
<div class="details">
<p>required by the compiler for BC</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line185" class="location">framework\libs\smarty\Smarty.class.php at line 185</a>

<h3 id="_dir_perms">_dir_perms</h3>
```php
public  int **$_dir_perms** = 0771```
<div class="details">
<p>default dir permissions</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line180" class="location">framework\libs\smarty\Smarty.class.php at line 180</a>

<h3 id="_file_perms">_file_perms</h3>
```php
public  int **$_file_perms** = 0644```
<div class="details">
<p>default file permissions</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line205" class="location">framework\libs\smarty\Smarty.class.php at line 205</a>

<h3 id="_parserdebug">_parserdebug</h3>
```php
public  bool **$_parserdebug** = false```
<div class="details">
<p>internal flag to enable parser debugging</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line140" class="location">framework\libs\smarty\Smarty.class.php at line 140</a>

<h3 id="_resource_handlers">_resource_handlers</h3>
```php
public  array **$_resource_handlers** = array()```
<div class="details">
<p>resource handler cache</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line170" class="location">framework\libs\smarty\Smarty.class.php at line 170</a>

<h3 id="_smarty_vars">_smarty_vars</h3>
```php
public static  array **$_smarty_vars** = array()```
<div class="details">
<p>global internal smarty vars</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line190" class="location">framework\libs\smarty\Smarty.class.php at line 190</a>

<h3 id="_tag_stack">_tag_stack</h3>
```php
public  array **$_tag_stack** = array()```
<div class="details">
<p>block tag hierarchy</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line155" class="location">framework\libs\smarty\Smarty.class.php at line 155</a>

<h3 id="autoload_filters">autoload_filters</h3>
```php
public  array **$autoload_filters** = array()```
<div class="details">
<p>autoload filter</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line160" class="location">framework\libs\smarty\Smarty.class.php at line 160</a>

<h3 id="default_modifiers">default_modifiers</h3>
```php
public  array **$default_modifiers** = array()```
<div class="details">
<p>default modifier</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line165" class="location">framework\libs\smarty\Smarty.class.php at line 165</a>

<h3 id="escape_html">escape_html</h3>
```php
public  boolean **$escape_html** = false```
<div class="details">
<p>autoescape variable output</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line211" class="location">framework\libs\smarty\Smarty.class.php at line 211</a>

<h3 id="merged_templates_func">merged_templates_func</h3>
```php
public  array **$merged_templates_func** = array()```
<div class="details">
<p>Saved parameter of merged templates during compilation</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line145" class="location">framework\libs\smarty\Smarty.class.php at line 145</a>

<h3 id="registered_cache_resources">registered_cache_resources</h3>
```php
public  array **$registered_cache_resources** = array()```
<div class="details">
<p>registered cache resources</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line125" class="location">framework\libs\smarty\Smarty.class.php at line 125</a>

<h3 id="registered_classes">registered_classes</h3>
```php
public  array **$registered_classes** = array()```
<div class="details">
<p>registered classes</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line130" class="location">framework\libs\smarty\Smarty.class.php at line 130</a>

<h3 id="registered_filters">registered_filters</h3>
```php
public  array **$registered_filters** = array()```
<div class="details">
<p>registered filters</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line120" class="location">framework\libs\smarty\Smarty.class.php at line 120</a>

<h3 id="registered_objects">registered_objects</h3>
```php
public  array **$registered_objects** = array()```
<div class="details">
<p>registered objects</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line135" class="location">framework\libs\smarty\Smarty.class.php at line 135</a>

<h3 id="registered_resources">registered_resources</h3>
```php
public  array **$registered_resources** = array()```
<div class="details">
<p>registered resources</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line195" class="location">framework\libs\smarty\Smarty.class.php at line 195</a>

<h3 id="smarty">smarty</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **$smarty**```
<div class="details">
<p>self pointer to Smarty object</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line175" class="location">framework\libs\smarty\Smarty.class.php at line 175</a>

<h3 id="start_time">start_time</h3>
```php
public  int **$start_time** = 0```
<div class="details">
<p>start time for execution time calculation</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line218" class="location">framework\libs\smarty\Smarty.class.php at line 218</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
<p>Initialize new Smarty object</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line315" class="location">framework\libs\smarty\Smarty.class.php at line 315</a>

<h3 id="templateExists()">templateExists</h3>
```php
public  boolean **templateExists**(string resource_name)```
<div class="details">
<p>Check if a template resource exists</p><dl>
<dt>Parameters:</dt>
<dd>resource_name - template name</dd>
<dt>Returns:</dt>
<dd>status</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line333" class="location">framework\libs\smarty\Smarty.class.php at line 333</a>

<h3 id="getGlobal()">getGlobal</h3>
```php
public  string **getGlobal**(object smarty, string varname)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line357" class="location">framework\libs\smarty\Smarty.class.php at line 357</a>

<h3 id="clearAllCache()">clearAllCache</h3>
```php
public  integer **clearAllCache**(integer exp_time, string type)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line375" class="location">framework\libs\smarty\Smarty.class.php at line 375</a>

<h3 id="clearCache()">clearCache</h3>
```php
public  integer **clearCache**(string template_name, string cache_id, string compile_id, integer exp_time, string type)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line390" class="location">framework\libs\smarty\Smarty.class.php at line 390</a>

<h3 id="enableSecurity()">enableSecurity</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **enableSecurity**(string|Smarty_Security security_class)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line416" class="location">framework\libs\smarty\Smarty.class.php at line 416</a>

<h3 id="disableSecurity()">disableSecurity</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **disableSecurity**()```
<div class="details">
<p>Disable security</p><dl>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line429" class="location">framework\libs\smarty\Smarty.class.php at line 429</a>

<h3 id="setTemplateDir()">setTemplateDir</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **setTemplateDir**(string|array template_dir)```
<div class="details">
<p>Set template directory</p><dl>
<dt>Parameters:</dt>
<dd>template_dir - directory(s) of template sources</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line448" class="location">framework\libs\smarty\Smarty.class.php at line 448</a>

<h3 id="addTemplateDir()">addTemplateDir</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **addTemplateDir**(string|array template_dir, string key)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line480" class="location">framework\libs\smarty\Smarty.class.php at line 480</a>

<h3 id="getTemplateDir()">getTemplateDir</h3>
```php
public  array|string **getTemplateDir**(mixed index)```
<div class="details">
<p>Get template directories</p><dl>
<dt>Parameters:</dt>
<dd>index - of directory to get, null to get all</dd>
<dt>Returns:</dt>
<dd>list of template directories, or directory of $index</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line495" class="location">framework\libs\smarty\Smarty.class.php at line 495</a>

<h3 id="setConfigDir()">setConfigDir</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **setConfigDir**(string|array template_dir, mixed config_dir)```
<div class="details">
<p>Set config directory</p><dl>
<dt>Parameters:</dt>
<dd>template_dir - directory(s) of configuration sources</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line513" class="location">framework\libs\smarty\Smarty.class.php at line 513</a>

<h3 id="addConfigDir()">addConfigDir</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **addConfigDir**(string|array config_dir, string key)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line546" class="location">framework\libs\smarty\Smarty.class.php at line 546</a>

<h3 id="getConfigDir()">getConfigDir</h3>
```php
public  array|string **getConfigDir**(mixed index)```
<div class="details">
<p>Get config directory</p><dl>
<dt>Parameters:</dt>
<dd>index - of directory to get, null to get all</dd>
<dt>Returns:</dt>
<dd>configuration directory</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line561" class="location">framework\libs\smarty\Smarty.class.php at line 561</a>

<h3 id="setPluginsDir()">setPluginsDir</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **setPluginsDir**(string|array plugins_dir)```
<div class="details">
<p>Set plugins directory</p><dl>
<dt>Parameters:</dt>
<dd>plugins_dir - directory(s) of plugins</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line578" class="location">framework\libs\smarty\Smarty.class.php at line 578</a>

<h3 id="addPluginsDir()">addPluginsDir</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **addPluginsDir**(object smarty, string plugins_dir)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line607" class="location">framework\libs\smarty\Smarty.class.php at line 607</a>

<h3 id="getPluginsDir()">getPluginsDir</h3>
```php
public  array **getPluginsDir**()```
<div class="details">
<p>Get plugin directories</p><dl>
<dt>Returns:</dt>
<dd>list of plugin directories</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line618" class="location">framework\libs\smarty\Smarty.class.php at line 618</a>

<h3 id="setCompileDir()">setCompileDir</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **setCompileDir**(string compile_dir)```
<div class="details">
<p>Set compile directory</p><dl>
<dt>Parameters:</dt>
<dd>compile_dir - directory to store compiled templates in</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line632" class="location">framework\libs\smarty\Smarty.class.php at line 632</a>

<h3 id="getCompileDir()">getCompileDir</h3>
```php
public  string **getCompileDir**()```
<div class="details">
<p>Get compiled directory</p><dl>
<dt>Returns:</dt>
<dd>path to compiled templates</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line643" class="location">framework\libs\smarty\Smarty.class.php at line 643</a>

<h3 id="setCacheDir()">setCacheDir</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **setCacheDir**(string cache_dir)```
<div class="details">
<p>Set cache directory</p><dl>
<dt>Parameters:</dt>
<dd>cache_dir - directory to store cached templates in</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line657" class="location">framework\libs\smarty\Smarty.class.php at line 657</a>

<h3 id="getCacheDir()">getCacheDir</h3>
```php
public  string **getCacheDir**()```
<div class="details">
<p>Get cache directory</p><dl>
<dt>Returns:</dt>
<dd>path of cache directory</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line668" class="location">framework\libs\smarty\Smarty.class.php at line 668</a>

<h3 id="setDefaultModifiers()">setDefaultModifiers</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **setDefaultModifiers**(array|string modifiers)```
<div class="details">
<p>Set default modifiers</p><dl>
<dt>Parameters:</dt>
<dd>modifiers - modifier or list of modifiers to set</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line680" class="location">framework\libs\smarty\Smarty.class.php at line 680</a>

<h3 id="addDefaultModifiers()">addDefaultModifiers</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **addDefaultModifiers**(array|string modifiers)```
<div class="details">
<p>Add default modifiers</p><dl>
<dt>Parameters:</dt>
<dd>modifiers - modifier or list of modifiers to add</dd>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line696" class="location">framework\libs\smarty\Smarty.class.php at line 696</a>

<h3 id="getDefaultModifiers()">getDefaultModifiers</h3>
```php
public  array **getDefaultModifiers**()```
<div class="details">
<p>Get default modifiers</p><dl>
<dt>Returns:</dt>
<dd>list of default modifiers</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line709" class="location">framework\libs\smarty\Smarty.class.php at line 709</a>

<h3 id="setAutoloadFilters()">setAutoloadFilters</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **setAutoloadFilters**(array filters, string type)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line727" class="location">framework\libs\smarty\Smarty.class.php at line 727</a>

<h3 id="addAutoloadFilters()">addAutoloadFilters</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **addAutoloadFilters**(array filters, string type)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line754" class="location">framework\libs\smarty\Smarty.class.php at line 754</a>

<h3 id="getAutoloadFilters()">getAutoloadFilters</h3>
```php
public  array **getAutoloadFilters**(string type)```
<div class="details">
<p>Get autoload filters</p><dl>
<dt>Parameters:</dt>
<dd>type - type of filter to get autoloads for. Defaults to all autoload filters</dd>
<dt>Returns:</dt>
<dd>array( 'type1' => array( 'filter1', 'filter2', … ) ) or array( 'filter1', 'filter2', …) if $type was specified</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line768" class="location">framework\libs\smarty\Smarty.class.php at line 768</a>

<h3 id="getDebugTemplate()">getDebugTemplate</h3>
```php
public  string **getDebugTemplate**()```
<div class="details">
<p>return name of debugging template</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line780" class="location">framework\libs\smarty\Smarty.class.php at line 780</a>

<h3 id="setDebugTemplate()">setDebugTemplate</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **setDebugTemplate**(string tpl_name)```
<div class="details">
<p>set the debug template</p><dl>
<dt>Returns:</dt>
<dd>current Smarty instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if file is not readable</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line800" class="location">framework\libs\smarty\Smarty.class.php at line 800</a>

<h3 id="createTemplate()">createTemplate</h3>
```php
public  object **createTemplate**(string template, mixed cache_id, mixed compile_id, object parent, boolean do_clone)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line866" class="location">framework\libs\smarty\Smarty.class.php at line 866</a>

<h3 id="loadPlugin()">loadPlugin</h3>
```php
public  string **loadPlugin**(string plugin_name, bool check)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line934" class="location">framework\libs\smarty\Smarty.class.php at line 934</a>

<h3 id="compileAllTemplates()">compileAllTemplates</h3>
```php
public  integer **compileAllTemplates**(string extension, bool force_compile, int time_limit, int max_errors, str extention)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line948" class="location">framework\libs\smarty\Smarty.class.php at line 948</a>

<h3 id="compileAllConfig()">compileAllConfig</h3>
```php
public  integer **compileAllConfig**(string extension, bool force_compile, int time_limit, int max_errors, str extention)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line961" class="location">framework\libs\smarty\Smarty.class.php at line 961</a>

<h3 id="clearCompiledTemplate()">clearCompiledTemplate</h3>
```php
public  integer **clearCompiledTemplate**(string resource_name, string compile_id, integer exp_time)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line973" class="location">framework\libs\smarty\Smarty.class.php at line 973</a>

<h3 id="getTags()">getTags</h3>
```php
public  array **getTags**(object templae, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)```
<div class="details">
<p>Return array of tag/attributes of all tags used by an template</p><dl>
<dt>Parameters:</dt>
<dd>templae - template object</dd>
<dt>Returns:</dt>
<dd>of tag/attributes</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line984" class="location">framework\libs\smarty\Smarty.class.php at line 984</a>

<h3 id="testInstall()">testInstall</h3>
```php
public  boolean **testInstall**(array errors)```
<div class="details">
<p>Run installation test</p><dl>
<dt>Parameters:</dt>
<dd>errors - Array to write errors into, rather than outputting them</dd>
<dt>Returns:</dt>
<dd>true if setup is fine, false if something is wrong</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line996" class="location">framework\libs\smarty\Smarty.class.php at line 996</a>

<h3 id="mutingErrorHandler()">mutingErrorHandler</h3>
```php
public static  boolean **mutingErrorHandler**(integer errno, mixed errstr, mixed errfile, mixed errline, mixed errcontext)```
<div class="details">
<p>Error Handler to mute expected messages</p><dl>
<dt>See Also:</dt>
<dd><code><a href="http://php.net/set_error_handler">http://php.net/set_error_handler</a></code></dd>
<dt>Parameters:</dt>
<dd>errno - Error level</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line1041" class="location">framework\libs\smarty\Smarty.class.php at line 1041</a>

<h3 id="muteExpectedErrors()">muteExpectedErrors</h3>
```php
public static  void **muteExpectedErrors**()```
<div class="details">
<p>Enable error handler to mute expected messages</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/Smarty.class.php.md#line1073" class="location">framework\libs\smarty\Smarty.class.php at line 1073</a>

<h3 id="unmuteExpectedErrors()">unmuteExpectedErrors</h3>
```php
public static  void **unmuteExpectedErrors**()```
<div class="details">
<p>Disable error handler muting expected messages</p></div>

- - -

