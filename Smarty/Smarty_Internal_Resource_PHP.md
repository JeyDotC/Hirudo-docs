

- - -

**Smarty\Smarty_Internal_Resource_PHP**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_php.php#L13" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 13</a>

#Class Smarty_Internal_Resource_PHP#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md">Smarty_Resource</a>
 &gt; <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource_Uncompiled.md">Smarty_Resource_Uncompiled</a>
 &gt; **Smarty_Internal_Resource_PHP**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Resource_PHP</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource_Uncompiled.md">Smarty_Resource_Uncompiled</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Resource PHP</p><p>Implements the file system as resource for PHP templates</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dd>Rodney Rehm</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Resource_PHP.md#short_open_tag"> $short_open_tag</a>
                                </p><p class="description">container for short_open_tag directive's value before executing PHP templates</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Create a new PHP Resource</p></td>
</tr>
</table>

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
<td class="description"><p class="name"><a href="#getcontent">getContent</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">Load template's source from file into current template object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#renderuncompiled">renderUncompiled</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">Render and output the template (without using the compiler)</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource_Uncompiled</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource_Uncompiled.md#populatecompiledfilepath">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource_Uncompiled.md#renderuncompiled">renderUncompiled</a></td></tr></table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Resource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#buildfilepath">buildFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#builduniqueresourcename">buildUniqueResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#config">config</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#fileexists">fileExists</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getbasename">getBasename</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getcontent">getContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#getuniquetemplatename">getUniqueTemplateName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#load">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#parseresourcename">parseResourceName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populate">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populatecompiledfilepath">populateCompiledFilepath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#populatetimestamp">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Resource.md#source">source</a></td></tr></table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_php.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 18</a>

<h3 id="short_open_tag">short_open_tag</h3>
<span class='k'>protected </span> <span class='nx'>string</span><span class='no'> $short_open_tag</span><span class='o'> = null</span>

<div class="details">
<p>container for short_open_tag directive's value before executing PHP templates</p>
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_php.php#L24" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 24</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Create a new PHP Resource</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_php.php#L36" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 36</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_php.php#L59" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 59</a>

<h3 id="populateTimestamp()">populateTimestamp</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populateTimestamp</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>populate Source Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_php.php#L72" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 72</a>

<h3 id="getContent()">getContent</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getContent</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>Load template's source from file into current template object</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>template source</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if source cannot be loaded</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_resource_php.php#L88" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_resource_php.php at line 88</a>

<h3 id="renderUncompiled()">renderUncompiled</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>renderUncompiled</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>Render and output the template (without using the compiler)</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if template cannot be loaded or allow_php_templates is disabled</dd>
</dl>

</div>

- - -

