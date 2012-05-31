- - -

**Smarty\Smarty_Config_Source**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_config_source.php.md#line22" class="location">framework\libs\smarty\sysplugins\smarty_config_source.php at line 22</a>

# Class Smarty_Config_Source #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html">Smarty_Template_Source</a>\n    *** Smarty_Config_Source **\n</pre>

- - -

<p class="signature">public  class **Smarty_Config_Source**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html">Smarty_Template_Source</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Meta Data Container for Config Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Property:</dt>
<dd>string $content</dd>
<dd>int $timestamp</dd>
<dd>bool $exists</dd>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Template_Source</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#compiler_class">compiler_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#components">components</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#filepath">filepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#handler">handler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#name">name</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#recompiled">recompiled</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#resource">resource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#smarty">smarty</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#template_lexer_class">template_lexer_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#template_parser_class">template_parser_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#type">type</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#uid">uid</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#uncompiled">uncompiled</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#unique_resource">unique_resource</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(<a href="../smarty/smarty_resource.html">Smarty_Resource</a> handler, <a href="../smarty/smarty.html">Smarty</a> smarty, string resource, string type, string name, string unique_resource)</p><p class="description">create Config Object container</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Template_Source</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#getCompiled()">getCompiled</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_template_source.html#renderUncompiled()">renderUncompiled</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_config_source.php.md#line34" class="location">framework\libs\smarty\sysplugins\smarty_config_source.php at line 34</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(<a href="../smarty/smarty_resource.html">Smarty_Resource</a> handler, <a href="../smarty/smarty.html">Smarty</a> smarty, string resource, string type, string name, string unique_resource)```
<div class="details">
<p>create Config Object container</p><dl>
<dt>Parameters:</dt>
<dd>handler - Resource Handler this source object communicates with</dd>
<dd>smarty - Smarty instance this source object belongs to</dd>
<dd>resource - full config_resource</dd>
<dd>type - type of resource</dd>
<dd>name - resource name</dd>
<dd>unique_resource - unqiue resource name</dd>
</dl>
</div>

- - -

