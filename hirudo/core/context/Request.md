

- - -

**Hirudo\Core\Context\Request**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L33" >framework\hirudo\Hirudo\Core\Context\Request.php at line 33</a>

#Class Request#

**Request**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/joomla/joomlarequest.md">Hirudo\Impl\Joomla\JoomlaRequest</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/standalone/sarequest.md">Hirudo\Impl\StandAlone\SARequest</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>Request</span></p>

<div class="comment" id="overview_description"><p>This object represents the current request.</p></div>

<dl>
<dt>Author:</dt>
<dd>Virtualidad</dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setattribute">setAttribute</a>(string key, mixed value)</p><p class="description">Stores a value in memory so it can be accesed "gloablly".</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getattribute">getAttribute</a>(string key, mixed default)</p><p class="description">Gets an in-memory value from the current request which is stored with
the setAttribute() method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#removeattribute">removeAttribute</a>(string key)</p><p class="description">Removes an in-memory stored value from this request.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#bind">bind</a>(type object, type bindings)</p><p class="description">TODO: #desition Remove this method?</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string name, mixed default)</p><p class="description">Retrieves a value from the GET parameters.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#post">post</a>(string name, mixed default)</p><p class="description">Retrieves a value from the POST parameters.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#file">file</a>(string name, mixed default)</p><p class="description">Retrieves a value from the FILE parameters.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#cookie">cookie</a>(string name, mixed default)</p><p class="description">Retrieves a value from the COOKIE parameters.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#env">env</a>(string name, mixed default)</p><p class="description">Retrieves a value from the ENV parameters.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#server">server</a>(string name, mixed default)</p><p class="description">Retrieves a value from the SERVER parameters.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#geturi">getURI</a>()</p><p class="description">Gets the current URI as a string.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#method">method</a>()</p><p class="description">Gets the current HTTP method (GET, POST, PUT, DELETE).</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/modulecall.html>ModuleCall</a></span></td>
<td class="description"><p class="name"><a href="#buildmodulecall">buildModuleCall</a>()</p><p class="description">Creates a ModuleCall from request parameters, generally from the URL,
the way this done depends on how this class interprets the URLs.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#submitted">submitted</a>()</p><p class="description">Determines if there is any data in the $_POST array.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getvar">getVar</a>(array collection, string index, mixed default)</p><p class="description">An utility method that simply returns tha value associated to the given
index or the given default value if there is no value associated to the
index.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Session</span></td>
<td class="description"><p class="name"><a href="#getsession">getSession</a>()</p><p class="description">Gets the current session object.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setsession">setSession</a>(Session session)</p><p class="description"></p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L49" >framework\hirudo\Hirudo\Core\Context\Request.php at line 49</a>

<h3 id="setAttribute()">setAttribute</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setAttribute</span> (string key, mixed value)

<div class="details">
<p>Stores a value in memory so it can be accesed "gloablly".</p><dl>
<dt>Parameters:</dt>
<dd>key - A key to identify the value.</dd>
<dd>value - The value.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L62" >framework\hirudo\Hirudo\Core\Context\Request.php at line 62</a>

<h3 id="getAttribute()">getAttribute</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getAttribute</span> (string key, mixed default)

<div class="details">
<p>Gets an in-memory value from the current request which is stored with
the setAttribute() method.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key that identifies the stored value.</dd>
<dd>default - A default value which is returned if there is no value associated to the given key.</dd>
<dt>Returns:</dt>
<dd>The value associated to the key.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L72" >framework\hirudo\Hirudo\Core\Context\Request.php at line 72</a>

<h3 id="removeAttribute()">removeAttribute</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>removeAttribute</span> (string key)

<div class="details">
<p>Removes an in-memory stored value from this request.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key corresponding to the value to be removed.</dd>
<dt>Returns:</dt>
<dd>The value that has been removed.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L88" >framework\hirudo\Hirudo\Core\Context\Request.php at line 88</a>

<h3 id="bind()">bind</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>bind</span> (type object, type bindings)

<div class="details">
<p>TODO: #desition Remove this method?</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L100" >framework\hirudo\Hirudo\Core\Context\Request.php at line 100</a>

<h3 id="get()">get</h3>
<span class='k'>abstract </span> <span class='nx'>mixed</span> <span class='nf'>get</span> (string name, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L109" >framework\hirudo\Hirudo\Core\Context\Request.php at line 109</a>

<h3 id="post()">post</h3>
<span class='k'>abstract </span> <span class='nx'>mixed</span> <span class='nf'>post</span> (string name, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L118" >framework\hirudo\Hirudo\Core\Context\Request.php at line 118</a>

<h3 id="file()">file</h3>
<span class='k'>abstract </span> <span class='nx'>mixed</span> <span class='nf'>file</span> (string name, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L127" >framework\hirudo\Hirudo\Core\Context\Request.php at line 127</a>

<h3 id="cookie()">cookie</h3>
<span class='k'>abstract </span> <span class='nx'>mixed</span> <span class='nf'>cookie</span> (string name, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L136" >framework\hirudo\Hirudo\Core\Context\Request.php at line 136</a>

<h3 id="env()">env</h3>
<span class='k'>abstract </span> <span class='nx'>mixed</span> <span class='nf'>env</span> (string name, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L145" >framework\hirudo\Hirudo\Core\Context\Request.php at line 145</a>

<h3 id="server()">server</h3>
<span class='k'>abstract </span> <span class='nx'>mixed</span> <span class='nf'>server</span> (string name, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L152" >framework\hirudo\Hirudo\Core\Context\Request.php at line 152</a>

<h3 id="getURI()">getURI</h3>
<span class='k'>abstract </span> <span class='nx'>string</span> <span class='nf'>getURI</span> ()

<div class="details">
<p>Gets the current URI as a string.</p><dl>
<dt>Returns:</dt>
<dd>the current URI.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L159" >framework\hirudo\Hirudo\Core\Context\Request.php at line 159</a>

<h3 id="method()">method</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>method</span> ()

<div class="details">
<p>Gets the current HTTP method (GET, POST, PUT, DELETE).</p><dl>
<dt>Returns:</dt>
<dd>Returns a string with the current HTTP method.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L169" >framework\hirudo\Hirudo\Core\Context\Request.php at line 169</a>

<h3 id="buildModuleCall()">buildModuleCall</h3>
<span class='k'>abstract </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/modulecall.html>ModuleCall</a></span> <span class='nf'>buildModuleCall</span> ()

<div class="details">
<p>Creates a ModuleCall from request parameters, generally from the URL,
the way this done depends on how this class interprets the URLs.</p><dl>
<dt>Returns:</dt>
<dd>An instance of ModuleCall based on this class interpretation of the URL</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L177" >framework\hirudo\Hirudo\Core\Context\Request.php at line 177</a>

<h3 id="submitted()">submitted</h3>
<span class='k'>abstract </span> <span class='nx'>bool</span> <span class='nf'>submitted</span> ()

<div class="details">
<p>Determines if there is any data in the $_POST array.</p><dl>
<dt>Deprecated:</dt>
<dd>This method looks to be useless</dd>
<dt>Returns:</dt>
<dd><code>true</code> if there is POST data.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L190" >framework\hirudo\Hirudo\Core\Context\Request.php at line 190</a>

<h3 id="getVar()">getVar</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span> <span class='nf'>getVar</span> (array collection, string index, mixed default)

<div class="details">
<p>An utility method that simply returns tha value associated to the given
index or the given default value if there is no value associated to the
index.</p><dl>
<dt>Parameters:</dt>
<dd>collection - The conllection from which the value will be requested.</dd>
<dd>index - The index for the requested value.</dd>
<dd>default - A default value which is returned if there is no value associated to the given index.</dd>
<dt>Returns:</dt>
<dd>The value associated to the given index.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L205" >framework\hirudo\Hirudo\Core\Context\Request.php at line 205</a>

<h3 id="getSession()">getSession</h3>
<span class='k'></span> <span class='nx'>Session</span> <span class='nf'>getSession</span> ()

<div class="details">
<p>Gets the current session object.</p><dl>
<dt>Returns:</dt>
<dd>The current session.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Request.php#L213" >framework\hirudo\Hirudo\Core\Context\Request.php at line 213</a>

<h3 id="setSession()">setSession</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setSession</span> (Session session)

<div class="details">
<p></p><dl>
<dt>Import(id="session").</dt>
</dl>

</div>

- - -

