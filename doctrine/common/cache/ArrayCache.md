

- - -

**Doctrine\Common\Cache\ArrayCache**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/ArrayCache.php#L36" >framework\libs\doctrine-common\Doctrine\Common\Cache\ArrayCache.php at line 36</a>

#Class ArrayCache#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md">CacheProvider</a>
    * **ArrayCache**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>ArrayCache</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md">CacheProvider</a>

</p>

<div class="comment" id="overview_description"><p>Array cache driver.</p></div>

<dl>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/lgpl-license.php LGPL</dd>
<dt>See Also:</dt>
<dd><code>www.doctrine-project.org</code></dd>
<dt>Since:</dt>
<dd>2.0</dd>
<dt>Author:</dt>
<dd>Benjamin Eberlei <kontakt@beberlei.de></dd>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
<dd>David Abdemoulaie <dave@hobodave.com></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#dofetch">doFetch</a>(string id)</p><p class="description">Fetches an entry from the cache.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#docontains">doContains</a>(string id)</p><p class="description">Test if an entry exists in the cache.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#dosave">doSave</a>(string id, string data, int lifeTime)</p><p class="description">Puts data into the cache.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#dodelete">doDelete</a>(string id)</p><p class="description">Deletes a cache entry.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#doflush">doFlush</a>()</p><p class="description">Deletes all cache entries.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#dogetstats">doGetStats</a>()</p><p class="description">Retrieves cached information from data store</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Doctrine\Common\Cache\CacheProvider</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#delete">delete</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#deleteAll">deleteAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#doContains">doContains</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#doDelete">doDelete</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#doFetch">doFetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#doFlush">doFlush</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#doGetStats">doGetStats</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#doSave">doSave</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#flushAll">flushAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/CacheProvider.md#getStats">getStats</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/ArrayCache.php#L46" >framework\libs\doctrine-common\Doctrine\Common\Cache\ArrayCache.php at line 46</a>

<h3 id="doFetch()">doFetch</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>doFetch</span> (string id)

<div class="details">
<p>Fetches an entry from the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The id of the cache entry to fetch.</dd>
<dt>Returns:</dt>
<dd>The cached data or FALSE, if no cache entry exists for the given id.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/ArrayCache.php#L54" >framework\libs\doctrine-common\Doctrine\Common\Cache\ArrayCache.php at line 54</a>

<h3 id="doContains()">doContains</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>doContains</span> (string id)

<div class="details">
<p>Test if an entry exists in the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The cache id of the entry to check for.</dd>
<dt>Returns:</dt>
<dd>TRUE if a cache entry exists for the given cache id, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/ArrayCache.php#L62" >framework\libs\doctrine-common\Doctrine\Common\Cache\ArrayCache.php at line 62</a>

<h3 id="doSave()">doSave</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>doSave</span> (string id, string data, int lifeTime)

<div class="details">
<p>Puts data into the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - The cache id.</dd>
<dd>data - The cache entry/data.</dd>
<dd>lifeTime - The lifetime. If != false, sets a specific lifetime for this cache entry (null => infinite lifeTime).</dd>
<dt>Returns:</dt>
<dd>TRUE if the entry was successfully stored in the cache, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/ArrayCache.php#L72" >framework\libs\doctrine-common\Doctrine\Common\Cache\ArrayCache.php at line 72</a>

<h3 id="doDelete()">doDelete</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>doDelete</span> (string id)

<div class="details">
<p>Deletes a cache entry.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id</dd>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/ArrayCache.php#L82" >framework\libs\doctrine-common\Doctrine\Common\Cache\ArrayCache.php at line 82</a>

<h3 id="doFlush()">doFlush</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>doFlush</span> ()

<div class="details">
<p>Deletes all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/ArrayCache.php#L92" >framework\libs\doctrine-common\Doctrine\Common\Cache\ArrayCache.php at line 92</a>

<h3 id="doGetStats()">doGetStats</h3>
<span class='k'>protected </span> <span class='nx'>array</span> <span class='nf'>doGetStats</span> ()

<div class="details">
<p>Retrieves cached information from data store</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
<dt>Returns:</dt>
<dd>An associative array with server's statistics if available, NULL otherwise.</dd>
</dl>

</div>

- - -

