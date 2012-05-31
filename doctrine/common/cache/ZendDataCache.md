- - -

**Doctrine\Common\Cache\ZendDataCache**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\ZendDataCache.php at line 31</div>
#Class ZendDataCache#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html">CacheProvider</a>
    ***ZendDataCache**


- - -

<p class="signature">public  class **ZendDataCache**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html">CacheProvider</a>

</p>

<div class="comment" id="overview_description"><p>Zend Data Cache cache driver.</p></div>

<dl>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/lgpl-license.php LGPL</dd>
<dt>See Also:</dt>
<dd><code>www.doctrine-project.org</code></dd>
<dt>Since:</dt>
<dd>2.0</dd>
<dt>Author:</dt>
<dd>Ralph Schindler <ralph.schindler@zend.com></dd>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">protected  string</td>
<td class="description"><p class="name"><a href="#doFetch">doFetch</a>(string id)</p><p class="description">Fetches an entry from the cache.</p></td>
</tr>
<tr>
<td class="type">protected  boolean</td>
<td class="description"><p class="name"><a href="#doContains">doContains</a>(string id)</p><p class="description">Test if an entry exists in the cache.</p></td>
</tr>
<tr>
<td class="type">protected  boolean</td>
<td class="description"><p class="name"><a href="#doSave">doSave</a>(string id, string data, int lifeTime)</p><p class="description">Puts data into the cache.</p></td>
</tr>
<tr>
<td class="type">protected  boolean</td>
<td class="description"><p class="name"><a href="#doDelete">doDelete</a>(string id)</p><p class="description">Deletes a cache entry.</p></td>
</tr>
<tr>
<td class="type">protected  boolean</td>
<td class="description"><p class="name"><a href="#doFlush">doFlush</a>()</p><p class="description">Deletes all cache entries.</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#doGetStats">doGetStats</a>()</p><p class="description">Retrieves cached information from data store</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Doctrine\Common\Cache\CacheProvider</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#delete()">delete</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#deleteAll()">deleteAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doContains()">doContains</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doDelete()">doDelete</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doFetch()">doFetch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doFlush()">doFlush</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doGetStats()">doGetStats</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#doSave()">doSave</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#flushAll()">flushAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/cache/cacheprovider.html#getStats()">getStats</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\ZendDataCache.php at line 36</div>
<h3 id="doFetch()">doFetch</h3>
```php
protected  string **doFetch**(string id)```
<div class="details">
<p>Fetches an entry from the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The id of the cache entry to fetch.</dd>
<dt>Returns:</dt>
<dd>The cached data or FALSE, if no cache entry exists for the given id.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\ZendDataCache.php at line 44</div>
<h3 id="doContains()">doContains</h3>
```php
protected  boolean **doContains**(string id)```
<div class="details">
<p>Test if an entry exists in the cache.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id The cache id of the entry to check for.</dd>
<dt>Returns:</dt>
<dd>TRUE if a cache entry exists for the given cache id, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\ZendDataCache.php at line 52</div>
<h3 id="doSave()">doSave</h3>
```php
protected  boolean **doSave**(string id, string data, int lifeTime)```
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

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\ZendDataCache.php at line 60</div>
<h3 id="doDelete()">doDelete</h3>
```php
protected  boolean **doDelete**(string id)```
<div class="details">
<p>Deletes a cache entry.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id</dd>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\ZendDataCache.php at line 68</div>
<h3 id="doFlush()">doFlush</h3>
```php
protected  boolean **doFlush**()```
<div class="details">
<p>Deletes all cache entries.</p><dl>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\ZendDataCache.php at line 80</div>
<h3 id="doGetStats()">doGetStats</h3>
```php
protected  array **doGetStats**()```
<div class="details">
<p>Retrieves cached information from data store</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
<dt>Returns:</dt>
<dd>An associative array with server's statistics if available, NULL otherwise.</dd>
</dl>
</div>

- - -

