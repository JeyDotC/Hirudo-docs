

- - -

**Smarty\Smarty_Resource_Custom**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_custom.php#L18" >framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 18</a>

#Class Smarty_Resource_Custom#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">Smarty_Resource</a>
    * **Smarty_Resource_Custom**




- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>Smarty_Resource_Custom</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">Smarty_Resource</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Resource Plugin</p><p>Wrapper Implementation for custom resource plugins</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">compileds</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">compiler_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">sources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">sysplugins</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">template_lexer_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">template_parser_class</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#fetch">fetch</a>(string name, string &$source, integer &$mtime, mixed source, mixed mtime)</p><p class="description">fetch template and its modification time from data source</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>integer|boolean</span></td>
<td class="description"><p class="name"><a href="#fetchtimestamp">fetchTimestamp</a>(string name)</p><p class="description">Fetch template's modification timestamp from data source{@internal implementing this method is optional.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcontent">getContent</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">Load template's source into current template object</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getbasename">getBasename</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">Determine basename for compiled filename</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.md">source</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_custom.php#L27" >framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 27</a>

<h3 id="fetch()">fetch</h3>
<span class='k'>protected abstract </span> <span class='nx'>void</span> <span class='nf'>fetch</span> (string name, string &$source, integer &$mtime, mixed source, mixed mtime)

<div class="details">
<p>fetch template and its modification time from data source</p><dl>
<dt>Parameters:</dt>
<dd>name - template name</dd>
<dd>&$source - template source</dd>
<dd>&$mtime - template modification timestamp (epoch)</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_custom.php#L38" >framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 38</a>

<h3 id="fetchTimestamp()">fetchTimestamp</h3>
<span class='k'>protected </span> <span class='nx'>integer|boolean</span> <span class='nf'>fetchTimestamp</span> (string name)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_custom.php#L49" >framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 49</a>

<h3 id="populate()">populate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populate</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Source Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_custom.php#L73" >framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 73</a>

<h3 id="getContent()">getContent</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getContent</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource_custom.php#L89" >framework\libs\smarty\sysplugins\smarty_resource_custom.php at line 89</a>

<h3 id="getBasename()">getBasename</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>getBasename</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>Determine basename for compiled filename</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>resource's basename</dd>
</dl>

</div>

- - -

