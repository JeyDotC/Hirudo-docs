- - -

**Smarty\Smarty_CacheResource_KeyValueStore**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line34" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 34</a>

# Class Smarty_CacheResource_KeyValueStore #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html">Smarty_CacheResource</a>\n    *** Smarty_CacheResource_KeyValueStore **\n</pre>

- - -

<p class="signature">public abstract  class **Smarty_CacheResource_KeyValueStore**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html">Smarty_CacheResource</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Cache Handler Base for Key/Value Storage Implementations</p><p>This class implements the functionality required to use simple key/value stores
for hierarchical cache groups. key/value stores like memcache or APC do not support
wildcards in keys, therefore a cache group cannot be cleared like "a|*" - which
is no problem to filesystem and RDBMS implementations.</p><p>This implementation is based on the concept of invalidation. While one specific cache
can be identified and cleared, any range of caches cannot be identified. For this reason
each level of the cache group hierarchy can have its own value in the store. These values
are nothing but microtimes, telling us when a particular cache group was cleared for the
last time. These keys are evaluated for every cache read to determine if the cache has
been invalidated since it was created and should hence be treated as inexistent.</p><p>Although deep hierarchies are possible, they are not recommended. Try to keep your
cache groups as shallow as possible. Anything up 3-5 parents should be ok. So
»a|b|c« is a good depth where »a|b|c|d|e|f|g|h|i|j|k« isn't. Try to join correlating
cache groups: if your cache groups look somewhat like »a|b|$page|$items|$whatever«
consider using »a|b|c|$page-$items-$whatever« instead.</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Cacher</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#contents">$contents</a></p><p class="description">cache for contents</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#timestamps">$timestamps</a></p><p class="description">cache for timestamps</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_CacheResource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#resources">resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#sysplugins">sysplugins</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populate()">populate</a>(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Cached Object with meta data from Resource</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populateTimestamp()">populateTimestamp</a>(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source)</p><p class="description">populate Cached Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td class="type"> booelan</td>
<td class="description"><p class="name"><a href="#process()">process</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Read the cached template and process the header</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#writeCachedContent()">writeCachedContent</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write the rendered template output to cache</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#clearAll()">clearAll</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, integer exp_time)</p><p class="description">Empty cachethe $exp_time argument is ignored altogether}</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#clear()">clear</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)</p><p class="description">Empty cache for a specific templatethe $exp_time argument is ignored altogether}</p></td>
</tr>
<tr>
<td class="type">protected  string</td>
<td class="description"><p class="name"><a href="#getTemplateUid()">getTemplateUid</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id)</p><p class="description">Get template's unique ID</p></td>
</tr>
<tr>
<td class="type">protected  string</td>
<td class="description"><p class="name"><a href="#sanitize()">sanitize</a>(string string)</p><p class="description">Sanitize CacheID components</p></td>
</tr>
<tr>
<td class="type">protected  boolean</td>
<td class="description"><p class="name"><a href="#fetch()">fetch</a>(string cid, string resource_name, string cache_id, string compile_id, string content, integer &$timestamp, string resource_uid, mixed timestamp)</p><p class="description">Fetch and prepare a cache object.</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#addMetaTimestamp()">addMetaTimestamp</a>(string &$content, mixed content)</p><p class="description">Add current microtime to the beginning of $cache_contentthe header uses 8 Bytes, the first 4 Bytes are the seconds, the second 4 Bytes are the microseconds}</p></td>
</tr>
<tr>
<td class="type">protected  float</td>
<td class="description"><p class="name"><a href="#getMetaTimestamp()">getMetaTimestamp</a>(string &$content, mixed content)</p><p class="description">Extract the timestamp the $content was cached</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#invalidate()">invalidate</a>(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)</p><p class="description">Invalidate CacheID</p></td>
</tr>
<tr>
<td class="type">protected  float</td>
<td class="description"><p class="name"><a href="#getLatestInvalidationTimestamp()">getLatestInvalidationTimestamp</a>(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)</p><p class="description">Determine the latest timestamp known to the invalidation chain</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#listInvalidationKeys()">listInvalidationKeys</a>(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)</p><p class="description">Translate a CacheID into the list of applicable InvalidationKeys.
</p></td>
</tr>
<tr>
<td class="type"> booelan</td>
<td class="description"><p class="name"><a href="#hasLock()">hasLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Check is cache is locked for this template</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#acquireLock()">acquireLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Lock cache for this template</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#releaseLock()">releaseLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Unlock cache for this template</p></td>
</tr>
<tr>
<td class="type">protected abstract  array</td>
<td class="description"><p class="name"><a href="#read()">read</a>(array keys)</p><p class="description">Read values for a set of keys from cache</p></td>
</tr>
<tr>
<td class="type">protected abstract  boolean</td>
<td class="description"><p class="name"><a href="#write()">write</a>(array keys, int expire)</p><p class="description">Save values for a set of keys to cache</p></td>
</tr>
<tr>
<td class="type">protected abstract  boolean</td>
<td class="description"><p class="name"><a href="#delete()">delete</a>(array keys)</p><p class="description">Remove values from cache</p></td>
</tr>
<tr>
<td class="type">protected  boolean</td>
<td class="description"><p class="name"><a href="#purge()">purge</a>()</p><p class="description">Remove *all* values from cache</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_CacheResource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#acquireLock()">acquireLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#clear()">clear</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#clearAll()">clearAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#getCachedContent()">getCachedContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#hasLock()">hasLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#invalidLoadedCache()">invalidLoadedCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#locked()">locked</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#process()">process</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#releaseLock()">releaseLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#writeCachedContent()">writeCachedContent</a></td></tr></table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line40" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 40</a>

<h3 id="contents">contents</h3>
```php
protected  array **$contents** = array()```
<div class="details">
<p>cache for contents</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line45" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 45</a>

<h3 id="timestamps">timestamps</h3>
```php
protected  array **$timestamps** = array()```
<div class="details">
<p>cache for timestamps</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line54" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 54</a>

<h3 id="populate()">populate</h3>
```php
public  void **populate**(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)```
<div class="details">
<p>populate Cached Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line70" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 70</a>

<h3 id="populateTimestamp()">populateTimestamp</h3>
```php
public  void **populateTimestamp**(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source)```
<div class="details">
<p>populate Cached Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line87" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 87</a>

<h3 id="process()">process</h3>
```php
public  booelan **process**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)```
<div class="details">
<p>Read the cached template and process the header</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>cached - cached object</dd>
<dt>Returns:</dt>
<dd>true or false if the cached content does not exist</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line114" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 114</a>

<h3 id="writeCachedContent()">writeCachedContent</h3>
```php
public  boolean **writeCachedContent**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)```
<div class="details">
<p>Write the rendered template output to cache</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>content - content to cache</dd>
<dt>Returns:</dt>
<dd>success</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line131" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 131</a>

<h3 id="clearAll()">clearAll</h3>
```php
public  integer **clearAll**(<a href="../smarty/smarty.html">Smarty</a> smarty, integer exp_time)```
<div class="details">
<p>Empty cache</p><p>the $exp_time argument is ignored altogether}</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>exp_time - expiration time [being ignored]</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted [always -1]</dd>
<dt>Uses:</dt>
<dd>purge() to clear the whole store</dd>
<dd>invalidate() to mark everything outdated if purge() is inapplicable</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line154" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 154</a>

<h3 id="clear()">clear</h3>
```php
public  integer **clear**(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)```
<div class="details">
<p>Empty cache for a specific template</p><p>the $exp_time argument is ignored altogether}</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>resource_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>exp_time - expiration time [being ignored]</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted [always -1]</dd>
<dt>Uses:</dt>
<dd>buildCachedFilepath() to generate the CacheID</dd>
<dd>invalidate() to mark CacheIDs parent chain as outdated</dd>
<dd>delete() to remove CacheID from cache</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line171" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 171</a>

<h3 id="getTemplateUid()">getTemplateUid</h3>
```php
protected  string **getTemplateUid**(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id)```
<div class="details">
<p>Get template's unique ID</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>resource_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dt>Returns:</dt>
<dd>filepath of cache file</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line200" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 200</a>

<h3 id="sanitize()">sanitize</h3>
```php
protected  string **sanitize**(string string)```
<div class="details">
<p>Sanitize CacheID components</p><dl>
<dt>Parameters:</dt>
<dd>string - CacheID component to sanitize</dd>
<dt>Returns:</dt>
<dd>sanitized CacheID component</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line222" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 222</a>

<h3 id="fetch()">fetch</h3>
```php
protected  boolean **fetch**(string cid, string resource_name, string cache_id, string compile_id, string content, integer &$timestamp, string resource_uid, mixed timestamp)```
<div class="details">
<p>Fetch and prepare a cache object.</p><dl>
<dt>Parameters:</dt>
<dd>cid - CacheID to fetch</dd>
<dd>resource_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>content - cached content</dd>
<dd>&$timestamp - cached timestamp (epoch)</dd>
<dd>resource_uid - resource's uid</dd>
<dt>Returns:</dt>
<dd>success</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line246" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 246</a>

<h3 id="addMetaTimestamp()">addMetaTimestamp</h3>
```php
protected  void **addMetaTimestamp**(string &$content, mixed content)```
<div class="details">
<p>Add current microtime to the beginning of $cache_content</p><p>the header uses 8 Bytes, the first 4 Bytes are the seconds, the second 4 Bytes are the microseconds}</p><dl>
<dt>Parameters:</dt>
<dd>&$content - the content to be cached</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line259" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 259</a>

<h3 id="getMetaTimestamp()">getMetaTimestamp</h3>
```php
protected  float **getMetaTimestamp**(string &$content, mixed content)```
<div class="details">
<p>Extract the timestamp the $content was cached</p><dl>
<dt>Parameters:</dt>
<dd>&$content - the cached content</dd>
<dt>Returns:</dt>
<dd>the microtime the content was cached</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line277" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 277</a>

<h3 id="invalidate()">invalidate</h3>
```php
protected  void **invalidate**(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)```
<div class="details">
<p>Invalidate CacheID</p><dl>
<dt>Parameters:</dt>
<dd>cid - CacheID</dd>
<dd>resource_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>resource_uid - source's uid</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line314" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 314</a>

<h3 id="getLatestInvalidationTimestamp()">getLatestInvalidationTimestamp</h3>
```php
protected  float **getLatestInvalidationTimestamp**(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)```
<div class="details">
<p>Determine the latest timestamp known to the invalidation chain</p><dl>
<dt>Parameters:</dt>
<dd>cid - CacheID to determine latest invalidation timestamp of</dd>
<dd>resource_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>resource_uid - source's filepath</dd>
<dt>Returns:</dt>
<dd>the microtime the CacheID was invalidated</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line347" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 347</a>

<h3 id="listInvalidationKeys()">listInvalidationKeys</h3>
```php
protected  array **listInvalidationKeys**(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)```
<div class="details">
<p>Translate a CacheID into the list of applicable InvalidationKeys.</p><p>Splits "some|chain|into|an|array" into array( '#clearAll#', 'some', 'some|chain', 'some|chain|into', ... )</p><dl>
<dt>Parameters:</dt>
<dd>cid - CacheID to translate</dd>
<dd>resource_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>resource_uid - source's filepath</dd>
<dt>Returns:</dt>
<dd>list of InvalidationKeys</dd>
<dt>Uses:</dt>
<dd>$invalidationKeyPrefix to prepend to each InvalidationKey</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line393" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 393</a>

<h3 id="hasLock()">hasLock</h3>
```php
public  booelan **hasLock**(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)```
<div class="details">
<p>Check is cache is locked for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
<dt>Returns:</dt>
<dd>true or false if cache is locked</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line406" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 406</a>

<h3 id="acquireLock()">acquireLock</h3>
```php
public  void **acquireLock**(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)```
<div class="details">
<p>Lock cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line419" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 419</a>

<h3 id="releaseLock()">releaseLock</h3>
```php
public  void **releaseLock**(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)```
<div class="details">
<p>Unlock cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line432" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 432</a>

<h3 id="read()">read</h3>
```php
protected abstract  array **read**(array keys)```
<div class="details">
<p>Read values for a set of keys from cache</p><dl>
<dt>Parameters:</dt>
<dd>keys - list of keys to fetch</dd>
<dt>Returns:</dt>
<dd>list of values with the given keys used as indexes</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line441" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 441</a>

<h3 id="write()">write</h3>
```php
protected abstract  boolean **write**(array keys, int expire)```
<div class="details">
<p>Save values for a set of keys to cache</p><dl>
<dt>Parameters:</dt>
<dd>keys - list of values to save</dd>
<dd>expire - expiration time</dd>
<dt>Returns:</dt>
<dd>true on success, false on failure</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line449" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 449</a>

<h3 id="delete()">delete</h3>
```php
protected abstract  boolean **delete**(array keys)```
<div class="details">
<p>Remove values from cache</p><dl>
<dt>Parameters:</dt>
<dd>keys - list of keys to delete</dd>
<dt>Returns:</dt>
<dd>true on success, false on failure</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php.md#line456" class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 456</a>

<h3 id="purge()">purge</h3>
```php
protected  boolean **purge**()```
<div class="details">
<p>Remove *all* values from cache</p><dl>
<dt>Returns:</dt>
<dd>true on success, false on failure</dd>
</dl>
</div>

- - -

