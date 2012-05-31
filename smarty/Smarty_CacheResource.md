
- - -

**Smarty\Smarty_CacheResource**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L16 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 16</a>

#Class Smarty_CacheResource#

**Smarty_CacheResource**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource_custom.html">Smarty_CacheResource_Custom</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource_keyvaluestore.html">Smarty_CacheResource_KeyValueStore</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_cacheresource_file.html">Smarty_Internal_CacheResource_File</a> </dd>
</dl>



- - -

<p class="signature">public abstract  class **Smarty_CacheResource**</p>

<div class="comment" id="overview_description"><p>Cache Handler API</p></div>

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
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#resources"> $resources</a>
                                </p><p class="description">cache for Smarty_CacheResource instances</p></td>
</tr>
<tr>
<td><span class='k'>protected static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#sysplugins"> $sysplugins</a>
                                </p><p class="description">resource types provided by the core</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Cached Object with meta data from Resource</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#populatetimestamp">populateTimestamp</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">populate Cached Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>booelan</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Read the cached template and process header</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#writecachedcontent">writeCachedContent</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write the rendered template output to cache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getcachedcontent">getCachedContent</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Return cached content</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearall">clearAll</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, integer exp_time)</p><p class="description">Empty cache</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clear">clear</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)</p><p class="description">Empty cache for a specific template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#locked">locked</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#haslock">hasLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#acquirelock">acquireLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#releaselock">releaseLock</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_cacheresource.html>Smarty_CacheResource</a></span></td>
<td class="description"><p class="name"><a href="#load">load</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, string type)</p><p class="description">Load Cache Resource Handler</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#invalidloadedcache">invalidLoadedCache</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty)</p><p class="description">Invalid Loaded Cache Files</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L36 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 36</a>

<h3 id="populate()">populate</h3>
<span class='k'>abstract </span> <span class='nx'>void</span> <span class='nf'>populate</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)

<div class="details">
<p>populate Cached Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L44 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 44</a>

<h3 id="populateTimestamp()">populateTimestamp</h3>
<span class='k'>abstract </span> <span class='nx'>void</span> <span class='nf'>populateTimestamp</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
<p>populate Cached Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - cached object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L53 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 53</a>

<h3 id="process()">process</h3>
<span class='k'>abstract </span> <span class='nx'>booelan</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
<p>Read the cached template and process header</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>cached - cached object</dd>
<dt>Returns:</dt>
<dd>true or false if the cached content does not exist</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L62 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 62</a>

<h3 id="writeCachedContent()">writeCachedContent</h3>
<span class='k'>abstract </span> <span class='nx'>boolean</span> <span class='nf'>writeCachedContent</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L70 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 70</a>

<h3 id="getCachedContent()">getCachedContent</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getCachedContent</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)

<div class="details">
<p>Return cached content</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>content - content of cache</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L87 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 87</a>

<h3 id="clearAll()">clearAll</h3>
<span class='k'>abstract </span> <span class='nx'>integer</span> <span class='nf'>clearAll</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, integer exp_time)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L99 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 99</a>

<h3 id="clear()">clear</h3>
<span class='k'>abstract </span> <span class='nx'>integer</span> <span class='nf'>clear</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L102 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 102</a>

<h3 id="locked()">locked</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>locked</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L118 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 118</a>

<h3 id="hasLock()">hasLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>hasLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L124 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 124</a>

<h3 id="acquireLock()">acquireLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>acquireLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L130 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 130</a>

<h3 id="releaseLock()">releaseLock</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>releaseLock</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L144 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 144</a>

<h3 id="load()">load</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty_cacheresource.html>Smarty_CacheResource</a></span> <span class='nf'>load</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty, string type)

<div class="details">
<p>Load Cache Resource Handler</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
<dd>type - name of the cache resource</dd>
<dt>Returns:</dt>
<dd>Cache Resource Handler</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_cacheresource.php#L185 class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 185</a>

<h3 id="invalidLoadedCache()">invalidLoadedCache</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>invalidLoadedCache</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/smarty.html">Smarty</a> smarty)

<div class="details">
<p>Invalid Loaded Cache Files</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
</dl>
</div>

- - -

