
- - -

**Smarty\Smarty_Internal_Resource_String**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_string.php#L21 class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_string.php at line 21</a>

#Class Smarty_Internal_Resource_String#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>
    * **Smarty_Internal_Resource_String**




- - -

<p class="signature">public  class **Smarty_Internal_Resource_String**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Resource String</p><p>Implements the strings as resource for Smarty template</p><p>unlike eval-resources the compiled state of string-resources is saved for subsequent access}</p></div>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcontent">getContent</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Load template's source from $resource_name into current template object</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#decode">decode</a>(string string)</p><p class="description">decode base64 and urlencode</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#builduniqueresourcename">buildUniqueResourceName</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, string resource_name)</p><p class="description">modify resource_name according to resource handlers specifications</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getbasename">getBasename</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Determine basename for compiled filenameAlways returns an empty string.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildFilepath()">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildUniqueResourceName()">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#config()">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#fileExists()">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getBasename()">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getContent()">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getUniqueTemplateName()">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#parseResourceName()">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateCompiledFilepath()">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#source()">source</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_string.php#L30 class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_string.php at line 30</a>

<h3 id="populate()">populate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populate</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Source Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_string.php#L44 class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_string.php at line 44</a>

<h3 id="getContent()">getContent</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getContent</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.html">Smarty_Template_Source</a> source)

<div class="details">
<p>Load template's source from $resource_name into current template object</p><dl>
<dt>Uses:</dt>
<dd>decode() to decode base64 and urlencoded template_resources</dd>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>template source</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if source cannot be loaded</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_string.php#L55 class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_string.php at line 55</a>

<h3 id="decode()">decode</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>decode</span> (string string)

<div class="details">
<p>decode base64 and urlencode</p><dl>
<dt>Parameters:</dt>
<dd>string - template_resource to decode</dd>
<dt>Returns:</dt>
<dd>decoded template_resource</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_string.php#L76 class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_string.php at line 76</a>

<h3 id="buildUniqueResourceName()">buildUniqueResourceName</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>buildUniqueResourceName</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, string resource_name)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_string.php#L89 class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_string.php at line 89</a>

<h3 id="getBasename()">getBasename</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>getBasename</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.html">Smarty_Template_Source</a> source)

<div class="details">
<p>Determine basename for compiled filename</p><p>Always returns an empty string.</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>resource's basename</dd>
</dl>
</div>

- - -

