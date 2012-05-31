
- - -

**Doctrine\Common\Cache\MemcachedCache**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 37</div>
#Class MemcachedCache#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html">CacheProvider</a>
    ***MemcachedCache**


- - -

<p class="signature">public  class **MemcachedCache**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html">CacheProvider</a>

</p>

<div class="comment" id="overview_description"><p>Memcached cache provider.</p></div>

<dl>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/lgpl-license.php LGPL</dd>
<dt>See Also:</dt>
<dd><code>www.doctrine-project.org</code></dd>
<dt>Since:</dt>
<dd>2.2</dd>
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
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setmemcached">setMemcached</a>(Memcached memcached)</p><p class="description">Sets the memcache instance to use.</p></td>
</tr>
<tr>
<td class="type">  Memcached</td>
<td class="description"><p class="name"><a href="#getmemcached">getMemcached</a>()</p><p class="description">Gets the memcached instance used by the cache.</p></td>
</tr>
<tr>
<td class="type"> protected  string</td>
<td class="description"><p class="name"><a href="#dofetch">doFetch</a>(string id)</p><p class="description">Fetches an entry from the cache.</p></td>
</tr>
<tr>
<td class="type"> protected  boolean</td>
<td class="description"><p class="name"><a href="#docontains">doContains</a>(string id)</p><p class="description">Test if an entry exists in the cache.</p></td>
</tr>
<tr>
<td class="type"> protected  boolean</td>
<td class="description"><p class="name"><a href="#dosave">doSave</a>(string id, string data, int lifeTime)</p><p class="description">Puts data into the cache.</p></td>
</tr>
<tr>
<td class="type"> protected  boolean</td>
<td class="description"><p class="name"><a href="#dodelete">doDelete</a>(string id)</p><p class="description">Deletes a cache entry.</p></td>
</tr>
<tr>
<td class="type"> protected  boolean</td>
<td class="description"><p class="name"><a href="#doflush">doFlush</a>()</p><p class="description">Deletes all cache entries.</p></td>
</tr>
<tr>
<td class="type"> protected  array</td>
<td class="description"><p class="name"><a href="#dogetstats">doGetStats</a>()</p><p class="description">Retrieves cached information from data store</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Doctrine\Common\Cache\CacheProvider</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#delete()">delete</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#deleteAll()">deleteAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doContains()">doContains</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doDelete()">doDelete</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doFetch()">doFetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doFlush()">doFlush</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doGetStats()">doGetStats</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doSave()">doSave</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#flushAll()">flushAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#getStats()">getStats</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 49</div>
<h3 id="setMemcached()">setMemcached</h3>

public  void **setMemcached** (Memcached memcached)<div class="details">
<p>Sets the memcache instance to use.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 59</div>
<h3 id="getMemcached()">getMemcached</h3>

public  Memcached **getMemcached** ()<div class="details">
<p>Gets the memcached instance used by the cache.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 67</div>
<h3 id="doFetch()">doFetch</h3>

protected  string **doFetch** (string id)<div class="details">
<p>Fetches an entry from the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The id of the cache entry to fetch.</dd>
<dt>Returns:</dt>
<dd>The cached data or FALSE, if no cache entry exists for the given id.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 75</div>
<h3 id="doContains()">doContains</h3>

protected  boolean **doContains** (string id)<div class="details">
<p>Test if an entry exists in the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The cache id of the entry to check for.</dd>
<dt>Returns:</dt>
<dd>TRUE if a cache entry exists for the given cache id, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 83</div>
<h3 id="doSave()">doSave</h3>

protected  boolean **doSave** (string id, string data, int lifeTime)<div class="details">
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

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 91</div>
<h3 id="doDelete()">doDelete</h3>

protected  boolean **doDelete** (string id)<div class="details">
<p>Deletes a cache entry.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id</dd>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 99</div>
<h3 id="doFlush()">doFlush</h3>

protected  boolean **doFlush** ()<div class="details">
<p>Deletes all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\MemcachedCache.php at line 107</div>
<h3 id="doGetStats()">doGetStats</h3>

protected  array **doGetStats** ()<div class="details">
<p>Retrieves cached information from data store</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
<dt>Returns:</dt>
<dd>An associative array with server's statistics if available, NULL otherwise.</dd>
</dl>
</div>

- - -

