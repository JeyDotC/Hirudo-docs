- - -

**Smarty\Smarty_Resource_Custom**
<div class="location">framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 18</div>
#Class Smarty_Resource_Custom#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>
    ***Smarty_Resource_Custom**


- - -

<p class="signature">public abstract  class **Smarty_Resource_Custom**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Resource Plugin</p><p>Wrapper Implementation for custom resource plugins</p></div>

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
<td class="type">protected abstract  void</td>
<td class="description"><p class="name"><a href="#fetch">fetch</a>(string name, string &$source, integer &$mtime, mixed source, mixed mtime)</p><p class="description">fetch template and its modification time from data source</p></td>
</tr>
<tr>
<td class="type">protected  integer|boolean</td>
<td class="description"><p class="name"><a href="#fetchTimestamp">fetchTimestamp</a>(string name)</p><p class="description">Fetch template's modification timestamp from data source{@internal implementing this method is optional.
</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getContent">getContent</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Load template's source into current template object</p></td>
</tr>
<tr>
<td class="type">protected  string</td>
<td class="description"><p class="name"><a href="#getBasename">getBasename</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Determine basename for compiled filename</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildFilepath()">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildUniqueResourceName()">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#config()">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#fileExists()">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getBasename()">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getContent()">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getUniqueTemplateName()">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#parseResourceName()">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateCompiledFilepath()">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#source()">source</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 27</div>
<h3 id="fetch()">fetch</h3>

```php
protected abstract  void **fetch**(string name, string &$source, integer &$mtime, mixed source, mixed mtime)
```
<div class="details">
<p>fetch template and its modification time from data source</p><dl>
<dt>Parameters:</dt>
<dd>name - template name</dd>
<dd>&$source - template source</dd>
<dd>&$mtime - template modification timestamp (epoch)</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 38</div>
<h3 id="fetchTimestamp()">fetchTimestamp</h3>

```php
protected  integer|boolean **fetchTimestamp**(string name)
```
<div class="details">
<p>Fetch template's modification timestamp from data source</p><p>implementing this method is optional.
Only implement it if modification times can be accessed faster than loading the complete template source.}</p><dl>
<dt>Parameters:</dt>
<dd>name - template name</dd>
<dt>Returns:</dt>
<dd>timestamp (epoch) the template was modified, or false if not found</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 49</div>
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

<div class="location">framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 73</div>
<h3 id="getContent()">getContent</h3>

```php
public  string **getContent**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)
```
<div class="details">
<p>Load template's source into current template object</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>template source</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if source cannot be loaded</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 89</div>
<h3 id="getBasename()">getBasename</h3>

```php
protected  string **getBasename**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)
```
<div class="details">
<p>Determine basename for compiled filename</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>resource's basename</dd>
</dl>
</div>

- - -

