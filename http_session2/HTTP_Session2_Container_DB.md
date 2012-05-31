- - -

**HTTP_Session2\HTTP_Session2_Container_DB**
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 87</div>
#Class HTTP_Session2_Container_DB#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container.html">HTTP_Session2_Container</a>
    ***HTTP_Session2_Container_DB**


- - -

<p class="signature">public  class **HTTP_Session2_Container_DB**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container.html">HTTP_Session2_Container</a>

</p>

<div class="comment" id="overview_description"><p>Database container for session data</p><p>Create the following table to store session data
<code>
CREATE TABLE `sessiondata` (
`id` CHAR(32) NOT NULL,
`expiry` INT UNSIGNED NOT NULL DEFAULT 0,
`data` TEXT NOT NULL,
PRIMARY KEY (`id`)
);
</code></p></div>

<dl>
<dt>Category:</dt>
<dd>HTTP</dd>
<dt>Author:</dt>
<dd>Alexander Radivanovich <info@wwwlab.net></dd>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/bsd-license.php The BSD License</dd>
<dt>Version:</dt>
<dd>Release: @package_version@</dd>
<dt>See Also:</dt>
<dd><code><a href="http://pear.php.net/package/HTTP_Session2">http://pear.php.net/package/HTTP_Session2</a></code></dd>
<dt>Deprecated:</dt>
<dd>This driver/container is deprecated from 0.9.0</dd>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from HTTP_Session2\HTTP_Session2_Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container.html#options">options</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array options)</p><p class="description">Constrtuctor method$options is an array with the options.
The options are:

'dsn' - The DSN string
'table' - Table with session data, default is 'sessiondata'
'autooptimize' - Boolean, 'true' to optimize
the table on garbage collection, default is 'false'.

</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">protected  boolean</td>
<td class="description"><p class="name"><a href="#connect">connect</a>(string dsn)</p><p class="description">Connect to database by using the given DSN string</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#setDefaults">setDefaults</a>()</p><p class="description">Set some default options</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#open">open</a>(string save_path, string session_name)</p><p class="description">Establish connection to a database</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#close">close</a>()</p><p class="description">Free resources</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#read">read</a>(string id)</p><p class="description">Read session data</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#write">write</a>(string id, string data)</p><p class="description">Write session data</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#destroy">destroy</a>(string id)</p><p class="description">Destroy session data</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#gc">gc</a>(int maxlifetime)</p><p class="description">Garbage collection</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#replicate">replicate</a>(string target, string id)</p><p class="description">Replicate session data to specified target</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from HTTP_Session2\HTTP_Session2_Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container.html#parseOptions()">parseOptions</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container.html#set()">set</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container.html#setDefaults()">setDefaults</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 120</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(array options)```
<div class="details">
<p>Constrtuctor method</p><p>$options is an array with the options.<br>
The options are:</p>
<ul>
<li>'dsn' - The DSN string</li>
<li>'table' - Table with session data, default is 'sessiondata'</li>
<li>'autooptimize' - Boolean, 'true' to optimize
the table on garbage collection, default is 'false'.</li>
</ul>
<p></p><dl>
<dt>Parameters:</dt>
<dd>options - The options</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 133</div>
<h3 id="connect()">connect</h3>
```php
protected  boolean **connect**(string dsn)```
<div class="details">
<p>Connect to database by using the given DSN string</p><dl>
<dt>Parameters:</dt>
<dd>dsn - DSN string</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - An exception?!</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 155</div>
<h3 id="setDefaults()">setDefaults</h3>
```php
protected  void **setDefaults**()```
<div class="details">
<p>Set some default options</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 172</div>
<h3 id="open()">open</h3>
```php
public  boolean **open**(string save_path, string session_name)```
<div class="details">
<p>Establish connection to a database</p><dl>
<dt>Parameters:</dt>
<dd>save_path - The path to save/write sessions.</dd>
<dd>session_name - The session name.</dd>
<dt>Uses:</dt>
<dd>self::connect();</dd>
<dd>self::$options</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 182</div>
<h3 id="close()">close</h3>
```php
public  boolean **close**()```
<div class="details">
<p>Free resources</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 195</div>
<h3 id="read()">read</h3>
```php
public  mixed **read**(string id)```
<div class="details">
<p>Read session data</p><dl>
<dt>Parameters:</dt>
<dd>id - The Id!</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - An exception!?</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 220</div>
<h3 id="write()">write</h3>
```php
public  boolean **write**(string id, string data)```
<div class="details">
<p>Write session data</p><dl>
<dt>Parameters:</dt>
<dd>id - The id.</dd>
<dd>data - The data.</dd>
<dt>Todo:</dt>
<dd>Remove sprintf(), they are expensive.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 277</div>
<h3 id="destroy()">destroy</h3>
```php
public  boolean **destroy**(string id)```
<div class="details">
<p>Destroy session data</p><dl>
<dt>Parameters:</dt>
<dd>id - The id.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 299</div>
<h3 id="gc()">gc</h3>
```php
public  boolean **gc**(int maxlifetime)```
<div class="details">
<p>Garbage collection</p><dl>
<dt>Parameters:</dt>
<dd>maxlifetime - The session's maximum lifetime.</dd>
<dt>Todo:</dt>
<dd>Find out why the DB is not used for garbage collection.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 343</div>
<h3 id="replicate()">replicate</h3>
```php
public  boolean **replicate**(string target, string id)```
<div class="details">
<p>Replicate session data to specified target</p><dl>
<dt>Parameters:</dt>
<dd>target - Target to replicate to</dd>
<dd>id - Id of record to replicate, if not specified current session id will be used</dd>
</dl>
</div>

- - -

