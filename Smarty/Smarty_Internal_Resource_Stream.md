

- - -

**Smarty\Smarty_Internal_Resource_Stream**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_stream.php#L22" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_stream.php at line 22</a>

#Class Smarty_Internal_Resource_Stream#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md">Smarty_Resource</a>
 &gt; <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource_Recompiled.md">Smarty_Resource_Recompiled</a>
 &gt; **Smarty_Internal_Resource_Stream**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Resource_Stream</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource_Recompiled.md">Smarty_Resource_Recompiled</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Resource Stream</p><p>Implements the streams as resource for Smarty template</p></div>

<dl>
<dt>See Also:</dt>
<dd><code><a href="http://php.net/streams">http://php.net/streams</a></code></dd>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcontent">getContent</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">Load template's source from stream into current template object</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#builduniqueresourcename">buildUniqueResourceName</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty, string resource_name)</p><p class="description">modify resource_name according to resource handlers specifications</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource_Recompiled</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource_Recompiled.md#populatecompiledfilepath">populateCompiledFilepath</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#buildfilepath">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#builduniqueresourcename">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#config">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#fileexists">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getbasename">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getcontent">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getuniquetemplatename">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#load">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#parseresourcename">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populate">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populatecompiledfilepath">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populatetimestamp">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#source">source</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_stream.php#L31" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_stream.php at line 31</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_stream.php#L47" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_stream.php at line 47</a>

<h3 id="getContent()">getContent</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getContent</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>Load template's source from stream into current template object</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>template source</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if source cannot be loaded</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_stream.php#L70" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_stream.php at line 70</a>

<h3 id="buildUniqueResourceName()">buildUniqueResourceName</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>buildUniqueResourceName</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty, string resource_name)

<div class="details">
<p>modify resource_name according to resource handlers specifications</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty instance</dd>
<dd>resource_name - resource_name to make unique</dd>
<dt>Returns:</dt>
<dd>unique resource name</dd>
</dl>

</div>

- - -

