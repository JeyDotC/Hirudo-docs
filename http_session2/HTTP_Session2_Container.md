- - -

**HTTP_Session2\HTTP_Session2_Container**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php.md#line64" class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 64</a>

# Class HTTP_Session2_Container #

<pre class="tree">** HTTP_Session2_Container **\n</pre>

<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container_db.html">HTTP_Session2_Container_DB</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container_mdb2.html">HTTP_Session2_Container_MDB2</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container_memcache.html">HTTP_Session2_Container_Memcache</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **HTTP_Session2_Container**</p>

<div class="comment" id="overview_description"><p>Container class for storing session data data</p></div>

<dl>
<dt>Category:</dt>
<dd>HTTP</dd>
<dt>Author:</dt>
<dd>Alexander Radivaniovich <info@wwwlab.net></dd>
<dd>Tony Bibbs <tony@geeklog.net></dd>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/bsd-license.php The BSD License</dd>
<dt>Version:</dt>
<dd>Release: @package_version@</dd>
<dt>See Also:</dt>
<dd><code><a href="http://pear.php.net/package/HTTP_Session2">http://pear.php.net/package/HTTP_Session2</a></code></dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#options">$options</a></p><p class="description">Additional options for the container object</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(array options)</p><p class="description">Constrtuctor method</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#setDefaults()">setDefaults</a>()</p><p class="description">Set some default options</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#parseOptions()">parseOptions</a>(array options)</p><p class="description">Parse options passed to the container class</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#set()">set</a>()</p><p class="description">Set session save handler</p></td>
</tr>
</table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php.md#line71" class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 71</a>

<h3 id="options">options</h3>
```php
protected  array **$options** = array()```
<div class="details">
<p>Additional options for the container object</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php.md#line80" class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 80</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(array options)```
<div class="details">
<p>Constrtuctor method</p><dl>
<dt>Parameters:</dt>
<dd>options - Additional options for the container object</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php.md#line103" class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 103</a>

<h3 id="setDefaults()">setDefaults</h3>
```php
protected  void **setDefaults**()```
<div class="details">
<p>Set some default options</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php.md#line114" class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 114</a>

<h3 id="parseOptions()">parseOptions</h3>
```php
protected  void **parseOptions**(array options)```
<div class="details">
<p>Parse options passed to the container class</p><dl>
<dt>Parameters:</dt>
<dd>options - Options</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php.md#line128" class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 128</a>

<h3 id="set()">set</h3>
```php
public  void **set**()```
<div class="details">
<p>Set session save handler</p></div>

- - -

