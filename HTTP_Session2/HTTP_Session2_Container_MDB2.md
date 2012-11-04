

- - -

**HTTP_Session2\HTTP_Session2_Container_MDB2**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L54" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 54</a>

#Class HTTP_Session2_Container_MDB2#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md">HTTP_Session2_Container</a>
 &gt; **HTTP_Session2_Container_MDB2**




- - -

<p><strong>public  class</strong> <span>HTTP_Session2_Container_MDB2</span>
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
<dt>Uses:</dt>
<dd>MDB2</dd>
<dd>MDB2_Driver_</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container_MDB2.md#crc"> $crc</a>
                                </p><p class="description">Session data cache id</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>object DB</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container_MDB2.md#db"> $db</a>
                                </p><p class="description">MDB2 connection object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from HTTP_Session2\HTTP_Session2_Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#options">options</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
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
<td class="description"><p class="name"><a href="#connect">connect</a>(mixed dsn)</p><p class="description">Connect to database by using the given DSN string</p></td>
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
<td class="description"><p class="name"><a href="#gc">gc</a>(int maxlifetime)</p><p class="description">Garbage collectionCurrently supported are mysql, mysqli and pgsql.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#replicate">replicate</a>(string target, string id)</p><p class="description">Replicate session data to specified target</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from HTTP_Session2\HTTP_Session2_Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#parseoptions">parseOptions</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#set">set</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#setdefaults">setDefaults</a></td></tr></table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L69" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 69</a>

<h3 id="crc">crc</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $crc</span><span class='o'> = false</span>

<div class="details">
<p>Session data cache id</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L62" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 62</a>

<h3 id="db">db</h3>
<span class='k'>protected </span> <span class='nx'>object DB</span><span class='no'> $db</span><span class='o'> = null</span>

<div class="details">
<p>MDB2 connection object</p>
</div>

- - -

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L87" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 87</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>object</span> <span class='nf'>__construct</span> (array options)

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

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L100" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 100</a>

<h3 id="connect()">connect</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>connect</span> (mixed dsn)

<div class="details">
<p>Connect to database by using the given DSN string</p><dl>
<dt>Parameters:</dt>
<dd>dsn - DSN string or MDB2 object</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - An exception?!</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L134" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 134</a>

<h3 id="setDefaults()">setDefaults</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>setDefaults</span> ()

<div class="details">
<p>Set some default options</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L151" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 151</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L161" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 161</a>

<h3 id="close()">close</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>close</span> ()

<div class="details">
<p>Free resources</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L178" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 178</a>

<h3 id="read()">read</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>read</span> (string id)

<div class="details">
<p>Read session data</p><dl>
<dt>Parameters:</dt>
<dd>id - The Id!</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - An exception!?</dd>
<dt>Todo:</dt>
<dd>Get rid off sprintf()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L203" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 203</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L261" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 261</a>

<h3 id="destroy()">destroy</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>destroy</span> (string id)

<div class="details">
<p>Destroy session data</p><dl>
<dt>Parameters:</dt>
<dd>id - The id.</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - An exception containing MDB2 data.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L286" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 286</a>

<h3 id="gc()">gc</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>gc</span> (int maxlifetime)

<div class="details">
<p>Garbage collection</p><p>Currently supported are mysql, mysqli and pgsql.</p><dl>
<dt>Parameters:</dt>
<dd>maxlifetime - The session's maximum lifetime.</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - An exception that contains MDB2 data.</dd>
<dt>Todo:</dt>
<dd>Fix database-specific garbage collection.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/MDB2.php#L319" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\MDB2.php at line 319</a>

<h3 id="replicate()">replicate</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>replicate</span> (string target, string id)

<div class="details">
<p>Replicate session data to specified target</p><dl>
<dt>Parameters:</dt>
<dd>target - The target (table) to replicate to.</dd>
<dd>id - Id of record to replicate, if not specified current session id will be used</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - To carry any MDB2 related error out.</dd>
</dl>

</div>

- - -

