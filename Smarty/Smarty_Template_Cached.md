

- - -

**Smarty\Smarty_Template_Cached**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L205" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 205</a>

#Class Smarty_Template_Cached#

**Smarty_Template_Cached**




- - -

<p><strong>public  class</strong> <span>Smarty_Template_Cached</span></p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Cache Data Container for Template Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#cache_id"> $cache_id</a>
                                </p><p class="description">Template Cache Id (Smarty_Internal_Template::$cache_id)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#compile_id"> $compile_id</a>
                                </p><p class="description">Template Compile Id (Smarty_Internal_Template::$compile_id)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#content"> $content</a>
                                </p><p class="description">Source Content</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#exists"> $exists</a>
                                </p><p class="description">Source Existance</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#filepath"> $filepath</a>
                                </p><p class="description">Source Filepath</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_CacheResource.md'>Smarty_CacheResource</a></span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#handler"> $handler</a>
                                </p><p class="description">CacheResource Handler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#is_locked"> $is_locked</a>
                                </p><p class="description">flag that cache is locked by this instance</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#lock_id"> $lock_id</a>
                                </p><p class="description">Id for cache locking</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#processed"> $processed</a>
                                </p><p class="description">Cache was processed</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md'>Smarty_Template_Source</a></span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#source"> $source</a>
                                </p><p class="description">Source Object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#timestamp"> $timestamp</a>
                                </p><p class="description">Source Timestamp</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Cached.md#valid"> $valid</a>
                                </p><p class="description">Cache Is Valid</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">create Cached Object container</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#write">write</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write this cache object to handler</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L258" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 258</a>

<h3 id="cache_id">cache_id</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $cache_id</span><span class='o'> = null</span>

<div class="details">
<p>Template Cache Id (Smarty_Internal_Template::$cache_id)</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L252" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 252</a>

<h3 id="compile_id">compile_id</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $compile_id</span><span class='o'> = null</span>

<div class="details">
<p>Template Compile Id (Smarty_Internal_Template::$compile_id)</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L216" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 216</a>

<h3 id="content">content</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $content</span><span class='o'> = null</span>

<div class="details">
<p>Source Content</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L228" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 228</a>

<h3 id="exists">exists</h3>
<span class='k'></span> <span class='nx'>boolean</span><span class='no'> $exists</span><span class='o'> = false</span>

<div class="details">
<p>Source Existance</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L210" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 210</a>

<h3 id="filepath">filepath</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $filepath</span><span class='o'> = false</span>

<div class="details">
<p>Source Filepath</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L246" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 246</a>

<h3 id="handler">handler</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_CacheResource.md'>Smarty_CacheResource</a></span><span class='no'> $handler</span><span class='o'> = null</span>

<div class="details">
<p>CacheResource Handler</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L270" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 270</a>

<h3 id="is_locked">is_locked</h3>
<span class='k'></span> <span class='nx'>bool</span><span class='no'> $is_locked</span><span class='o'> = false</span>

<div class="details">
<p>flag that cache is locked by this instance</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L264" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 264</a>

<h3 id="lock_id">lock_id</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $lock_id</span><span class='o'> = null</span>

<div class="details">
<p>Id for cache locking</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L240" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 240</a>

<h3 id="processed">processed</h3>
<span class='k'></span> <span class='nx'>boolean</span><span class='no'> $processed</span><span class='o'> = false</span>

<div class="details">
<p>Cache was processed</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L276" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 276</a>

<h3 id="source">source</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Template_Source.md'>Smarty_Template_Source</a></span><span class='no'> $source</span><span class='o'> = null</span>

<div class="details">
<p>Source Object</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L222" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 222</a>

<h3 id="timestamp">timestamp</h3>
<span class='k'></span> <span class='nx'>integer</span><span class='no'> $timestamp</span><span class='o'> = false</span>

<div class="details">
<p>Source Timestamp</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L234" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 234</a>

<h3 id="valid">valid</h3>
<span class='k'></span> <span class='nx'>boolean</span><span class='no'> $valid</span><span class='o'> = false</span>

<div class="details">
<p>Cache Is Valid</p>
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L283" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 283</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>create Cached Object container</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L362" target='_blank'>framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 362</a>

<h3 id="write()">write</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>write</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template, string content)

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

