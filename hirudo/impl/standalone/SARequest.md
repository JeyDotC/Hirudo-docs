
- - -

**Hirudo\Impl\StandAlone\SARequest**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L35 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 35</a>

#Class SARequest#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html">Request</a>
    * **SARequest**




- - -

<p class="signature">public  class **SARequest**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html">Request</a>

</p>

<div class="comment" id="overview_description"><p>Description of SARequest</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Export(id="request",:</dt>
<dd>factory="instance")</dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/hirudo/impl/standalone/sarequest.html>SARequest</a></span></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string name, mixed default)</p><p class="description">Retrieves a value from the GET parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#post">post</a>(string name, mixed default)</p><p class="description">Retrieves a value from the POST parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#file">file</a>(string name, mixed default)</p><p class="description">Retrieves a value from the FILE parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#cookie">cookie</a>(string name, mixed default)</p><p class="description">Retrieves a value from the COOKIE parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#env">env</a>(string name, mixed default)</p><p class="description">Retrieves a value from the ENV parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#server">server</a>(string name, mixed default)</p><p class="description">Retrieves a value from the SERVER parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#geturi">getURI</a>()</p><p class="description">Gets the current URI as a string.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#submitted">submitted</a>()</p><p class="description">Determines if there is any data in the $_POST array.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/modulecall.html>ModuleCall</a></span></td>
<td class="description"><p class="name"><a href="#buildmodulecall">buildModuleCall</a>()</p><p class="description">Creates a ModuleCall from request parameters, generally from the URL,
the way this done depends on how this class interprets the URLs.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\Request</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#bind()">bind</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#buildModuleCall()">buildModuleCall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#cookie()">cookie</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#env()">env</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#file()">file</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#get()">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#getAttribute()">getAttribute</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#getSession()">getSession</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#getURI()">getURI</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#getVar()">getVar</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#method()">method</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#post()">post</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#removeAttribute()">removeAttribute</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#server()">server</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#setAttribute()">setAttribute</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#setSession()">setSession</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#submitted()">submitted</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L47 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 47</a>

<h3 id="instance()">instance</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/hirudo/impl/standalone/sarequest.html>SARequest</a></span> <span class='nf'>instance</span> ()

<div class="details">
<p></p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L55 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 55</a>

<h3 id="get()">get</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>get</span> (string name, mixed default)

<div class="details">
<p>Retrieves a value from the GET parameters.</p><dl>
<dt>Parameters:</dt>
<dd>name - The GET index.</dd>
<dd>default - A default value that will be returned if GET doesn't have a value for the given index.</dd>
<dt>Returns:</dt>
<dd>The value corresponding to the $name index in the GET array.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L59 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 59</a>

<h3 id="post()">post</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>post</span> (string name, mixed default)

<div class="details">
<p>Retrieves a value from the POST parameters.</p><dl>
<dt>Parameters:</dt>
<dd>name - The POST index.</dd>
<dd>default - A default value that will be returned if POST doesn't have a value for the given index.</dd>
<dt>Returns:</dt>
<dd>The value corresponding to the $name index in the POST array.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L63 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 63</a>

<h3 id="file()">file</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>file</span> (string name, mixed default)

<div class="details">
<p>Retrieves a value from the FILE parameters.</p><dl>
<dt>Parameters:</dt>
<dd>name - The FILE index.</dd>
<dd>default - A default value that will be returned if FILE doesn't have a value for the given index.</dd>
<dt>Returns:</dt>
<dd>The value corresponding to the $name index in the FILE array.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L67 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 67</a>

<h3 id="cookie()">cookie</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>cookie</span> (string name, mixed default)

<div class="details">
<p>Retrieves a value from the COOKIE parameters.</p><dl>
<dt>Parameters:</dt>
<dd>name - The COOKIE index.</dd>
<dd>default - A default value that will be returned if COOKIE doesn't have a value for the given index.</dd>
<dt>Returns:</dt>
<dd>The value corresponding to the $name index in the COOKIE array.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L71 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 71</a>

<h3 id="env()">env</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>env</span> (string name, mixed default)

<div class="details">
<p>Retrieves a value from the ENV parameters.</p><dl>
<dt>Parameters:</dt>
<dd>name - The ENV index.</dd>
<dd>default - A default value that will be returned if ENV doesn't have a value for the given index.</dd>
<dt>Returns:</dt>
<dd>The value corresponding to the $name index in the ENV array.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L75 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 75</a>

<h3 id="server()">server</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>server</span> (string name, mixed default)

<div class="details">
<p>Retrieves a value from the SERVER parameters.</p><dl>
<dt>Parameters:</dt>
<dd>name - The SERVER index.</dd>
<dd>default - A default value that will be returned if SERVER doesn't have a value for the given index.</dd>
<dt>Returns:</dt>
<dd>The value corresponding to the $name index in the SERVER array.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L79 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 79</a>

<h3 id="getURI()">getURI</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getURI</span> ()

<div class="details">
<p>Gets the current URI as a string.</p><dl>
<dt>Returns:</dt>
<dd>the current URI.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L84 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 84</a>

<h3 id="submitted()">submitted</h3>
<span class='k'></span> <span class='nx'>bool</span> <span class='nf'>submitted</span> ()

<div class="details">
<p>Determines if there is any data in the $_POST array.</p><dl>
<dt>Deprecated:</dt>
<dd>This method looks to be useless</dd>
<dt>Returns:</dt>
<dd><code>true</code> if there is POST data.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/hirudo/impl/standalone/sarequest.php#L88 class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 88</a>

<h3 id="buildModuleCall()">buildModuleCall</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/modulecall.html>ModuleCall</a></span> <span class='nf'>buildModuleCall</span> ()

<div class="details">
<p>Creates a ModuleCall from request parameters, generally from the URL,
the way this done depends on how this class interprets the URLs.</p><dl>
<dt>Returns:</dt>
<dd>An instance of ModuleCall based on this class interpretation of the URL</dd>
</dl>
</div>

- - -

