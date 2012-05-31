- - -

**Smarty\Smarty_Internal_Resource_File**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_resource_file.php.md#line19" class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_file.php at line 19</a>

# Class Smarty_Internal_Resource_File #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>\n    *** Smarty_Internal_Resource_File **\n</pre>

- - -

<p class="signature">public  class **Smarty_Internal_Resource_File**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Resource File</p><p>Implements the file system as resource for Smarty templates</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#compileds">compileds</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#compiler_class">compiler_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#resources">resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#sources">sources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#sysplugins">sysplugins</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#template_lexer_class">template_lexer_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#template_parser_class">template_parser_class</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populate()">populate</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populateTimestamp()">populateTimestamp</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">populate Source Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getContent()">getContent</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Load template's source from file into current template object</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getBasename()">getBasename</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Determine basename for compiled filename</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildFilepath()">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildUniqueResourceName()">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#config()">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#fileExists()">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getBasename()">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getContent()">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getUniqueTemplateName()">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#parseResourceName()">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateCompiledFilepath()">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#source()">source</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_resource_file.php.md#line27" class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_file.php at line 27</a>

<h3 id="populate()">populate</h3>
```php
public  void **populate**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)```
<div class="details">
<p>populate Source Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_resource_file.php.md#line49" class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_file.php at line 49</a>

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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_resource_file.php.md#line62" class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_file.php at line 62</a>

<h3 id="getContent()">getContent</h3>
```php
public  string **getContent**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)```
<div class="details">
<p>Load template's source from file into current template object</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>template source</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if source cannot be loaded</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_resource_file.php.md#line79" class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_file.php at line 79</a>

<h3 id="getBasename()">getBasename</h3>
```php
public  string **getBasename**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)```
<div class="details">
<p>Determine basename for compiled filename</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>resource's basename</dd>
</dl>
</div>

- - -

