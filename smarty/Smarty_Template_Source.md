

- - -

**Smarty\Smarty_Template_Source**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L557" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 557</a>

#Class Smarty_Template_Source#

**Smarty_Template_Source**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Config_Source.md">Smarty_Config_Source</a> </dd>
</dl>



- - -

<p><strong>public static  class</strong> <span>Smarty_Template_Source</span></p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Meta Data Container for Template Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Property:</dt>
<dd>integer $timestamp Source Timestamp</dd>
<dd>boolean $exists Source Existance</dd>
<dd>boolean $template Extended Template reference</dd>
<dd>string $content Source Content</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#compiler_class"> $compiler_class</a>
                                </p><p class="description">Name of the Class to compile this resource's contents with</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#components"> $components</a>
                                </p><p class="description">The Components an extended template is made of</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#filepath"> $filepath</a>
                                </p><p class="description">Source Filepath</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Resource'>Smarty_Resource</a></span></td>
<td class="description"><p class="name" ><a href="#handler"> $handler</a>
                                </p><p class="description">Resource Handler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#name"> $name</a>
                                </p><p class="description">Resource Name</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#recompiled"> $recompiled</a>
                                </p><p class="description">Source must be recompiled on every occasion</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#resource"> $resource</a>
                                </p><p class="description">Template Resource (Smarty_Internal_Template::$template_resource)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty'>Smarty</a></span></td>
<td class="description"><p class="name" ><a href="#smarty"> $smarty</a>
                                </p><p class="description">Smarty instance</p></td>
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
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#type"> $type</a>
                                </p><p class="description">Resource Type</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#uid"> $uid</a>
                                </p><p class="description">Unique Template ID</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#uncompiled"> $uncompiled</a>
                                </p><p class="description">Source is bypassing compiler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#unique_resource"> $unique_resource</a>
                                </p><p class="description">Unique Resource Name</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Resource.md">Smarty_Resource</a> handler, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource, string type, string name, string unique_resource)</p><p class="description">create Source Object container</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Template_Compiled>Smarty_Template_Compiled</a></span></td>
<td class="description"><p class="name"><a href="#getcompiled">getCompiled</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">get a Compiled Object of this source</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#renderuncompiled">renderUncompiled</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">render the uncompiled source</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L653" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 653</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Resource.md">Smarty_Resource</a> handler, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource, string type, string name, string unique_resource)

<div class="details">
<p>create Source Object container</p><dl>
<dt>Parameters:</dt>
<dd>handler - Resource Handler this source object communicates with</dd>
<dd>smarty - Smarty instance this source object belongs to</dd>
<dd>resource - full template_resource</dd>
<dd>type - type of resource</dd>
<dd>name - resource name</dd>
<dd>unique_resource - unqiue resource name</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L676" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 676</a>

<h3 id="getCompiled()">getCompiled</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Template_Compiled>Smarty_Template_Compiled</a></span> <span class='nf'>getCompiled</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>get a Compiled Object of this source</p><dl>
<dt>Parameters:</dt>
<dd>_template - template objet</dd>
<dt>Returns:</dt>
<dd>compiled object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L700" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 700</a>

<h3 id="renderUncompiled()">renderUncompiled</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>renderUncompiled</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>render the uncompiled source</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
</dl>

</div>

- - -

