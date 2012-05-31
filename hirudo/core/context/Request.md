- - -

**Hirudo\Core\Context\Request**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line33" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 33</a>

# Class Request #

<pre class="tree">** Request **\n</pre>

<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/joomla/joomlarequest.html">Hirudo\Impl\Joomla\JoomlaRequest</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/standalone/sarequest.html">Hirudo\Impl\StandAlone\SARequest</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Request**</p>

<div class="comment" id="overview_description"><p>This object represents the current request.</p></div>

<dl>
<dt>Author:</dt>
<dd>Virtualidad</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setAttribute()">setAttribute</a>(string key, mixed value)</p><p class="description">Stores a value in memory so it can be accesed "gloablly".</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getAttribute()">getAttribute</a>(string key, mixed default)</p><p class="description">Gets an in-memory value from the current request which is stored with
the setAttribute() method.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#removeAttribute()">removeAttribute</a>(string key)</p><p class="description">Removes an in-memory stored value from this request.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#bind()">bind</a>(type object, type bindings)</p><p class="description">TODO: #desition Remove this method?</p></td>
</tr>
<tr>
<td class="type">abstract  mixed</td>
<td class="description"><p class="name"><a href="#get()">get</a>(string name, mixed default)</p><p class="description">Retrieves a value from the GET parameters.</p></td>
</tr>
<tr>
<td class="type">abstract  mixed</td>
<td class="description"><p class="name"><a href="#post()">post</a>(string name, mixed default)</p><p class="description">Retrieves a value from the POST parameters.</p></td>
</tr>
<tr>
<td class="type">abstract  mixed</td>
<td class="description"><p class="name"><a href="#file()">file</a>(string name, mixed default)</p><p class="description">Retrieves a value from the FILE parameters.</p></td>
</tr>
<tr>
<td class="type">abstract  mixed</td>
<td class="description"><p class="name"><a href="#cookie()">cookie</a>(string name, mixed default)</p><p class="description">Retrieves a value from the COOKIE parameters.</p></td>
</tr>
<tr>
<td class="type">abstract  mixed</td>
<td class="description"><p class="name"><a href="#env()">env</a>(string name, mixed default)</p><p class="description">Retrieves a value from the ENV parameters.</p></td>
</tr>
<tr>
<td class="type">abstract  mixed</td>
<td class="description"><p class="name"><a href="#server()">server</a>(string name, mixed default)</p><p class="description">Retrieves a value from the SERVER parameters.</p></td>
</tr>
<tr>
<td class="type">abstract  string</td>
<td class="description"><p class="name"><a href="#getURI()">getURI</a>()</p><p class="description">Gets the current URI as a string.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#method()">method</a>()</p><p class="description">Gets the current HTTP method (GET, POST, PUT, DELETE).</p></td>
</tr>
<tr>
<td class="type">abstract  <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a></td>
<td class="description"><p class="name"><a href="#buildModuleCall()">buildModuleCall</a>()</p><p class="description">Creates a ModuleCall from request parameters, generally from the URL,
the way this done depends on how this class interprets the URLs.</p></td>
</tr>
<tr>
<td class="type">abstract  bool</td>
<td class="description"><p class="name"><a href="#submitted()">submitted</a>()</p><p class="description">Determines if there is any data in the $_POST array.</p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#getVar()">getVar</a>(array collection, string index, mixed default)</p><p class="description">An utility method that simply returns tha value associated to the given
index or the given default value if there is no value associated to the
index.</p></td>
</tr>
<tr>
<td class="type"> Session</td>
<td class="description"><p class="name"><a href="#getSession()">getSession</a>()</p><p class="description">Gets the current session object.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setSession()">setSession</a>(Session session)</p><p class="description"></p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line49" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 49</a>

<h3 id="setAttribute()">setAttribute</h3>
```php
public  void **setAttribute**(string key, mixed value)```
<div class="details">
<p>Stores a value in memory so it can be accesed "gloablly".</p><dl>
<dt>Parameters:</dt>
<dd>key - A key to identify the value.</dd>
<dd>value - The value.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line62" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 62</a>

<h3 id="getAttribute()">getAttribute</h3>
```php
public  mixed **getAttribute**(string key, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line72" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 72</a>

<h3 id="removeAttribute()">removeAttribute</h3>
```php
public  mixed **removeAttribute**(string key)```
<div class="details">
<p>Removes an in-memory stored value from this request.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key corresponding to the value to be removed.</dd>
<dt>Returns:</dt>
<dd>The value that has been removed.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line88" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 88</a>

<h3 id="bind()">bind</h3>
```php
public  void **bind**(type object, type bindings)```
<div class="details">
<p>TODO: #desition Remove this method?</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line100" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 100</a>

<h3 id="get()">get</h3>
```php
public abstract  mixed **get**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line109" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 109</a>

<h3 id="post()">post</h3>
```php
public abstract  mixed **post**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line118" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 118</a>

<h3 id="file()">file</h3>
```php
public abstract  mixed **file**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line127" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 127</a>

<h3 id="cookie()">cookie</h3>
```php
public abstract  mixed **cookie**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line136" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 136</a>

<h3 id="env()">env</h3>
```php
public abstract  mixed **env**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line145" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 145</a>

<h3 id="server()">server</h3>
```php
public abstract  mixed **server**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line152" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 152</a>

<h3 id="getURI()">getURI</h3>
```php
public abstract  string **getURI**()```
<div class="details">
<p>Gets the current URI as a string.</p><dl>
<dt>Returns:</dt>
<dd>the current URI.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line159" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 159</a>

<h3 id="method()">method</h3>
```php
public  string **method**()```
<div class="details">
<p>Gets the current HTTP method (GET, POST, PUT, DELETE).</p><dl>
<dt>Returns:</dt>
<dd>Returns a string with the current HTTP method.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line169" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 169</a>

<h3 id="buildModuleCall()">buildModuleCall</h3>
```php
public abstract  <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> **buildModuleCall**()```
<div class="details">
<p>Creates a ModuleCall from request parameters, generally from the URL,
the way this done depends on how this class interprets the URLs.</p><dl>
<dt>Returns:</dt>
<dd>An instance of ModuleCall based on this class interpretation of the URL</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line177" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 177</a>

<h3 id="submitted()">submitted</h3>
```php
public abstract  bool **submitted**()```
<div class="details">
<p>Determines if there is any data in the $_POST array.</p><dl>
<dt>Deprecated:</dt>
<dd>This method looks to be useless</dd>
<dt>Returns:</dt>
<dd><code>true</code> if there is POST data.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line190" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 190</a>

<h3 id="getVar()">getVar</h3>
```php
protected  mixed **getVar**(array collection, string index, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line205" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 205</a>

<h3 id="getSession()">getSession</h3>
```php
public  Session **getSession**()```
<div class="details">
<p>Gets the current session object.</p><dl>
<dt>Returns:</dt>
<dd>The current session.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Request.php.md#line213" class="location">framework\hirudo\Hirudo\Core\Context\Request.php at line 213</a>

<h3 id="setSession()">setSession</h3>
```php
public  void **setSession**(Session session)```
<div class="details">
<p></p><dl>
<dt>Import(id="session").</dt>
</dl>
</div>

- - -

