

- - -

**HTTP_Session2\HTTP_Session2_Container_Memcache**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L38" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 38</a>

#Class HTTP_Session2_Container_Memcache#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md">HTTP_Session2_Container</a>
 &gt; **HTTP_Session2_Container_Memcache**




- - -

<p><strong>public  class</strong> <span>HTTP_Session2_Container_Memcache</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md">HTTP_Session2_Container</a>

</p>

<div class="comment" id="overview_description"><p>Memcache container for session data</p></div>

<dl>
<dt>Category:</dt>
<dd>HTTP</dd>
<dt>Author:</dt>
<dd>Chad Wagner <chad.wagner@gmail.com></dd>
<dd>Torsten Roehr <torsten.roehr@gmx.de></dd>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/bsd-license.php The BSD License</dd>
<dt>Version:</dt>
<dd>Release: @package_version@</dd>
<dt>See Also:</dt>
<dd><code><a href="http://pear.php.net/package/HTTP_Session2">http://pear.php.net/package/HTTP_Session2</a></code></dd>
<dt>Since:</dt>
<dd>0.6.2</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>object Memcache</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container_Memcache.md#mc"> $mc</a>
                                </p><p class="description">Memcache connection object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from HTTP_Session2\HTTP_Session2_Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#options">options</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array options)</p><p class="description">Constructor method$options is an array with the options.
The options are:

'memcache' - Memcache object
'prefix'   - Key prefix, default is 'sessiondata:'

</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#connect">connect</a>(Memcache mc)</p><p class="description">Connect using the given Memcache object.</p></td>
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
<td class="description"><p class="name"><a href="#write">write</a>(string id, mixed data)</p><p class="description">Write session data</p></td>
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

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L45" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 45</a>

<h3 id="mc">mc</h3>
<span class='k'>protected </span> <span class='nx'>object Memcache</span><span class='no'> $mc</span><span class='o'> = null</span>

<div class="details">
<p>Memcache connection object</p>
</div>

- - -

##Constructor Detail##


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L61" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 61</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>object</span> <span class='nf'>__construct</span> (array options)

<div class="details">
<p>Constructor method</p><p>$options is an array with the options.<br>
The options are:</p>
<ul>
<li>'memcache' - Memcache object
<li>'prefix'   - Key prefix, default is 'sessiondata:'</li>
</ul>
<p></p><dl>
<dt>Parameters:</dt>
<dd>options - Options</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L74" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 74</a>

<h3 id="connect()">connect</h3>
<span class='k'>protected </span> <span class='nx'>boolean</span> <span class='nf'>connect</span> (Memcache mc)

<div class="details">
<p>Connect using the given Memcache object.</p><dl>
<dt>Parameters:</dt>
<dd>mc - A Memcache instance.</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L91" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 91</a>

<h3 id="setDefaults()">setDefaults</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>setDefaults</span> ()

<div class="details">
<p>Set some default options</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L105" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 105</a>

<h3 id="open()">open</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>open</span> (string save_path, string session_name)

<div class="details">
<p>Establish connection to a database</p><dl>
<dt>Parameters:</dt>
<dd>save_path - Save path</dd>
<dd>session_name - Session name</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L115" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 115</a>

<h3 id="close()">close</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>close</span> ()

<div class="details">
<p>Free resources</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L126" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 126</a>

<h3 id="read()">read</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>read</span> (string id)

<div class="details">
<p>Read session data</p><dl>
<dt>Parameters:</dt>
<dd>id - Session id</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L139" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 139</a>

<h3 id="write()">write</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>write</span> (string id, mixed data)

<div class="details">
<p>Write session data</p><dl>
<dt>Parameters:</dt>
<dd>id - Session id</dd>
<dd>data - Session data</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L156" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 156</a>

<h3 id="destroy()">destroy</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>destroy</span> (string id)

<div class="details">
<p>Destroy session data</p><dl>
<dt>Parameters:</dt>
<dd>id - Session id</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L169" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 169</a>

<h3 id="gc()">gc</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>gc</span> (int maxlifetime)

<div class="details">
<p>Garbage collection</p><dl>
<dt>Parameters:</dt>
<dd>maxlifetime - Maximum lifetime</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Memcache.php#L183" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Memcache.php at line 183</a>

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

