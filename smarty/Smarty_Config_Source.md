

- - -

**Smarty\Smarty_Config_Source**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_config_source.php#L22" >framework\libs\smarty\sysplugins\smarty_config_source.php at line 22</a>

#Class Smarty_Config_Source#

<a href="">Smarty_Template_Source</a>
    * **Smarty_Config_Source**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Smarty_Config_Source</span>
extends <a href="">Smarty_Template_Source</a>

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
<tr><td><a href="">compiler_class</a>, <a href="">components</a>, <a href="">filepath</a>, <a href="">handler</a>, <a href="">name</a>, <a href="">recompiled</a>, <a href="">resource</a>, <a href="">smarty</a>, <a href="">template_lexer_class</a>, <a href="">template_parser_class</a>, <a href="">type</a>, <a href="">uid</a>, <a href="">uncompiled</a>, <a href="">unique_resource</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Resource.md">Smarty_Resource</a> handler, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource, string type, string name, string unique_resource)</p><p class="description">create Config Object container</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Template_Source</th></tr>
<tr><td><a href="">__construct</a>, <a href="">getCompiled</a>, <a href="">renderUncompiled</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_config_source.php#L34" >framework\libs\smarty\sysplugins\smarty_config_source.php at line 34</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Resource.md">Smarty_Resource</a> handler, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource, string type, string name, string unique_resource)

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

