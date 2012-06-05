

- - -

**Smarty\Smarty_Template_Compiled**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L765" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 765</a>

#Class Smarty_Template_Compiled#

**Smarty_Template_Compiled**




- - -

<p><strong>public  class</strong> <span>Smarty_Template_Compiled</span></p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Meta Data Container for Template Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Property:</dt>
<dd>string $content compiled content</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="_properties"> $_properties</a>
                                </p><p class="description">Metadata propertiespopulated by Smarty_Internal_Template::decodeProperties()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="exists"> $exists</a>
                                </p><p class="description">Compiled Existance</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="filepath"> $filepath</a>
                                </p><p class="description">Compiled Filepath</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="iscompiled"> $isCompiled</a>
                                </p><p class="description">Template was compiled</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="loaded"> $loaded</a>
                                </p><p class="description">Compiled Content Loaded</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Compiled.md#source'>Smarty_Template_Source</a></span></td>
<td class="description"><p class="name" ><a href="source"> $source</a>
                                </p><p class="description">Source Object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name" ><a href="timestamp"> $timestamp</a>
                                </p><p class="description">Compiled Timestamp</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)</p><p class="description">create Compiled Object container</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L809" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 809</a>

<h3 id="_properties">_properties</h3>
<span class='k'></span> <span class='nx'>array</span><span class='no'> $_properties</span><span class='o'> = null</span>

<div class="details">
<p>Metadata properties</p><p>populated by Smarty_Internal_Template::decodeProperties()</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L783" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 783</a>

<h3 id="exists">exists</h3>
<span class='k'></span> <span class='nx'>boolean</span><span class='no'> $exists</span><span class='o'> = false</span>

<div class="details">
<p>Compiled Existance</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L771" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 771</a>

<h3 id="filepath">filepath</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $filepath</span><span class='o'> = null</span>

<div class="details">
<p>Compiled Filepath</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L795" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 795</a>

<h3 id="isCompiled">isCompiled</h3>
<span class='k'></span> <span class='nx'>boolean</span><span class='no'> $isCompiled</span><span class='o'> = false</span>

<div class="details">
<p>Template was compiled</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L789" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 789</a>

<h3 id="loaded">loaded</h3>
<span class='k'></span> <span class='nx'>boolean</span><span class='no'> $loaded</span><span class='o'> = false</span>

<div class="details">
<p>Compiled Content Loaded</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L801" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 801</a>

<h3 id="source">source</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Compiled.md#source'>Smarty_Template_Source</a></span><span class='no'> $source</span><span class='o'> = null</span>

<div class="details">
<p>Source Object</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L777" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 777</a>

<h3 id="timestamp">timestamp</h3>
<span class='k'></span> <span class='nx'>integer</span><span class='no'> $timestamp</span><span class='o'> = null</span>

<div class="details">
<p>Compiled Timestamp</p>
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_resource.php#L816" target='_blank'>framework\libs\smarty\sysplugins\smarty_resource.php at line 816</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md">Smarty_Template_Source</a> source)

<div class="details">
<p>create Compiled Object container</p><dl>
<dt>Parameters:</dt>
<dd>source - source object this compiled object belongs to</dd>
</dl>

</div>

- - -

