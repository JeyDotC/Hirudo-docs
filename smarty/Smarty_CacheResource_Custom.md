
- - -

**Smarty\Smarty_CacheResource_Custom**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 16#L16 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 16</a>

#Class Smarty_CacheResource_Custom#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html">Smarty_CacheResource</a>
    * **Smarty_CacheResource_Custom**




- - -

<p class="signature">public abstract  class **Smarty_CacheResource_Custom**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html">Smarty_CacheResource</a>

</p>

<div class="comment" id="overview_description"><p>Cache Handler API</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Cacher</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_CacheResource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#resources">resources</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#sysplugins">sysplugins</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#fetch">fetch</a>(string id, string name, string cache_id, string compile_id, string content, integer mtime)</p><p class="description">fetch cached content and its modification time from data source</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>integer|boolean</span></td>
<td class="description"><p class="name"><a href="#fetchtimestamp">fetchTimestamp</a>(string id, string name, string cache_id, string compile_id)</p><p class="description">Fetch cached content's modification timestamp from data source{@internal implementing this method is optional.
</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#save">save</a>(string id, string name, string cache_id, string compile_id, integer|null exp_time, string content)</p><p class="description">Save content to cache</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#delete">delete</a>(string name, string cache_id, string compile_id, integer|null exp_time)</p><p class="description">Delete content from cache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Cached Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populatetimestamp">populateTimestamp</a>(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">populate Cached Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>booelan</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Read the cached template and process the header</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#writecachedcontent">writeCachedContent</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write the rendered template output to cache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearall">clearAll</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, integer exp_time)</p><p class="description">Empty cache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clear">clear</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)</p><p class="description">Empty cache for a specific template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>booelan</span></td>
<td class="description"><p class="name"><a href="#haslock">hasLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Check is cache is locked for this template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#acquirelock">acquireLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Lock cache for this template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#releaselock">releaseLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Unlock cache for this template</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_CacheResource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#acquireLock()">acquireLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#clear()">clear</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#clearAll()">clearAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#getCachedContent()">getCachedContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#hasLock()">hasLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#invalidLoadedCache()">invalidLoadedCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#locked()">locked</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#process()">process</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#releaseLock()">releaseLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#writeCachedContent()">writeCachedContent</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 29#L29 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 29</a>

<h3 id="fetch()">fetch</h3>
<span class='k'>protected abstract </span> <span class='nx'>void</span> <span class='nf'>fetch</span> (string id, string name, string cache_id, string compile_id, string content, integer mtime)

<div class="details">
<p>fetch cached content and its modification time from data source</p><dl>
<dt>Parameters:</dt>
<dd>id - unique cache content identifier</dd>
<dd>name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>content - cached content</dd>
<dd>mtime - cache modification timestamp (epoch)</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 43#L43 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 43</a>

<h3 id="fetchTimestamp()">fetchTimestamp</h3>
<span class='k'>protected </span> <span class='nx'>integer|boolean</span> <span class='nf'>fetchTimestamp</span> (string id, string name, string cache_id, string compile_id)

<div class="details">
<p>Fetch cached content's modification timestamp from data source</p><p>implementing this method is optional.
Only implement it if modification times can be accessed faster than loading the complete cached content.}</p><dl>
<dt>Parameters:</dt>
<dd>id - unique cache content identifier</dd>
<dd>name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dt>Returns:</dt>
<dd>timestamp (epoch) the template was modified, or false if not found</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 59#L59 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 59</a>

<h3 id="save()">save</h3>
<span class='k'>protected abstract </span> <span class='nx'>boolean</span> <span class='nf'>save</span> (string id, string name, string cache_id, string compile_id, integer|null exp_time, string content)

<div class="details">
<p>Save content to cache</p><dl>
<dt>Parameters:</dt>
<dd>id - unique cache content identifier</dd>
<dd>name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>exp_time - seconds till expiration or null</dd>
<dd>content - content to cache</dd>
<dt>Returns:</dt>
<dd>success</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 70#L70 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 70</a>

<h3 id="delete()">delete</h3>
<span class='k'>protected abstract </span> <span class='nx'>integer</span> <span class='nf'>delete</span> (string name, string cache_id, string compile_id, integer|null exp_time)

<div class="details">
<p>Delete content from cache</p><dl>
<dt>Parameters:</dt>
<dd>name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>exp_time - seconds till expiration time in seconds or null</dd>
<dt>Returns:</dt>
<dd>number of deleted caches</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 79#L79 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 79</a>

<h3 id="populate()">populate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populate</span> (<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Cached Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 94#L94 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 94</a>

<h3 id="populateTimestamp()">populateTimestamp</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populateTimestamp</span> (<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
<p>populate Cached Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - cached object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 115#L115 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 115</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>booelan</span> <span class='nf'>process</span> (<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 147#L147 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 147</a>

<h3 id="writeCachedContent()">writeCachedContent</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>writeCachedContent</span> (<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 166#L166 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 166</a>

<h3 id="clearAll()">clearAll</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clearAll</span> (<a href="../smarty/smarty.html">Smarty</a> smarty, integer exp_time)

<div class="details">
<p>Empty cache</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>exp_time - expiration time (number of seconds, not timestamp)</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 182#L182 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 182</a>

<h3 id="clear()">clear</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clear</span> (<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)

<div class="details">
<p>Empty cache for a specific template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>resource_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>exp_time - expiration time (number of seconds, not timestamp)</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 195#L195 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 195</a>

<h3 id="hasLock()">hasLock</h3>
<span class='k'></span> <span class='nx'>booelan</span> <span class='nf'>hasLock</span> (<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 214#L214 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 214</a>

<h3 id="acquireLock()">acquireLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>acquireLock</span> (<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
<p>Lock cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 229#L229 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource_custom.php at line 229</a>

<h3 id="releaseLock()">releaseLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>releaseLock</span> (<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
<p>Unlock cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
</dl>
</div>

- - -

