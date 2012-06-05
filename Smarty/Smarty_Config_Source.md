

- - -

**Smarty\Smarty_Config_Source**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_config_source.php#L22" target='_blank'>framework\libs\smarty\sysplugins\smarty_config_source.php at line 22</a>

#Class Smarty_Config_Source#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a>
 &gt; **Smarty_Config_Source**




- - -

<p><strong>public  class</strong> <span>Smarty_Config_Source</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a>

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


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Template_Source</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#compiler_class">compiler_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#components">components</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#filepath">filepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#handler">handler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#name">name</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#recompiled">recompiled</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#resource">resource</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#smarty">smarty</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#template_lexer_class">template_lexer_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#template_parser_class">template_parser_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#type">type</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#uid">uid</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#uncompiled">uncompiled</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#unique_resource">unique_resource</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md">Smarty_Resource</a> handler, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty, string resource, string type, string name, string unique_resource)</p><p class="description">create Config Object container</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Template_Source</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#getcompiled">getCompiled</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md#renderuncompiled">renderUncompiled</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_config_source.php#L34" target='_blank'>framework\libs\smarty\sysplugins\smarty_config_source.php at line 34</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md">Smarty_Resource</a> handler, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty, string resource, string type, string name, string unique_resource)

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

