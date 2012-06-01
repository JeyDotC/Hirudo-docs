

- - -

**Doctrine\Common\Cache\MemcacheCache**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L37" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 37</a>

#Class MemcacheCache#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html">CacheProvider</a>
    * **MemcacheCache**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>MemcacheCache</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html">CacheProvider</a>

</p>

<div class="comment" id="overview_description"><p>Memcache cache provider.</p></div>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setmemcache">setMemcache</a>(Memcache memcache)</p><p class="description">Sets the memcache instance to use.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Memcache</span></td>
<td class="description"><p class="name"><a href="#getmemcache">getMemcache</a>()</p><p class="description">Gets the memcache instance used by the cache.</p></td>
</tr>
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
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#delete()">delete</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#deleteAll()">deleteAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doContains()">doContains</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doDelete()">doDelete</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doFetch()">doFetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doFlush()">doFlush</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doGetStats()">doGetStats</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doSave()">doSave</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#flushAll()">flushAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#getStats()">getStats</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L49" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 49</a>

<h3 id="setMemcache()">setMemcache</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setMemcache</span> (Memcache memcache)

<div class="details">
<p>Sets the memcache instance to use.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L59" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 59</a>

<h3 id="getMemcache()">getMemcache</h3>
<span class='k'></span> <span class='nx'>Memcache</span> <span class='nf'>getMemcache</span> ()

<div class="details">
<p>Gets the memcache instance used by the cache.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L67" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 67</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L75" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 75</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L83" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 83</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L91" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 91</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L99" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 99</a>

<h3 id="doFlush()">doFlush</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>doFlush</span> ()

<div class="details">
<p>Deletes all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/MemcacheCache.php#L107" >framework\libs\doctrine-common\Doctrine\Common\Cache\MemcacheCache.php at line 107</a>

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

