

- - -

**Smarty\Smarty_Resource_Uncompiled**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_uncompiled.php#L18" >framework\libs\smarty\sysplugins\smarty_resource_uncompiled.php at line 18</a>

#Class Smarty_Resource_Uncompiled#

<a href="">Smarty_Resource</a>
    * **Smarty_Resource_Uncompiled**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="">Smarty_Internal_Resource_PHP</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>Smarty_Resource_Uncompiled</span>
extends <a href="">Smarty_Resource</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Resource Plugin</p><p>Base implementation for resource plugins that don't use the compiler</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="">compileds</a>, <a href="">compiler_class</a>, <a href="">resources</a>, <a href="">sources</a>, <a href="">sysplugins</a>, <a href="">template_lexer_class</a>, <a href="">template_parser_class</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#renderuncompiled">renderUncompiled</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">Render and output the template (without using the compiler)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populatecompiledfilepath">populateCompiledFilepath</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Compiled.md">Smarty_Template_Compiled</a> compiled, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">populate compiled object with compiled filepath</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="">buildFilepath</a>, <a href="">buildUniqueResourceName</a>, <a href="">config</a>, <a href="">fileExists</a>, <a href="">getBasename</a>, <a href="">getContent</a>, <a href="">getUniqueTemplateName</a>, <a href="">load</a>, <a href="">parseResourceName</a>, <a href="">populate</a>, <a href="">populateCompiledFilepath</a>, <a href="">populateTimestamp</a>, <a href="">source</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_uncompiled.php#L27" >framework\libs\smarty\sysplugins\smarty_resource_uncompiled.php at line 27</a>

<h3 id="renderUncompiled()">renderUncompiled</h3>
<span class='k'>abstract </span> <span class='nx'>void</span> <span class='nf'>renderUncompiled</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_uncompiled.php#L35" >framework\libs\smarty\sysplugins\smarty_resource_uncompiled.php at line 35</a>

<h3 id="populateCompiledFilepath()">populateCompiledFilepath</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populateCompiledFilepath</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Compiled.md">Smarty_Template_Compiled</a> compiled, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate compiled object with compiled filepath</p><dl>
<dt>Parameters:</dt>
<dd>compiled - compiled object</dd>
<dd>_template - template object (is ignored)</dd>
</dl>

</div>

- - -

