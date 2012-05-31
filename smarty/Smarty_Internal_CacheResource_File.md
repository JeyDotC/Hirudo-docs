- - -

**Smarty\Smarty_Internal_CacheResource_File**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 19</div>
#Class Smarty_Internal_CacheResource_File#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html">Smarty_CacheResource</a>
    ***Smarty_Internal_CacheResource_File**


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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Cached Object with meta data from Resource</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#populateTimestamp">populateTimestamp</a>(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source)</p><p class="description">populate Cached Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td class="type"> booelan</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Read the cached template and process its header</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#writeCachedContent">writeCachedContent</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write the rendered template output to cache</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#clearAll">clearAll</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, integer exp_time, <a href="../smarty/smarty.html">Smarty</a> smarty)</p><p class="description">Empty cache</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#clear">clear</a>(<a href="../smarty/smarty.html">Smarty</a> _template, string resource_name, string cache_id, string compile_id, integer exp_time, <a href="../smarty/smarty.html">Smarty</a> smarty)</p><p class="description">Empty cache for a specific template</p></td>
</tr>
<tr>
<td class="type"> booelan</td>
<td class="description"><p class="name"><a href="#hasLock">hasLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Check is cache is locked for this template</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#acquireLock">acquireLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Lock cache for this template</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#releaseLock">releaseLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Unlock cache for this template</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_CacheResource</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#acquireLock()">acquireLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#clear()">clear</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#clearAll()">clearAll</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#getCachedContent()">getCachedContent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#hasLock()">hasLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#invalidLoadedCache()">invalidLoadedCache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#load()">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#locked()">locked</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#populate()">populate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#populateTimestamp()">populateTimestamp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#process()">process</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#releaseLock()">releaseLock</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_cacheresource.html#writeCachedContent()">writeCachedContent</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 28</div>
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 74</div>
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 87</div>
<h3 id="process()">process</h3>
```php
public  booelan **process**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 100</div>
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 117</div>
<h3 id="clearAll()">clearAll</h3>
```php
public  integer **clearAll**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, integer exp_time, <a href="../smarty/smarty.html">Smarty</a> smarty)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 132</div>
<h3 id="clear()">clear</h3>
```php
public  integer **clear**(<a href="../smarty/smarty.html">Smarty</a> _template, string resource_name, string cache_id, string compile_id, integer exp_time, <a href="../smarty/smarty.html">Smarty</a> smarty)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 228</div>
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 245</div>
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_cacheresource_file.php at line 257</div>
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

