- - -

**Hirudo\Impl\StandAlone\SARequest**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line35" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 35</a>

# Class SARequest #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html">Request</a>\n    *** SARequest **\n</pre>

- - -

<p class="signature">public  class **SARequest**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html">Request</a>

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
<td class="type">static  <a href="../../../hirudo/impl/standalone/sarequest.html">SARequest</a></td>
<td class="description"><p class="name"><a href="#instance()">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#get()">get</a>(string name, mixed default)</p><p class="description">Retrieves a value from the GET parameters.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#post()">post</a>(string name, mixed default)</p><p class="description">Retrieves a value from the POST parameters.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#file()">file</a>(string name, mixed default)</p><p class="description">Retrieves a value from the FILE parameters.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#cookie()">cookie</a>(string name, mixed default)</p><p class="description">Retrieves a value from the COOKIE parameters.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#env()">env</a>(string name, mixed default)</p><p class="description">Retrieves a value from the ENV parameters.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#server()">server</a>(string name, mixed default)</p><p class="description">Retrieves a value from the SERVER parameters.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getURI()">getURI</a>()</p><p class="description">Gets the current URI as a string.</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#submitted()">submitted</a>()</p><p class="description">Determines if there is any data in the $_POST array.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a></td>
<td class="description"><p class="name"><a href="#buildModuleCall()">buildModuleCall</a>()</p><p class="description">Creates a ModuleCall from request parameters, generally from the URL,
the way this done depends on how this class interprets the URLs.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\Request</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#bind()">bind</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#buildModuleCall()">buildModuleCall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#cookie()">cookie</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#env()">env</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#file()">file</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#get()">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#getAttribute()">getAttribute</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#getSession()">getSession</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#getURI()">getURI</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#getVar()">getVar</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#method()">method</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#post()">post</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#removeAttribute()">removeAttribute</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#server()">server</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#setAttribute()">setAttribute</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#setSession()">setSession</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/request.html#submitted()">submitted</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line47" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 47</a>

<h3 id="instance()">instance</h3>
```php
public static  <a href="../../../hirudo/impl/standalone/sarequest.html">SARequest</a> **instance**()```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line55" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 55</a>

<h3 id="get()">get</h3>
```php
public  mixed **get**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line59" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 59</a>

<h3 id="post()">post</h3>
```php
public  mixed **post**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line63" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 63</a>

<h3 id="file()">file</h3>
```php
public  mixed **file**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line67" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 67</a>

<h3 id="cookie()">cookie</h3>
```php
public  mixed **cookie**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line71" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 71</a>

<h3 id="env()">env</h3>
```php
public  mixed **env**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line75" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 75</a>

<h3 id="server()">server</h3>
```php
public  mixed **server**(string name, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line79" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 79</a>

<h3 id="getURI()">getURI</h3>
```php
public  string **getURI**()```
<div class="details">
<p>Gets the current URI as a string.</p><dl>
<dt>Returns:</dt>
<dd>the current URI.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line84" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 84</a>

<h3 id="submitted()">submitted</h3>
```php
public  bool **submitted**()```
<div class="details">
<p>Determines if there is any data in the $_POST array.</p><dl>
<dt>Deprecated:</dt>
<dd>This method looks to be useless</dd>
<dt>Returns:</dt>
<dd><code>true</code> if there is POST data.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SARequest.php.md#line88" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARequest.php at line 88</a>

<h3 id="buildModuleCall()">buildModuleCall</h3>
```php
public  <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> **buildModuleCall**()```
<div class="details">
<p>Creates a ModuleCall from request parameters, generally from the URL,
the way this done depends on how this class interprets the URLs.</p><dl>
<dt>Returns:</dt>
<dd>An instance of ModuleCall based on this class interpretation of the URL</dd>
</dl>
</div>

- - -

