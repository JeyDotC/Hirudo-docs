- - -

**Smarty\Smarty_Resource_Uncompiled**
<div class="location">framework\libs\smarty\sysplugins\smarty_resource_uncompiled.php at line 18</div>
#Class Smarty_Resource_Uncompiled#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>
    ***Smarty_Resource_Uncompiled**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_resource_php.html">Smarty_Internal_Resource_PHP</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Smarty_Resource_Uncompiled**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Resource Plugin</p><p>Base implementation for resource plugins that don't use the compiler</p></div>

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
<td class="type">abstract  void</td>
<td class="description"><p class="name"><a href="#renderUncompiled">renderUncompiled</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">Render and output the template (without using the compiler)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populateCompiledFilepath">populateCompiledFilepath</a>(<a href="../smarty/smarty_template_compiled.html">Smarty_Template_Compiled</a> compiled, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate compiled object with compiled filepath</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildFilepath()">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildUniqueResourceName()">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#config()">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#fileExists()">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getBasename()">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getContent()">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getUniqueTemplateName()">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#parseResourceName()">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateCompiledFilepath()">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#source()">source</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_resource_uncompiled.php at line 27</div>
<h3 id="renderUncompiled()">renderUncompiled</h3>

```php
public abstract  void **renderUncompiled**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)
```
<div class="details">
<p>Render and output the template (without using the compiler)</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - on failure</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource_uncompiled.php at line 35</div>
<h3 id="populateCompiledFilepath()">populateCompiledFilepath</h3>

```php
public  void **populateCompiledFilepath**(<a href="../smarty/smarty_template_compiled.html">Smarty_Template_Compiled</a> compiled, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)
```
<div class="details">
<p>populate compiled object with compiled filepath</p><dl>
<dt>Parameters:</dt>
<dd>compiled - compiled object</dd>
<dd>_template - template object (is ignored)</dd>
</dl>
</div>

- - -

