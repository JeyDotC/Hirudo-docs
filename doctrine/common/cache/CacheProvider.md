- - -

**Doctrine\Common\Cache\CacheProvider**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 33</div>
#Class CacheProvider#

**CacheProvider**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cache.html">Cache</a> </dd>
</dl>

<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/apccache.html">ApcCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/arraycache.html">ArrayCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/memcachecache.html">MemcacheCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/memcachedcache.html">MemcachedCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/wincachecache.html">WincacheCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/xcachecache.html">XcacheCache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/zenddatacache.html">ZendDataCache</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **CacheProvider**</p>

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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#delete">delete</a>(mixed id)</p><p class="description">Deletes a cache entry.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getStats">getStats</a>()</p><p class="description">Retrieves cached information from data storeThe server's statistics array has the following values:- <b>hits</b>
Number of keys that have been requested and found present.- <b>misses</b>
Number of items that have been requested and not found.- <b>uptime</b>
Time that the server is running.- <b>memory_usage</b>
Memory used by this server to store items.- <b>memory_available</b>
Memory allowed to use for storage.</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#flushAll">flushAll</a>()</p><p class="description">Deletes all cache entries.</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#deleteAll">deleteAll</a>()</p><p class="description">Delete all cache entries.</p></td>
</tr>
<tr>
<td class="type">protected abstract  string</td>
<td class="description"><p class="name"><a href="#doFetch">doFetch</a>(string id)</p><p class="description">Fetches an entry from the cache.</p></td>
</tr>
<tr>
<td class="type">protected abstract  boolean</td>
<td class="description"><p class="name"><a href="#doContains">doContains</a>(string id)</p><p class="description">Test if an entry exists in the cache.</p></td>
</tr>
<tr>
<td class="type">protected abstract  boolean</td>
<td class="description"><p class="name"><a href="#doSave">doSave</a>(string id, string data, int lifeTime)</p><p class="description">Puts data into the cache.</p></td>
</tr>
<tr>
<td class="type">protected abstract  boolean</td>
<td class="description"><p class="name"><a href="#doDelete">doDelete</a>(string id)</p><p class="description">Deletes a cache entry.</p></td>
</tr>
<tr>
<td class="type">protected abstract  boolean</td>
<td class="description"><p class="name"><a href="#doFlush">doFlush</a>()</p><p class="description">Deletes all cache entries.</p></td>
</tr>
<tr>
<td class="type">protected abstract  array</td>
<td class="description"><p class="name"><a href="#doGetStats">doGetStats</a>()</p><p class="description">Retrieves cached information from data store</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 43</div>
<h3 id="delete()">delete</h3>

```php
public  void **delete**(mixed id)
```
<div class="details">
<p>Deletes a cache entry.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 51</div>
<h3 id="getStats()">getStats</h3>

```php
public  void **getStats**()
```
<div class="details">
<p>Retrieves cached information from data store</p><p>The server's statistics array has the following values:</p><p>- <b>hits</b>
Number of keys that have been requested and found present.</p><p>- <b>misses</b>
Number of items that have been requested and not found.</p><p>- <b>uptime</b>
Time that the server is running.</p><p>- <b>memory_usage</b>
Memory used by this server to store items.</p><p>- <b>memory_available</b>
Memory allowed to use for storage.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 61</div>
<h3 id="flushAll()">flushAll</h3>

```php
public  boolean **flushAll**()
```
<div class="details">
<p>Deletes all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entries were successfully flushed, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 71</div>
<h3 id="deleteAll()">deleteAll</h3>

```php
public  boolean **deleteAll**()
```
<div class="details">
<p>Delete all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entries were successfully deleted, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 99</div>
<h3 id="doFetch()">doFetch</h3>

```php
protected abstract  string **doFetch**(string id)
```
<div class="details">
<p>Fetches an entry from the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The id of the cache entry to fetch.</dd>
<dt>Returns:</dt>
<dd>The cached data or FALSE, if no cache entry exists for the given id.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 107</div>
<h3 id="doContains()">doContains</h3>

```php
protected abstract  boolean **doContains**(string id)
```
<div class="details">
<p>Test if an entry exists in the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The cache id of the entry to check for.</dd>
<dt>Returns:</dt>
<dd>TRUE if a cache entry exists for the given cache id, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 117</div>
<h3 id="doSave()">doSave</h3>

```php
protected abstract  boolean **doSave**(string id, string data, int lifeTime)
```
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

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 125</div>
<h3 id="doDelete()">doDelete</h3>

```php
protected abstract  boolean **doDelete**(string id)
```
<div class="details">
<p>Deletes a cache entry.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id</dd>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 132</div>
<h3 id="doFlush()">doFlush</h3>

```php
protected abstract  boolean **doFlush**()
```
<div class="details">
<p>Deletes all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\CacheProvider.php at line 140</div>
<h3 id="doGetStats()">doGetStats</h3>

```php
protected abstract  array **doGetStats**()
```
<div class="details">
<p>Retrieves cached information from data store</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
<dt>Returns:</dt>
<dd>An associative array with server's statistics if available, NULL otherwise.</dd>
</dl>
</div>

- - -

