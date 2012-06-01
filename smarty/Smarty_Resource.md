

- - -

**Smarty\Smarty_Resource**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L18" >framework\libs\smarty\sysplugins\smarty_resource.php at line 18</a>

#Class Smarty_Resource#

**Smarty_Resource**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="">Smarty_Internal_Resource_Extends</a> <a href="">Smarty_Internal_Resource_File</a> <a href="">Smarty_Internal_Resource_Registered</a> <a href="">Smarty_Internal_Resource_String</a> <a href="">Smarty_Resource_Custom</a> <a href="">Smarty_Resource_Recompiled</a> <a href="">Smarty_Resource_Uncompiled</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>Smarty_Resource</span></p>

<div class="comment" id="overview_description"><p>Smarty Resource Plugin</p><p>Base implementation for resource plugins</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#compileds"> $compileds</a>
                                </p><p class="description">cache for Smarty_Template_Compiled instances</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#compiler_class"> $compiler_class</a>
                                </p><p class="description">Name of the Class to compile this resource's contents with</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#resources"> $resources</a>
                                </p><p class="description">cache for Smarty_Resource instances</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#sources"> $sources</a>
                                </p><p class="description">cache for Smarty_Template_Source instances</p></td>
</tr>
<tr>
<td><span class='k'>protected static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#sysplugins"> $sysplugins</a>
                                </p><p class="description">resource types provided by the core</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#template_lexer_class"> $template_lexer_class</a>
                                </p><p class="description">Name of the Class to tokenize this resource's contents with</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#template_parser_class"> $template_parser_class</a>
                                </p><p class="description">Name of the Class to parse this resource's contents with</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcontent">getContent</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">Load template's source into current template objectThe loaded source is assigned to $_template->source->content directly.}</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">populate Source Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populatetimestamp">populateTimestamp</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">populate Source Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#builduniqueresourcename">buildUniqueResourceName</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource_name)</p><p class="description">modify resource_name according to resource handlers specifications</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populatecompiledfilepath">populateCompiledFilepath</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Compiled.md">Smarty_Template_Compiled</a> compiled, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">populate Compiled Object with compiled filepath</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#buildfilepath">buildFilepath</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">build template filepath by traversing the template_dir array</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#fileexists">fileExists</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, string file)</p><p class="description">test is file exists and save timestamp</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getbasename">getBasename</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">Determine basename for compiled filename</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Resource>Smarty_Resource</a></span></td>
<td class="description"><p class="name"><a href="#load">load</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string type)</p><p class="description">Load Resource Handler</p></td>
</tr>
<tr>
<td><span class='k'>protected static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#parseresourcename">parseResourceName</a>(string resource_name, string default_resource, string &$name, string &$type, mixed name, mixed type)</p><p class="description">extract resource_type and resource_name from template_resource and config_resource</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getuniquetemplatename">getUniqueTemplateName</a>(string smarty, string template_resource)</p><p class="description">modify template_resource according to resource handlers specifications</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Template_Source>Smarty_Template_Source</a></span></td>
<td class="description"><p class="name"><a href="#source">source</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string template_resource)</p><p class="description">initialize Source Object for given resourceEither [$_template] or [$smarty, $template_resource] must be specified</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Config_Source>Smarty_Config_Source</a></span></td>
<td class="description"><p class="name"><a href="#config">config</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Config.md">Smarty_Internal_Config</a> _config)</p><p class="description">initialize Config Source Object for given resource</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L67" >framework\libs\smarty\sysplugins\smarty_resource.php at line 67</a>

<h3 id="getContent()">getContent</h3>
<span class='k'>abstract </span> <span class='nx'>string</span> <span class='nf'>getContent</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>Load template's source into current template object</p><p>The loaded source is assigned to $_template->source->content directly.}</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dt>Returns:</dt>
<dd>template source</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if source cannot be loaded</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L75" >framework\libs\smarty\sysplugins\smarty_resource.php at line 75</a>

<h3 id="populate()">populate</h3>
<span class='k'>abstract </span> <span class='nx'>void</span> <span class='nf'>populate</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Source Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L82" >framework\libs\smarty\sysplugins\smarty_resource.php at line 82</a>

<h3 id="populateTimestamp()">populateTimestamp</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populateTimestamp</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>populate Source Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L95" >framework\libs\smarty\sysplugins\smarty_resource.php at line 95</a>

<h3 id="buildUniqueResourceName()">buildUniqueResourceName</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>buildUniqueResourceName</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource_name)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L106" >framework\libs\smarty\sysplugins\smarty_resource.php at line 106</a>

<h3 id="populateCompiledFilepath()">populateCompiledFilepath</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populateCompiledFilepath</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Compiled.md">Smarty_Template_Compiled</a> compiled, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Compiled Object with compiled filepath</p><dl>
<dt>Parameters:</dt>
<dd>compiled - compiled object</dd>
<dd>_template - template object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L149" >framework\libs\smarty\sysplugins\smarty_resource.php at line 149</a>

<h3 id="buildFilepath()">buildFilepath</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>buildFilepath</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>build template filepath by traversing the template_dir array</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>_template - template object</dd>
<dt>Returns:</dt>
<dd>fully qualified filepath</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if default template handler is registered but not callable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L316" >framework\libs\smarty\sysplugins\smarty_resource.php at line 316</a>

<h3 id="fileExists()">fileExists</h3>
<span class='k'>protected </span> <span class='nx'>bool</span> <span class='nf'>fileExists</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source, string file)

<div class="details">
<p>test is file exists and save timestamp</p><dl>
<dt>Parameters:</dt>
<dd>source - source object</dd>
<dd>file - file name</dd>
<dt>Returns:</dt>
<dd>true if file exists</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L329" >framework\libs\smarty\sysplugins\smarty_resource.php at line 329</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L341" >framework\libs\smarty\sysplugins\smarty_resource.php at line 341</a>

<h3 id="load()">load</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Resource>Smarty_Resource</a></span> <span class='nf'>load</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string type)

<div class="details">
<p>Load Resource Handler</p><dl>
<dt>Parameters:</dt>
<dd>smarty - smarty object</dd>
<dd>type - name of the resource</dd>
<dt>Returns:</dt>
<dd>Resource Handler</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L427" >framework\libs\smarty\sysplugins\smarty_resource.php at line 427</a>

<h3 id="parseResourceName()">parseResourceName</h3>
<span class='k'>protected static </span> <span class='nx'>void</span> <span class='nf'>parseResourceName</span> (string resource_name, string default_resource, string &$name, string &$type, mixed name, mixed type)

<div class="details">
<p>extract resource_type and resource_name from template_resource and config_resource</p><dl>
<dt>Note:</dt>
<dd>"C:/foo.tpl" was forced to file resource up till Smarty 3.1.3 (including).</dd>
<dt>Parameters:</dt>
<dd>resource_name - template_resource or config_resource to parse</dd>
<dd>default_resource - the default resource_type defined in $smarty</dd>
<dd>&$name - the parsed resource name</dd>
<dd>&$type - the parsed resource type</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L457" >framework\libs\smarty\sysplugins\smarty_resource.php at line 457</a>

<h3 id="getUniqueTemplateName()">getUniqueTemplateName</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>getUniqueTemplateName</span> (string smarty, string template_resource)

<div class="details">
<p>modify template_resource according to resource handlers specifications</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty instance</dd>
<dd>template_resource - template_resource to extracate resource handler and name of</dd>
<dt>Returns:</dt>
<dd>unique resource name</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L475" >framework\libs\smarty\sysplugins\smarty_resource.php at line 475</a>

<h3 id="source()">source</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Template_Source>Smarty_Template_Source</a></span> <span class='nf'>source</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string template_resource)

<div class="details">
<p>initialize Source Object for given resource</p><p>Either [$_template] or [$smarty, $template_resource] must be specified</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>smarty - smarty object</dd>
<dd>template_resource - resource identifier</dd>
<dt>Returns:</dt>
<dd>Source Object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L508" >framework\libs\smarty\sysplugins\smarty_resource.php at line 508</a>

<h3 id="config()">config</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Config_Source>Smarty_Config_Source</a></span> <span class='nf'>config</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Config.md">Smarty_Internal_Config</a> _config)

<div class="details">
<p>initialize Config Source Object for given resource</p><dl>
<dt>Parameters:</dt>
<dd>_config - config object</dd>
<dt>Returns:</dt>
<dd>Source Object</dd>
</dl>

</div>

- - -

