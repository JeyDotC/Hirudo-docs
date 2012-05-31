
- - -

**Smarty\Smarty_Template_Cached**
<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 205</div>
#Class Smarty_Template_Cached#

**Smarty_Template_Cached**


- - -

<p class="signature">public  class **Smarty_Template_Cached**</p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Cache Data Container for Template Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>

- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#cache_id">$cache_id</a></p><p class="description">Template Cache Id (Smarty_Internal_Template::$cache_id)</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compile_id">$compile_id</a></p><p class="description">Template Compile Id (Smarty_Internal_Template::$compile_id)</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#content">$content</a></p><p class="description">Source Content</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#exists">$exists</a></p><p class="description">Source Existance</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#filepath">$filepath</a></p><p class="description">Source Filepath</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_cacheresource.html">Smarty_CacheResource</a></td>
<td class="description"><p class="name"><a href="#handler">$handler</a></p><p class="description">CacheResource Handler</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#is_locked">$is_locked</a></p><p class="description">flag that cache is locked by this instance</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#lock_id">$lock_id</a></p><p class="description">Id for cache locking</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#processed">$processed</a></p><p class="description">Cache was processed</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a></td>
<td class="description"><p class="name"><a href="#source">$source</a></p><p class="description">Source Object</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#timestamp">$timestamp</a></p><p class="description">Source Timestamp</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#valid">$valid</a></p><p class="description">Cache Is Valid</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">create Cached Object container</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#write">write</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)</p><p class="description">Write this cache object to handler</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 258</div>
<h3 id="cache_id">cache_id</h3>

public  string $cache_id = null
<div class="details">
<p>Template Cache Id (Smarty_Internal_Template::$cache_id)</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 252</div>
<h3 id="compile_id">compile_id</h3>

public  string $compile_id = null
<div class="details">
<p>Template Compile Id (Smarty_Internal_Template::$compile_id)</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 216</div>
<h3 id="content">content</h3>

public  string $content = null
<div class="details">
<p>Source Content</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 228</div>
<h3 id="exists">exists</h3>

public  boolean $exists = false
<div class="details">
<p>Source Existance</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 210</div>
<h3 id="filepath">filepath</h3>

public  string $filepath = false
<div class="details">
<p>Source Filepath</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 246</div>
<h3 id="handler">handler</h3>

public  <a href="../smarty/smarty_cacheresource.html">Smarty_CacheResource</a> $handler = null
<div class="details">
<p>CacheResource Handler</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 270</div>
<h3 id="is_locked">is_locked</h3>

public  bool $is_locked = false
<div class="details">
<p>flag that cache is locked by this instance</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 264</div>
<h3 id="lock_id">lock_id</h3>

public  string $lock_id = null
<div class="details">
<p>Id for cache locking</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 240</div>
<h3 id="processed">processed</h3>

public  boolean $processed = false
<div class="details">
<p>Cache was processed</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 276</div>
<h3 id="source">source</h3>

public  <a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> $source = null
<div class="details">
<p>Source Object</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 222</div>
<h3 id="timestamp">timestamp</h3>

public  integer $timestamp = false
<div class="details">
<p>Source Timestamp</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 234</div>
<h3 id="valid">valid</h3>

public  boolean $valid = false
<div class="details">
<p>Cache Is Valid</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 283</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)
```
<div class="details">
<p>create Cached Object container</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_cacheresource.php at line 362</div>
<h3 id="write()">write</h3>

public  boolean **write** (<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string content)<div class="details">
<p>Write this cache object to handler</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
<dd>content - content to cache</dd>
<dt>Returns:</dt>
<dd>success</dd>
</dl>
</div>

- - -

