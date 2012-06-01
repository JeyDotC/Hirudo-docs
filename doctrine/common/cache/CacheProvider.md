

- - -

**Doctrine\Common\Cache\CacheProvider**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L33" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 33</a>

#Class CacheProvider#

**CacheProvider**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/Cache.md">Cache</a> </dd>
</dl>

<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/ApcCache.md">ApcCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/ArrayCache.md">ArrayCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/MemcacheCache.md">MemcacheCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/MemcachedCache.md">MemcachedCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/WincacheCache.md">WincacheCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/XcacheCache.md">XcacheCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/ZendDataCache.md">ZendDataCache</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>CacheProvider</span></p>

<div class="comment" id="overview_description"><p>Base class for cache provider implementations.</p></div>

<dl>
<dt>Since:</dt>
<dd>2.2</dd>
<dt>Author:</dt>
<dd>Benjamin Eberlei <kontakt@beberlei.de></dd>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
<dd>Fabio B. Silva <fabio.bat.silva@gmail.com></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#delete">delete</a>(mixed id)</p><p class="description">Deletes a cache entry.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getstats">getStats</a>()</p><p class="description">Retrieves cached information from data storeThe server's statistics array has the following values:- <b>hits</b>
Number of keys that have been requested and found present.- <b>misses</b>
Number of items that have been requested and not found.- <b>uptime</b>
Time that the server is running.- <b>memory_usage</b>
Memory used by this server to store items.- <b>memory_available</b>
Memory allowed to use for storage.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#flushall">flushAll</a>()</p><p class="description">Deletes all cache entries.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#deleteall">deleteAll</a>()</p><p class="description">Delete all cache entries.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#dofetch">doFetch</a>(string id)</p><p class="description">Fetches an entry from the cache.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#docontains">doContains</a>(string id)</p><p class="description">Test if an entry exists in the cache.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#dosave">doSave</a>(string id, string data, int lifeTime)</p><p class="description">Puts data into the cache.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#dodelete">doDelete</a>(string id)</p><p class="description">Deletes a cache entry.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#doflush">doFlush</a>()</p><p class="description">Deletes all cache entries.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#dogetstats">doGetStats</a>()</p><p class="description">Retrieves cached information from data store</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L43" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 43</a>

<h3 id="delete()">delete</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>delete</span> (mixed id)

<div class="details">
<p>Deletes a cache entry.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L51" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 51</a>

<h3 id="getStats()">getStats</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getStats</span> ()

<div class="details">
<p>Retrieves cached information from data store</p><p>The server's statistics array has the following values:</p><p>- <b>hits</b>
Number of keys that have been requested and found present.</p><p>- <b>misses</b>
Number of items that have been requested and not found.</p><p>- <b>uptime</b>
Time that the server is running.</p><p>- <b>memory_usage</b>
Memory used by this server to store items.</p><p>- <b>memory_available</b>
Memory allowed to use for storage.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L61" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 61</a>

<h3 id="flushAll()">flushAll</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>flushAll</span> ()

<div class="details">
<p>Deletes all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entries were successfully flushed, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L71" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 71</a>

<h3 id="deleteAll()">deleteAll</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>deleteAll</span> ()

<div class="details">
<p>Delete all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entries were successfully deleted, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L99" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 99</a>

<h3 id="doFetch()">doFetch</h3>
<span class='k'>protected abstract </span> <span class='nx'>string</span> <span class='nf'>doFetch</span> (string id)

<div class="details">
<p>Fetches an entry from the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The id of the cache entry to fetch.</dd>
<dt>Returns:</dt>
<dd>The cached data or FALSE, if no cache entry exists for the given id.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L107" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 107</a>

<h3 id="doContains()">doContains</h3>
<span class='k'>protected abstract </span> <span class='nx'>boolean</span> <span class='nf'>doContains</span> (string id)

<div class="details">
<p>Test if an entry exists in the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The cache id of the entry to check for.</dd>
<dt>Returns:</dt>
<dd>TRUE if a cache entry exists for the given cache id, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L117" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 117</a>

<h3 id="doSave()">doSave</h3>
<span class='k'>protected abstract </span> <span class='nx'>boolean</span> <span class='nf'>doSave</span> (string id, string data, int lifeTime)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L125" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 125</a>

<h3 id="doDelete()">doDelete</h3>
<span class='k'>protected abstract </span> <span class='nx'>boolean</span> <span class='nf'>doDelete</span> (string id)

<div class="details">
<p>Deletes a cache entry.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id</dd>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L132" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 132</a>

<h3 id="doFlush()">doFlush</h3>
<span class='k'>protected abstract </span> <span class='nx'>boolean</span> <span class='nf'>doFlush</span> ()

<div class="details">
<p>Deletes all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Cache/CacheProvider.php#L140" >framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 140</a>

<h3 id="doGetStats()">doGetStats</h3>
<span class='k'>protected abstract </span> <span class='nx'>array</span> <span class='nf'>doGetStats</span> ()

<div class="details">
<p>Retrieves cached information from data store</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
<dt>Returns:</dt>
<dd>An associative array with server's statistics if available, NULL otherwise.</dd>
</dl>

</div>

- - -

