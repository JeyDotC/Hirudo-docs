

- - -

**HTTP_Session2\HTTP_Session2_Container_DB**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L87" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 87</a>

#Class HTTP_Session2_Container_DB#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md">HTTP_Session2_Container</a>
 &gt; **HTTP_Session2_Container_DB**




- - -

<p><strong>public  class</strong> <span>HTTP_Session2_Container_DB</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md">HTTP_Session2_Container</a>

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


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from HTTP_Session2\HTTP_Session2_Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#options">options</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
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
<td><span class='k'>protected </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#connect">connect</a>(string dsn)</p><p class="description">Connect to database by using the given DSN string</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setdefaults">setDefaults</a>()</p><p class="description">Set some default options</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#open">open</a>(string save_path, string session_name)</p><p class="description">Establish connection to a database</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#close">close</a>()</p><p class="description">Free resources</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#read">read</a>(string id)</p><p class="description">Read session data</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#write">write</a>(string id, string data)</p><p class="description">Write session data</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#destroy">destroy</a>(string id)</p><p class="description">Destroy session data</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#gc">gc</a>(int maxlifetime)</p><p class="description">Garbage collection</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#replicate">replicate</a>(string target, string id)</p><p class="description">Replicate session data to specified target</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from HTTP_Session2\HTTP_Session2_Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#parseoptions">parseOptions</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#set">set</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#setdefaults">setDefaults</a></td></tr></table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L120" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 120</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (array options)

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

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L133" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 133</a>

<h3 id="connect()">connect</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>connect</span> (string dsn)

<div class="details">
<p>Connect to database by using the given DSN string</p><dl>
<dt>Parameters:</dt>
<dd>dsn - DSN string</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - An exception?!</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L155" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 155</a>

<h3 id="setDefaults()">setDefaults</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>setDefaults</span> ()

<div class="details">
<p>Set some default options</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L172" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 172</a>

<h3 id="open()">open</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>open</span> (string save_path, string session_name)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L182" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 182</a>

<h3 id="close()">close</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>close</span> ()

<div class="details">
<p>Free resources</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L195" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 195</a>

<h3 id="read()">read</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>read</span> (string id)

<div class="details">
<p>Read session data</p><dl>
<dt>Parameters:</dt>
<dd>id - The Id!</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - An exception!?</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L220" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 220</a>

<h3 id="write()">write</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>write</span> (string id, string data)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L277" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 277</a>

<h3 id="destroy()">destroy</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>destroy</span> (string id)

<div class="details">
<p>Destroy session data</p><dl>
<dt>Parameters:</dt>
<dd>id - The id.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L299" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 299</a>

<h3 id="gc()">gc</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>gc</span> (int maxlifetime)

<div class="details">
<p>Garbage collection</p><dl>
<dt>Parameters:</dt>
<dd>maxlifetime - The session's maximum lifetime.</dd>
<dt>Todo:</dt>
<dd>Find out why the DB is not used for garbage collection.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/DB.php#L343" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\DB.php at line 343</a>

<h3 id="replicate()">replicate</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>replicate</span> (string target, string id)

<div class="details">
<p>Replicate session data to specified target</p><dl>
<dt>Parameters:</dt>
<dd>target - Target to replicate to</dd>
<dd>id - Id of record to replicate, if not specified current session id will be used</dd>
</dl>

</div>

- - -

