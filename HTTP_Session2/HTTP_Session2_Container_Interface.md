

- - -

**HTTP_Session2\HTTP_Session2_Container_Interface**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Interface.php#L57" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Interface.php at line 57</a>

#Interface HTTP_Session2_Container_Interface#

**HTTP_Session2_Container_Interface**




- - -

<p><strong>public  interface</strong> <span>HTTP_Session2_Container_Interface</span></p>

<div class="comment" id="overview_description"><p>Container class for storing session data data</p></div>

<dl>
<dt>Category:</dt>
<dd>HTTP</dd>
<dt>Author:</dt>
<dd>Alexander Radivaniovich <info@wwwlab.net></dd>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/bsd-license.php The BSD License</dd>
<dt>Version:</dt>
<dd>Release: @package_version@</dd>
<dt>See Also:</dt>
<dd><code><a href="http://pear.php.net/package/HTTP_Session2">http://pear.php.net/package/HTTP_Session2</a></code></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#open">open</a>(string save_path, string session_name)</p><p class="description">open</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#close">close</a>()</p><p class="description">close</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#read">read</a>(string id)</p><p class="description">read</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#write">write</a>(string id, string data)</p><p class="description">write</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#destroy">destroy</a>(string id)</p><p class="description">destroy</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#gc">gc</a>(int maxlifetime)</p><p class="description">gc</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#replicate">replicate</a>(string target, string id)</p><p class="description">Replicate session data to specified target</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Interface.php#L67" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Interface.php at line 67</a>

<h3 id="open()">open</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>open</span> (string save_path, string session_name)

<div class="details">
<p>open</p><dl>
<dt>Parameters:</dt>
<dd>save_path - Path to save sessions in.</dd>
<dd>session_name - Name of the session.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Interface.php#L74" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Interface.php at line 74</a>

<h3 id="close()">close</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>close</span> ()

<div class="details">
<p>close</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Interface.php#L83" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Interface.php at line 83</a>

<h3 id="read()">read</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>read</span> (string id)

<div class="details">
<p>read</p><dl>
<dt>Parameters:</dt>
<dd>id - The session ID.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Interface.php#L93" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Interface.php at line 93</a>

<h3 id="write()">write</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>write</span> (string id, string data)

<div class="details">
<p>write</p><dl>
<dt>Parameters:</dt>
<dd>id - The session ID.</dd>
<dd>data - The data to save/write.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Interface.php#L102" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Interface.php at line 102</a>

<h3 id="destroy()">destroy</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>destroy</span> (string id)

<div class="details">
<p>destroy</p><dl>
<dt>Parameters:</dt>
<dd>id - The session ID.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Interface.php#L111" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Interface.php at line 111</a>

<h3 id="gc()">gc</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>gc</span> (int maxlifetime)

<div class="details">
<p>gc</p><dl>
<dt>Parameters:</dt>
<dd>maxlifetime - The session's maximum lifetime.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container/Interface.php#L122" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container\Interface.php at line 122</a>

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

