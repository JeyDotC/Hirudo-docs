

- - -

**Smarty\Smarty_Template_Cached**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L205" >framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 205</a>

#Class Smarty_Template_Cached#

**Smarty_Template_Cached**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Smarty_Template_Cached</span></p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Cache Data Container for Template Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#cache_id"> $cache_id</a>
                                </p><p class="description">Template Cache Id (Smarty_Internal_Template::$cache_id)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#compile_id"> $compile_id</a>
                                </p><p class="description">Template Compile Id (Smarty_Internal_Template::$compile_id)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#content"> $content</a>
                                </p><p class="description">Source Content</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#exists"> $exists</a>
                                </p><p class="description">Source Existance</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#filepath"> $filepath</a>
                                </p><p class="description">Source Filepath</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_cacheresource.html'>Smarty_CacheResource</a></span></td>
<td class="description"><p class="name" ><a href="#handler"> $handler</a>
                                </p><p class="description">CacheResource Handler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#is_locked"> $is_locked</a>
                                </p><p class="description">flag that cache is locked by this instance</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#lock_id"> $lock_id</a>
                                </p><p class="description">Id for cache locking</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#processed"> $processed</a>
                                </p><p class="description">Cache was processed</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_source.html'>Smarty_Template_Source</a></span></td>
<td class="description"><p class="name" ><a href="#source"> $source</a>
                                </p><p class="description">Source Object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name" ><a href="#timestamp"> $timestamp</a>
                                </p><p class="description">Source Timestamp</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#valid"> $valid</a>
                                </p><p class="description">Cache Is Valid</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.md">Smarty_Internal_Template</a> _template)</p><p class="description">create Cached Object container</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#write">write</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.md">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write this cache object to handler</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L283" >framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 283</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>create Cached Object container</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L362" >framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 362</a>

<h3 id="write()">write</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>write</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.md">Smarty_Internal_Template</a> _template, string content)

<div class="details">
<p>Write this cache object to handler</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>content - content to cache</dd>
<dt>Returns:</dt>
<dd>success</dd>
</dl>

</div>

- - -

