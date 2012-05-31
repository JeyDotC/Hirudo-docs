- - -

**Smarty\Smarty_Resource**
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 18</div>
#Class Smarty_Resource#

**Smarty_Resource**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_resource_extends.html">Smarty_Internal_Resource_Extends</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_resource_file.html">Smarty_Internal_Resource_File</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_resource_registered.html">Smarty_Internal_Resource_Registered</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_resource_string.html">Smarty_Internal_Resource_String</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_custom.html">Smarty_Resource_Custom</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_recompiled.html">Smarty_Resource_Recompiled</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_uncompiled.html">Smarty_Resource_Uncompiled</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Smarty_Resource**</p>

<div class="comment" id="overview_description"><p>Smarty Resource Plugin</p><p>Base implementation for resource plugins</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#compileds">$compileds</a></p><p class="description">cache for Smarty_Template_Compiled instances</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compiler_class">$compiler_class</a></p><p class="description">Name of the Class to compile this resource's contents with</p></td>
</tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#resources">$resources</a></p><p class="description">cache for Smarty_Resource instances</p></td>
</tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#sources">$sources</a></p><p class="description">cache for Smarty_Template_Source instances</p></td>
</tr>
<tr>
<td class="type">protected static  array</td>
<td class="description"><p class="name"><a href="#sysplugins">$sysplugins</a></p><p class="description">resource types provided by the core</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#template_lexer_class">$template_lexer_class</a></p><p class="description">Name of the Class to tokenize this resource's contents with</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#template_parser_class">$template_parser_class</a></p><p class="description">Name of the Class to parse this resource's contents with</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">abstract  string</td>
<td class="description"><p class="name"><a href="#getContent">getContent</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Load template's source into current template objectThe loaded source is assigned to $_template->source->content directly.}</p></td>
</tr>
<tr>
<td class="type">abstract  void</td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populateTimestamp">populateTimestamp</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">populate Source Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td class="type">protected  string</td>
<td class="description"><p class="name"><a href="#buildUniqueResourceName">buildUniqueResourceName</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name)</p><p class="description">modify resource_name according to resource handlers specifications</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populateCompiledFilepath">populateCompiledFilepath</a>(<a href="../smarty/smarty_template_compiled.html">Smarty_Template_Compiled</a> compiled, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Compiled Object with compiled filepath</p></td>
</tr>
<tr>
<td class="type">protected  string</td>
<td class="description"><p class="name"><a href="#buildFilepath">buildFilepath</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">build template filepath by traversing the template_dir array</p></td>
</tr>
<tr>
<td class="type">protected  bool</td>
<td class="description"><p class="name"><a href="#fileExists">fileExists</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, string file)</p><p class="description">test is file exists and save timestamp</p></td>
</tr>
<tr>
<td class="type">protected  string</td>
<td class="description"><p class="name"><a href="#getBasename">getBasename</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Determine basename for compiled filename</p></td>
</tr>
<tr>
<td class="type">static  <a href="../smarty/smarty_resource.html">Smarty_Resource</a></td>
<td class="description"><p class="name"><a href="#load">load</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, string type)</p><p class="description">Load Resource Handler</p></td>
</tr>
<tr>
<td class="type">protected static  void</td>
<td class="description"><p class="name"><a href="#parseResourceName">parseResourceName</a>(string resource_name, string default_resource, string &$name, string &$type, mixed name, mixed type)</p><p class="description">extract resource_type and resource_name from template_resource and config_resource</p></td>
</tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#getUniqueTemplateName">getUniqueTemplateName</a>(string smarty, string template_resource)</p><p class="description">modify template_resource according to resource handlers specifications</p></td>
</tr>
<tr>
<td class="type">static  <a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a></td>
<td class="description"><p class="name"><a href="#source">source</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty.html">Smarty</a> smarty, string template_resource)</p><p class="description">initialize Source Object for given resourceEither [$_template] or [$smarty, $template_resource] must be specified</p></td>
</tr>
<tr>
<td class="type">static  <a href="../smarty/smarty_config_source.html">Smarty_Config_Source</a></td>
<td class="description"><p class="name"><a href="#config">config</a>(<a href="../smarty/smarty_internal_config.html">Smarty_Internal_Config</a> _config)</p><p class="description">initialize Config Source Object for given resource</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 28</div>
<h3 id="compileds">compileds</h3>
```php
public static  array **$compileds** = array()```
<div class="details">
<p>cache for Smarty_Template_Compiled instances</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 44</div>
<h3 id="compiler_class">compiler_class</h3>
```php
public  string **$compiler_class** = 'Smarty_Internal_SmartyTemplateCompiler'```
<div class="details">
<p>Name of the Class to compile this resource's contents with</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 33</div>
<h3 id="resources">resources</h3>
```php
public static  array **$resources** = array()```
<div class="details">
<p>cache for Smarty_Resource instances</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 23</div>
<h3 id="sources">sources</h3>
```php
public static  array **$sources** = array()```
<div class="details">
<p>cache for Smarty_Template_Source instances</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 38</div>
<h3 id="sysplugins">sysplugins</h3>
```php
protected static  array **$sysplugins** = array(...)```
<div class="details">
<p>resource types provided by the core</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 50</div>
<h3 id="template_lexer_class">template_lexer_class</h3>
```php
public  string **$template_lexer_class** = 'Smarty_Internal_Templatelexer'```
<div class="details">
<p>Name of the Class to tokenize this resource's contents with</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 56</div>
<h3 id="template_parser_class">template_parser_class</h3>
```php
public  string **$template_parser_class** = 'Smarty_Internal_Templateparser'```
<div class="details">
<p>Name of the Class to parse this resource's contents with</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 67</div>
<h3 id="getContent()">getContent</h3>
```php
public abstract  string **getContent**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)```
<div class="details">
<p>Load template's source into current template object</p><p>The loaded source is assigned to $_template->source->content directly.}</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>template source</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if source cannot be loaded</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 75</div>
<h3 id="populate()">populate</h3>
```php
public abstract  void **populate**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)```
<div class="details">
<p>populate Source Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 82</div>
<h3 id="populateTimestamp()">populateTimestamp</h3>
```php
public  void **populateTimestamp**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)```
<div class="details">
<p>populate Source Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 95</div>
<h3 id="buildUniqueResourceName()">buildUniqueResourceName</h3>
```php
protected  string **buildUniqueResourceName**(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name)```
<div class="details">
<p>modify resource_name according to resource handlers specifications</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty instance</dd>
<dd>resource_name - resource_name to make unique</dd>
<dt>Returns:</dt>
<dd>unique resource name</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 106</div>
<h3 id="populateCompiledFilepath()">populateCompiledFilepath</h3>
```php
public  void **populateCompiledFilepath**(<a href="../smarty/smarty_template_compiled.html">Smarty_Template_Compiled</a> compiled, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)```
<div class="details">
<p>populate Compiled Object with compiled filepath</p><dl>
<dt>Parameters:</dt>
<dd>compiled - compiled object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 149</div>
<h3 id="buildFilepath()">buildFilepath</h3>
```php
protected  string **buildFilepath**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)```
<div class="details">
<p>build template filepath by traversing the template_dir array</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
<dt>Returns:</dt>
<dd>fully qualified filepath</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if default template handler is registered but not callable</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 316</div>
<h3 id="fileExists()">fileExists</h3>
```php
protected  bool **fileExists**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, string file)```
<div class="details">
<p>test is file exists and save timestamp</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>file - file name</dd>
<dt>Returns:</dt>
<dd>true if file exists</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 329</div>
<h3 id="getBasename()">getBasename</h3>
```php
protected  string **getBasename**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)```
<div class="details">
<p>Determine basename for compiled filename</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>resource's basename</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 341</div>
<h3 id="load()">load</h3>
```php
public static  <a href="../smarty/smarty_resource.html">Smarty_Resource</a> **load**(<a href="../smarty/smarty.html">Smarty</a> smarty, string type)```
<div class="details">
<p>Load Resource Handler</p><dl>
<dt>Parameters:</dt>
<dd>smarty - smarty object</dd>
<dd>type - name of the resource</dd>
<dt>Returns:</dt>
<dd>Resource Handler</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 427</div>
<h3 id="parseResourceName()">parseResourceName</h3>
```php
protected static  void **parseResourceName**(string resource_name, string default_resource, string &$name, string &$type, mixed name, mixed type)```
<div class="details">
<p>extract resource_type and resource_name from template_resource and config_resource</p><dl>
<dt>Note:</dt>
<dd>"C:/foo.tpl" was forced to file resource up till Smarty 3.1.3 (including).</dd>
<dt>Parameters:</dt>
<dd>resource_name - template_resource or config_resource to parse</dd>
<dd>default_resource - the default resource_type defined in $smarty</dd>
<dd>&$name - the parsed resource name</dd>
<dd>&$type - the parsed resource type</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 457</div>
<h3 id="getUniqueTemplateName()">getUniqueTemplateName</h3>
```php
public static  string **getUniqueTemplateName**(string smarty, string template_resource)```
<div class="details">
<p>modify template_resource according to resource handlers specifications</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty instance</dd>
<dd>template_resource - template_resource to extracate resource handler and name of</dd>
<dt>Returns:</dt>
<dd>unique resource name</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 475</div>
<h3 id="source()">source</h3>
```php
public static  <a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> **source**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty.html">Smarty</a> smarty, string template_resource)```
<div class="details">
<p>initialize Source Object for given resource</p><p>Either [$_template] or [$smarty, $template_resource] must be specified</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>smarty - smarty object</dd>
<dd>template_resource - resource identifier</dd>
<dt>Returns:</dt>
<dd>Source Object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 508</div>
<h3 id="config()">config</h3>
```php
public static  <a href="../smarty/smarty_config_source.html">Smarty_Config_Source</a> **config**(<a href="../smarty/smarty_internal_config.html">Smarty_Internal_Config</a> _config)```
<div class="details">
<p>initialize Config Source Object for given resource</p><dl>
<dt>Parameters:</dt>
<dd>_config - config object</dd>
<dt>Returns:</dt>
<dd>Source Object</dd>
</dl>
</div>

- - -

