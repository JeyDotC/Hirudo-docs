

- - -

**Smarty\Smarty_Template_Compiled**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L765" >framework\libs\smarty\sysplugins\smarty_resource.php at line 765</a>

#Class Smarty_Template_Compiled#

**Smarty_Template_Compiled**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Smarty_Template_Compiled</span></p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Meta Data Container for Template Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Property:</dt>
<dd>string $content compiled content</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_properties"> $_properties</a>
                                </p><p class="description">Metadata propertiespopulated by Smarty_Internal_Template::decodeProperties()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#exists"> $exists</a>
                                </p><p class="description">Compiled Existance</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#filepath"> $filepath</a>
                                </p><p class="description">Compiled Filepath</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#isCompiled"> $isCompiled</a>
                                </p><p class="description">Template was compiled</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#loaded"> $loaded</a>
                                </p><p class="description">Compiled Content Loaded</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.html'>Smarty_Template_Source</a></span></td>
<td class="description"><p class="name" ><a href="#source"> $source</a>
                                </p><p class="description">Source Object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name" ><a href="#timestamp"> $timestamp</a>
                                </p><p class="description">Compiled Timestamp</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.md">Smarty_Template_Source</a> source)</p><p class="description">create Compiled Object container</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L816" >framework\libs\smarty\sysplugins\smarty_resource.php at line 816</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>create Compiled Object container</p><dl>
<dt>Parameters:</dt>
<dd>source - source object this compiled object belongs to</dd>
</dl>

</div>

- - -

