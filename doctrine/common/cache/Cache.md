
- - -

**Doctrine\Common\Cache\Cache**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\Cache.php at line 36</div>
#Interface Cache#

**Cache**


- - -

<p class="signature">public  interface **Cache**</p>

<div class="comment" id="overview_description"><p>Interface for cache drivers.</p></div>

<dl>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/lgpl-license.php LGPL</dd>
<dt>See Also:</dt>
<dd><code>www.doctrine-project.org</code></dd>
<dt>Since:</dt>
<dd>2.0</dd>
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
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#delete">delete</a>(string id)</p><p class="description">Deletes a cache entry.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#getstats">getStats</a>()</p><p class="description">Retrieves cached information from data storeThe server's statistics array has the following values:- <b>hits</b>
Number of keys that have been requested and found present.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\Cache.php at line 46</div>
<h3 id="delete()">delete</h3>

public  boolean **delete** (string id)<div class="details">
<p>Deletes a cache entry.</p><dl>
<dt>Parameters:</dt>
<dd>id - cache id</dd>
<dt>Returns:</dt>
<dd>TRUE if the cache entry was successfully deleted, FALSE otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Cache\Cache.php at line 71</div>
<h3 id="getStats()">getStats</h3>

public  void **getStats** ()<div class="details">
<p>Retrieves cached information from data store</p><p>The server's statistics array has the following values:</p><p>- <b>hits</b>
Number of keys that have been requested and found present.</p><p>- <b>misses</b>
Number of items that have been requested and not found.</p><p>- <b>uptime</b>
Time that the server is running.</p><p>- <b>memory_usage</b>
Memory used by this server to store items.</p><p>- <b>memory_available</b>
Memory allowed to use for storage.</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
</dl>
</div>

- - -

