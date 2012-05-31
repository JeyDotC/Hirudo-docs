
- - -

**Smarty\Smarty_Internal_CacheResource_File**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L19 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 19</a>

#Class Smarty_Internal_CacheResource_File#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html">Smarty_CacheResource</a>
    * **Smarty_Internal_CacheResource_File**




- - -

<p class="signature">public  class **Smarty_Internal_CacheResource_File**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html">Smarty_CacheResource</a>

</p>

<div class="comment" id="overview_description"><p>This class does contain all necessary methods for the HTML cache on file system</p><p>Implements the file system as resource for the HTML cache Version ussing nocache inserts.</p></div>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Cached Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populatetimestamp">populateTimestamp</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source)</p><p class="description">populate Cached Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>booelan</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Read the cached template and process its header</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#writecachedcontent">writeCachedContent</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write the rendered template output to cache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearall">clearAll</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, integer exp_time, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty)</p><p class="description">Empty cache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clear">clear</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> _template, string resource_name, string cache_id, string compile_id, integer exp_time, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty)</p><p class="description">Empty cache for a specific template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>booelan</span></td>
<td class="description"><p class="name"><a href="#haslock">hasLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Check is cache is locked for this template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#acquirelock">acquireLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Lock cache for this template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#releaselock">releaseLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Unlock cache for this template</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_CacheResource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#acquireLock()">acquireLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#clear()">clear</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#clearAll()">clearAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#getCachedContent()">getCachedContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#hasLock()">hasLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#invalidLoadedCache()">invalidLoadedCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#locked()">locked</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#process()">process</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#releaseLock()">releaseLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#writeCachedContent()">writeCachedContent</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L28 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 28</a>

<h3 id="populate()">populate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populate</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Cached Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L74 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 74</a>

<h3 id="populateTimestamp()">populateTimestamp</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>populateTimestamp</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source)

<div class="details">
<p>populate Cached Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L87 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 87</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>booelan</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
<p>Read the cached template and process its header</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>cached - cached object</dd>
<dt>Returns:</dt>
<dd>true or false if the cached content does not exist</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L100 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 100</a>

<h3 id="writeCachedContent()">writeCachedContent</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>writeCachedContent</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L117 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 117</a>

<h3 id="clearAll()">clearAll</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clearAll</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, integer exp_time, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty)

<div class="details">
<p>Empty cache</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>exp_time - expiration time (number of seconds, not timestamp)</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L132 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 132</a>

<h3 id="clear()">clear</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>clear</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> _template, string resource_name, string cache_id, string compile_id, integer exp_time, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty)

<div class="details">
<p>Empty cache for a specific template</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>resource_name - template name</dd>
<dd>cache_id - cache id</dd>
<dd>compile_id - compile id</dd>
<dd>exp_time - expiration time (number of seconds, not timestamp)</dd>
<dt>Returns:</dt>
<dd>number of cache files deleted</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L228 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 228</a>

<h3 id="hasLock()">hasLock</h3>
<span class='k'></span> <span class='nx'>booelan</span> <span class='nf'>hasLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L245 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 245</a>

<h3 id="acquireLock()">acquireLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>acquireLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
<p>Lock cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_cacheresource_file.php#L257 class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 257</a>

<h3 id="releaseLock()">releaseLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>releaseLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
<p>Unlock cache for this template</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>cached - cached object</dd>
</dl>
</div>

- - -

