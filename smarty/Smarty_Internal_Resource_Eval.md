
- - -

**Smarty\Smarty_Internal_Resource_Eval**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_eval.php at line 21</div>
#Class Smarty_Internal_Resource_Eval#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html">Smarty_Resource</a>
    *<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_recompiled.html">Smarty_Resource_Recompiled</a>
        ***Smarty_Internal_Resource_Eval**


- - -

<p class="signature">public  class **Smarty_Internal_Resource_Eval**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_recompiled.html">Smarty_Resource_Recompiled</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Resource Eval</p><p>Implements the strings as resource for Smarty template</p><p>unlike string-resources the compiled state of eval-resources is NOT saved for subsequent access}</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#getcontent">getContent</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Load template's source from $resource_name into current template object</p></td>
</tr>
<tr>
<td class="type"> protected  string</td>
<td class="description"><p class="name"><a href="#decode">decode</a>(string string)</p><p class="description">decode base64 and urlencode</p></td>
</tr>
<tr>
<td class="type"> protected  string</td>
<td class="description"><p class="name"><a href="#builduniqueresourcename">buildUniqueResourceName</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name)</p><p class="description">modify resource_name according to resource handlers specifications</p></td>
</tr>
<tr>
<td class="type"> protected  string</td>
<td class="description"><p class="name"><a href="#getbasename">getBasename</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">Determine basename for compiled filename</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource_Recompiled</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource_recompiled.html#populateCompiledFilepath()">populateCompiledFilepath</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildFilepath()">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#buildUniqueResourceName()">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#config()">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#fileExists()">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getBasename()">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getContent()">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#getUniqueTemplateName()">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#parseResourceName()">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateCompiledFilepath()">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_resource.html#source()">source</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_eval.php at line 30</div>
<h3 id="populate()">populate</h3>

public  void **populate** (<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)<div class="details">
<p>populate Source Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_eval.php at line 44</div>
<h3 id="getContent()">getContent</h3>

public  string **getContent** (<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)<div class="details">
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_eval.php at line 55</div>
<h3 id="decode()">decode</h3>

protected  string **decode** (string string)<div class="details">
<p>decode base64 and urlencode</p><dl>
<dt>Parameters:</dt>
<dd>string - template_resource to decode</dd>
<dt>Returns:</dt>
<dd>decoded template_resource</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_eval.php at line 76</div>
<h3 id="buildUniqueResourceName()">buildUniqueResourceName</h3>

protected  string **buildUniqueResourceName** (<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name)<div class="details">
<p>modify resource_name according to resource handlers specifications</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty instance</dd>
<dd>resource_name - resource_name to make unique</dd>
<dt>Returns:</dt>
<dd>unique resource name</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_resource_eval.php at line 87</div>
<h3 id="getBasename()">getBasename</h3>

protected  string **getBasename** (<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)<div class="details">
<p>Determine basename for compiled filename</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>resource's basename</dd>
</dl>
</div>

- - -

