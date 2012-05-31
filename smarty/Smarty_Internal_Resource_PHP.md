- - -

**Smarty\Smarty_Internal_Resource_PHP**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 13</div>
#Class Smarty_Internal_Resource_PHP#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>
    *<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_uncompiled.html">Smarty_Resource_Uncompiled</a>
        ***Smarty_Internal_Resource_PHP**


- - -

<p class="signature">public  class **Smarty_Internal_Resource_PHP**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_uncompiled.html">Smarty_Resource_Uncompiled</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Resource PHP</p><p>Implements the file system as resource for PHP templates</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dd>Rodney Rehm</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  string</td>
<td class="description"><p class="name"><a href="#short_open_tag">$short_open_tag</a></p><p class="description">container for short_open_tag directive's value before executing PHP templates</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Create a new PHP Resource</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populateTimestamp">populateTimestamp</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">populate Source Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getContent">getContent</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Load template's source from file into current template object</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#renderUncompiled">renderUncompiled</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">Render and output the template (without using the compiler)</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource_Uncompiled</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_uncompiled.html#populateCompiledFilepath()">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_uncompiled.html#renderUncompiled()">renderUncompiled</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildFilepath()">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildUniqueResourceName()">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#config()">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#fileExists()">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getBasename()">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getContent()">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getUniqueTemplateName()">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#parseResourceName()">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateCompiledFilepath()">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#source()">source</a></td></tr></table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 18</div>
<h3 id="short_open_tag">short_open_tag</h3>

```php
protected  string$short_open_tag = null
```
<div class="details">
<p>container for short_open_tag directive's value before executing PHP templates</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 24</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**()
```
<div class="details">
<p>Create a new PHP Resource</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 36</div>
<h3 id="populate()">populate</h3>

```php
public  void **populate**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)
```
<div class="details">
<p>populate Source Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 59</div>
<h3 id="populateTimestamp()">populateTimestamp</h3>

```php
public  void **populateTimestamp**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)
```
<div class="details">
<p>populate Source Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 72</div>
<h3 id="getContent()">getContent</h3>

```php
public  string **getContent**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)
```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 88</div>
<h3 id="renderUncompiled()">renderUncompiled</h3>

```php
public  void **renderUncompiled**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)
```
<div class="details">
<p>Render and output the template (without using the compiler)</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if template cannot be loaded or allow_php_templates is disabled</dd>
</dl>
</div>

- - -

