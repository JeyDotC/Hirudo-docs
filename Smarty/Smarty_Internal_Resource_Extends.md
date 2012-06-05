

- - -

**Smarty\Smarty_Internal_Resource_Extends**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_extends.php#L19" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_extends.php at line 19</a>

#Class Smarty_Internal_Resource_Extends#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md">Smarty_Resource</a>
 &gt; **Smarty_Internal_Resource_Extends**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Resource_Extends</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md">Smarty_Resource</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Resource Extends</p><p>Implements the file system as resource for Smarty which {extend}s a chain of template files templates</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="mbstring_overload"> $mbstring_overload</a>
                                </p><p class="description">mbstring.overload flag</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#compileds">compileds</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#compiler_class">compiler_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#resources">resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#sources">sources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#sysplugins">sysplugins</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#template_lexer_class">template_lexer_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#template_parser_class">template_parser_class</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populatetimestamp">populateTimestamp</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">populate Source Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcontent">getContent</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">Load template's source from files into current template object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getbasename">getBasename</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">Determine basename for compiled filename</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#buildfilepath">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#builduniqueresourcename">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#config">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#fileexists">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getbasename">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getcontent">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getuniquetemplatename">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#load">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#parseresourcename">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populate">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populatecompiledfilepath">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populatetimestamp">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#source">source</a></td></tr></table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_extends.php#L26" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_extends.php at line 26</a>

<h3 id="mbstring_overload">mbstring_overload</h3>
<span class='k'></span> <span class='nx'>int</span><span class='no'> $mbstring_overload</span><span class='o'> = 0</span>

<div class="details">
<p>mbstring.overload flag</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_extends.php#L34" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_extends.php at line 34</a>

<h3 id="populate()">populate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populate</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Source Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_extends.php#L67" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_extends.php at line 67</a>

<h3 id="populateTimestamp()">populateTimestamp</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populateTimestamp</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>populate Source Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_extends.php#L83" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_extends.php at line 83</a>

<h3 id="getContent()">getContent</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getContent</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>Load template's source from files into current template object</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>template source</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if source cannot be loaded</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_extends.php#L150" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_extends.php at line 150</a>

<h3 id="getBasename()">getBasename</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getBasename</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>Determine basename for compiled filename</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>resource's basename</dd>
</dl>

</div>

- - -

