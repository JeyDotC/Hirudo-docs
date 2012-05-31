- - -

**Smarty\Smarty_CacheResource**
<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 16</div>
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
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#resources">$resources</a></p><p class="description">cache for Smarty_CacheResource instances</p></td>
</tr>
<tr>
<td class="type">protected static  array</td>
<td class="description"><p class="name"><a href="#sysplugins">$sysplugins</a></p><p class="description">resource types provided by the core</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">abstract  void</td>
<td class="description"><p class="name"><a href="#populate">populate</a>(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">populate Cached Object with meta data from Resource</p></td>
</tr>
<tr>
<td class="type">abstract  void</td>
<td class="description"><p class="name"><a href="#populateTimestamp">populateTimestamp</a>(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">populate Cached Object with timestamp and exists from Resource</p></td>
</tr>
<tr>
<td class="type">abstract  booelan</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p><p class="description">Read the cached template and process header</p></td>
</tr>
<tr>
<td class="type">abstract  boolean</td>
<td class="description"><p class="name"><a href="#writeCachedContent">writeCachedContent</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write the rendered template output to cache</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getCachedContent">getCachedContent</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Return cached content</p></td>
</tr>
<tr>
<td class="type">abstract  integer</td>
<td class="description"><p class="name"><a href="#clearAll">clearAll</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, integer exp_time)</p><p class="description">Empty cache</p></td>
</tr>
<tr>
<td class="type">abstract  integer</td>
<td class="description"><p class="name"><a href="#clear">clear</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)</p><p class="description">Empty cache for a specific template</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#locked">locked</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#hasLock">hasLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#acquireLock">acquireLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#releaseLock">releaseLock</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)</p></td>
</tr>
<tr>
<td class="type">static  <a href="../smarty/smarty_cacheresource.html">Smarty_CacheResource</a></td>
<td class="description"><p class="name"><a href="#load">load</a>(<a href="../smarty/smarty.html">Smarty</a> smarty, string type)</p><p class="description">Load Cache Resource Handler</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#invalidLoadedCache">invalidLoadedCache</a>(<a href="../smarty/smarty.html">Smarty</a> smarty)</p><p class="description">Invalid Loaded Cache Files</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 21</div>
<h3 id="resources">resources</h3>

```php
public static  array$resources = array()
```
<div class="details">
<p>cache for Smarty_CacheResource instances</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 27</div>
<h3 id="sysplugins">sysplugins</h3>

```php
protected static  array$sysplugins = array(...)
```
<div class="details">
<p>resource types provided by the core</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 36</div>
<h3 id="populate()">populate</h3>

```php
public abstract  void **populate**(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)
```
<div class="details">
<p>populate Cached Object with meta data from Resource</p><dl>
<dt>Parameters:</dt>
<dd>cached - cached object</dd>
<dd>_template - template object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 44</div>
<h3 id="populateTimestamp()">populateTimestamp</h3>

```php
public abstract  void **populateTimestamp**(<a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> source, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)
```
<div class="details">
<p>populate Cached Object with timestamp and exists from Resource</p><dl>
<dt>Parameters:</dt>
<dd>source - cached object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 53</div>
<h3 id="process()">process</h3>

```php
public abstract  booelan **process**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)
```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 62</div>
<h3 id="writeCachedContent()">writeCachedContent</h3>

```php
public abstract  boolean **writeCachedContent**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)
```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 70</div>
<h3 id="getCachedContent()">getCachedContent</h3>

```php
public  void **getCachedContent**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)
```
<div class="details">
<p>Return cached content</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>content - content of cache</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 87</div>
<h3 id="clearAll()">clearAll</h3>

```php
public abstract  integer **clearAll**(<a href="../smarty/smarty.html">Smarty</a> smarty, integer exp_time)
```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 99</div>
<h3 id="clear()">clear</h3>

```php
public abstract  integer **clear**(<a href="../smarty/smarty.html">Smarty</a> smarty, string resource_name, string cache_id, string compile_id, integer exp_time)
```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 102</div>
<h3 id="locked()">locked</h3>

```php
public  void **locked**(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 118</div>
<h3 id="hasLock()">hasLock</h3>

```php
public  void **hasLock**(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 124</div>
<h3 id="acquireLock()">acquireLock</h3>

```php
public  void **acquireLock**(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 130</div>
<h3 id="releaseLock()">releaseLock</h3>

```php
public  void **releaseLock**(<a href="../smarty/smarty.html">Smarty</a> smarty, <a href="../smarty/smarty_template_cached.html">Smarty_Template_Cached</a> cached)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 144</div>
<h3 id="load()">load</h3>

```php
public static  <a href="../smarty/smarty_cacheresource.html">Smarty_CacheResource</a> **load**(<a href="../smarty/smarty.html">Smarty</a> smarty, string type)
```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 185</div>
<h3 id="invalidLoadedCache()">invalidLoadedCache</h3>

```php
public static  void **invalidLoadedCache**(<a href="../smarty/smarty.html">Smarty</a> smarty)
```
<div class="details">
<p>Invalid Loaded Cache Files</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty object</dd>
</dl>
</div>

- - -

