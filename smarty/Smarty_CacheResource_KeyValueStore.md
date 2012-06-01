

- - -

**Smarty\Smarty_CacheResource_KeyValueStore**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L34" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 34</a>

#Class Smarty_CacheResource_KeyValueStore#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md">Smarty_CacheResource</a>
    * **Smarty_CacheResource_KeyValueStore**




- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>Smarty_CacheResource_KeyValueStore</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md">Smarty_CacheResource</a>

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
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#contents"> $contents</a>
                                </p><p class="description">cache for contents</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#timestamps"> $timestamps</a>
                                </p><p class="description">cache for timestamps</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_CacheResource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#resources">resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#sysplugins">sysplugins</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)</p><p class="description">populate Cached Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populatetimestamp">populateTimestamp</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> source)</p><p class="description">populate Cached Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>booelan</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached)</p><p class="description">Read the cached template and process the header</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#writecachedcontent">writeCachedContent</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write the rendered template output to cache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearall">clearAll</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, integer exp_time)</p><p class="description">Empty cachethe $exp_time argument is ignored altogether}</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clear">clear</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)</p><p class="description">Empty cache for a specific templatethe $exp_time argument is ignored altogether}</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#gettemplateuid">getTemplateUid</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource_name, string cache_id, string compile_id)</p><p class="description">Get template's unique ID</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#sanitize">sanitize</a>(string string)</p><p class="description">Sanitize CacheID components</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#fetch">fetch</a>(string cid, string resource_name, string cache_id, string compile_id, string content, integer &$timestamp, string resource_uid, mixed timestamp)</p><p class="description">Fetch and prepare a cache object.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addmetatimestamp">addMetaTimestamp</a>(string &$content, mixed content)</p><p class="description">Add current microtime to the beginning of $cache_contentthe header uses 8 Bytes, the first 4 Bytes are the seconds, the second 4 Bytes are the microseconds}</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>float</span></td>
<td class="description"><p class="name"><a href="#getmetatimestamp">getMetaTimestamp</a>(string &$content, mixed content)</p><p class="description">Extract the timestamp the $content was cached</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#invalidate">invalidate</a>(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)</p><p class="description">Invalidate CacheID</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>float</span></td>
<td class="description"><p class="name"><a href="#getlatestinvalidationtimestamp">getLatestInvalidationTimestamp</a>(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)</p><p class="description">Determine the latest timestamp known to the invalidation chain</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#listinvalidationkeys">listInvalidationKeys</a>(string cid, string resource_name, string cache_id, string compile_id, string resource_uid)</p><p class="description">Translate a CacheID into the list of applicable InvalidationKeys.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>booelan</span></td>
<td class="description"><p class="name"><a href="#haslock">hasLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached)</p><p class="description">Check is cache is locked for this template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#acquirelock">acquireLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached)</p><p class="description">Lock cache for this template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#releaselock">releaseLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached)</p><p class="description">Unlock cache for this template</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#read">read</a>(array keys)</p><p class="description">Read values for a set of keys from cache</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#write">write</a>(array keys, int expire)</p><p class="description">Save values for a set of keys to cache</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#delete">delete</a>(array keys)</p><p class="description">Remove values from cache</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#purge">purge</a>()</p><p class="description">Remove *all* values from cache</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_CacheResource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#acquireLock">acquireLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#clear">clear</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#clearAll">clearAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#getCachedContent">getCachedContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#hasLock">hasLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#invalidLoadedCache">invalidLoadedCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#load">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#locked">locked</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#populate">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#populateTimestamp">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#process">process</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#releaseLock">releaseLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_CacheResource.md#writeCachedContent">writeCachedContent</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L54" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 54</a>

<h3 id="populate()">populate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populate</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Cached Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
<dd>_template - template object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L70" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 70</a>

<h3 id="populateTimestamp()">populateTimestamp</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populateTimestamp</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> source)

<div class="details">
<p>populate Cached Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L87" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 87</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>booelan</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L114" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 114</a>

<h3 id="writeCachedContent()">writeCachedContent</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>writeCachedContent</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> _template, string content)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L131" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 131</a>

<h3 id="clearAll()">clearAll</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clearAll</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, integer exp_time)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L154" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 154</a>

<h3 id="clear()">clear</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clear</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L171" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 171</a>

<h3 id="getTemplateUid()">getTemplateUid</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>getTemplateUid</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, string resource_name, string cache_id, string compile_id)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L200" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 200</a>

<h3 id="sanitize()">sanitize</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>sanitize</span> (string string)

<div class="details">
<p>Sanitize CacheID components</p><dl>
<dt>Parameters:</dt>
<dd>string - CacheID component to sanitize</dd>
<dt>Returns:</dt>
<dd>sanitized CacheID component</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L222" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 222</a>

<h3 id="fetch()">fetch</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>fetch</span> (string cid, string resource_name, string cache_id, string compile_id, string content, integer &$timestamp, string resource_uid, mixed timestamp)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L246" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 246</a>

<h3 id="addMetaTimestamp()">addMetaTimestamp</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>addMetaTimestamp</span> (string &$content, mixed content)

<div class="details">
<p>Add current microtime to the beginning of $cache_content</p><p>the header uses 8 Bytes, the first 4 Bytes are the seconds, the second 4 Bytes are the microseconds}</p><dl>
<dt>Parameters:</dt>
<dd>&$content - the content to be cached</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L259" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 259</a>

<h3 id="getMetaTimestamp()">getMetaTimestamp</h3>
<span class='k'>protected </span> <span class='nx'>float</span> <span class='nf'>getMetaTimestamp</span> (string &$content, mixed content)

<div class="details">
<p>Extract the timestamp the $content was cached</p><dl>
<dt>Parameters:</dt>
<dd>&$content - the cached content</dd>
<dt>Returns:</dt>
<dd>the microtime the content was cached</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L277" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 277</a>

<h3 id="invalidate()">invalidate</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>invalidate</span> (string cid, string resource_name, string cache_id, string compile_id, string resource_uid)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L314" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 314</a>

<h3 id="getLatestInvalidationTimestamp()">getLatestInvalidationTimestamp</h3>
<span class='k'>protected </span> <span class='nx'>float</span> <span class='nf'>getLatestInvalidationTimestamp</span> (string cid, string resource_name, string cache_id, string compile_id, string resource_uid)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L347" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 347</a>

<h3 id="listInvalidationKeys()">listInvalidationKeys</h3>
<span class='k'>protected </span> <span class='nx'>array</span> <span class='nf'>listInvalidationKeys</span> (string cid, string resource_name, string cache_id, string compile_id, string resource_uid)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L393" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 393</a>

<h3 id="hasLock()">hasLock</h3>
<span class='k'></span> <span class='nx'>booelan</span> <span class='nf'>hasLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L406" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 406</a>

<h3 id="acquireLock()">acquireLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>acquireLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached)

<div class="details">
<p>Lock cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L419" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 419</a>

<h3 id="releaseLock()">releaseLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>releaseLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Template_Cached.md">Smarty_Template_Cached</a> cached)

<div class="details">
<p>Unlock cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L432" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 432</a>

<h3 id="read()">read</h3>
<span class='k'>protected abstract </span> <span class='nx'>array</span> <span class='nf'>read</span> (array keys)

<div class="details">
<p>Read values for a set of keys from cache</p><dl>
<dt>Parameters:</dt>
<dd>keys - list of keys to fetch</dd>
<dt>Returns:</dt>
<dd>list of values with the given keys used as indexes</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L441" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 441</a>

<h3 id="write()">write</h3>
<span class='k'>protected abstract </span> <span class='nx'>boolean</span> <span class='nf'>write</span> (array keys, int expire)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L449" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 449</a>

<h3 id="delete()">delete</h3>
<span class='k'>protected abstract </span> <span class='nx'>boolean</span> <span class='nf'>delete</span> (array keys)

<div class="details">
<p>Remove values from cache</p><dl>
<dt>Parameters:</dt>
<dd>keys - list of keys to delete</dd>
<dt>Returns:</dt>
<dd>true on success, false on failure</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource_keyvaluestore.php#L456" >framework\libs\smarty\sysplugins\smarty_cacheresource_keyvaluestore.php at line 456</a>

<h3 id="purge()">purge</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>purge</span> ()

<div class="details">
<p>Remove *all* values from cache</p><dl>
<dt>Returns:</dt>
<dd>true on success, false on failure</dd>
</dl>

</div>

- - -

