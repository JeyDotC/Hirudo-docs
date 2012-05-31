- - -

**Joomla.Framework\JURI**
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 30</div>
#Class JURI#

**JURI**


- - -

<p class="signature">public  class **JURI**</p>

<div class="comment" id="overview_description"><p>JURI Class</p><p>This class serves two purposes.  First to parse a URI and provide a common interface
for the Joomla Framework to access and manipulate a URI.  Second to attain the URI of
the current executing script from the server regardless of server.</p></div>

<dl>
<dt>Author:</dt>
<dd>Louis Landry <louis.landry@joomla.org></dd>
<dt>Subpackage:</dt>
<dd>Environment</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string uri)</p><p class="description">Constructor.
</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  <a href="../../joomla/framework/juri.html">JURI</a></td>
<td class="description"><p class="name"><a href="#getInstance">getInstance</a>(string uri)</p><p class="description">Returns a reference to a global JURI object, only creating it
if it doesn't already exist.
</p></td>
</tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#base">base</a>(boolean pathonly)</p><p class="description">Returns the base URI for the request.</p></td>
</tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#root">root</a>(boolean pathonly, mixed path)</p><p class="description">Returns the root URI for the request.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#current">current</a>()</p><p class="description">Returns the URL for the request, minus the query</p></td>
</tr>
<tr>
<td class="type">static  boolean</td>
<td class="description"><p class="name"><a href="#parse">parse</a>(string uri)</p><p class="description">Parse a given URI and populate the class fields</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#toString">toString</a>(array parts)</p><p class="description">Returns full uri string</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#setprivate">setprivate</a>(string name, string value)</p><p class="description">Adds a query privateiable and value, replacing the value if it
already exists and returning the old value.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getprivate">getprivate</a>(string name, mixed default)</p><p class="description">Returns a query privateiable by name</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#delprivate">delprivate</a>(string name)</p><p class="description">Removes an item from the query string privateiables if it exists</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setQuery">setQuery</a>(mixed (array|string), mixed query)</p><p class="description">Sets the query to a supplied string in format:
foo=bar&x=y</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getQuery">getQuery</a>(bool toArray)</p><p class="description">Returns flat query string</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#buildQuery">buildQuery</a>(mixed params, mixed akey)</p><p class="description">Build a query from a array (reverse of the PHP parse_str())</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getScheme">getScheme</a>()</p><p class="description">Get URI scheme (protocol)
ie. </p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setScheme">setScheme</a>(string scheme)</p><p class="description">Set URI scheme (protocol)
ie. </p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getUser">getUser</a>()</p><p class="description">Get URI username
returns the username, or null if no username was specified</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setUser">setUser</a>(string user)</p><p class="description">Set URI username</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getPass">getPass</a>()</p><p class="description">Get URI password
returns the password, or null if no password was specified</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setPass">setPass</a>(string pass)</p><p class="description">Set URI password</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getHost">getHost</a>()</p><p class="description">Get URI host
returns the hostname/ip, or null if no hostname/ip was specified</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setHost">setHost</a>(string host)</p><p class="description">Set URI host</p></td>
</tr>
<tr>
<td class="type"> int</td>
<td class="description"><p class="name"><a href="#getPort">getPort</a>()</p><p class="description">Get URI port
returns the port number, or null if no port was specified</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setPort">setPort</a>(int port)</p><p class="description">Set URI port</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getPath">getPath</a>()</p><p class="description">Gets the URI path string</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setPath">setPath</a>(string path)</p><p class="description">Set the URI path string</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getFragment">getFragment</a>()</p><p class="description">Get the URI archor string
everything after the "#"</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setFragment">setFragment</a>(string anchor)</p><p class="description">Set the URI anchor string
everything after the "#"</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#isSSL">isSSL</a>()</p><p class="description">Checks whether the current URI is using HTTPS</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 112</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(string uri)
```
<div class="details">
<p>Constructor.
You can pass a URI string to the constructor to initialize a specific URI.</p><dl>
<dt>Parameters:</dt>
<dd>uri - The optional URI string</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 130</div>
<h3 id="getInstance()">getInstance</h3>

```php
public static  <a href="../../joomla/framework/juri.html">JURI</a> **getInstance**(string uri)
```
<div class="details">
<p>Returns a reference to a global JURI object, only creating it
if it doesn't already exist.</p><p>This method must be invoked as:
<pre>  $uri =& JURI::getInstance([$uri]);</pre></p><dl>
<dt>Parameters:</dt>
<dd>uri - The URI to parse. [optional: if null uses script URI]</dd>
<dt>Returns:</dt>
<dd>The URI object.</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 197</div>
<h3 id="base()">base</h3>

```php
public static  string **base**(boolean pathonly)
```
<div class="details">
<p>Returns the base URI for the request.</p><dl>
<dt>Parameters:</dt>
<dd>pathonly - If false, prepend the scheme, host and port information. Default is false.</dd>
<dt>Returns:</dt>
<dd>The base URI string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 224</div>
<h3 id="root()">root</h3>

```php
public static  string **root**(boolean pathonly, mixed path)
```
<div class="details">
<p>Returns the root URI for the request.</p><dl>
<dt>Parameters:</dt>
<dd>pathonly - If false, prepend the scheme, host and port information. Default is false.</dd>
<dt>Returns:</dt>
<dd>The root URI string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 247</div>
<h3 id="current()">current</h3>

```php
public  string **current**()
```
<div class="details">
<p>Returns the URL for the request, minus the query</p><dl>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 267</div>
<h3 id="parse()">parse</h3>

```php
public static  boolean **parse**(string uri)
```
<div class="details">
<p>Parse a given URI and populate the class fields</p><dl>
<dt>Parameters:</dt>
<dd>uri - The URI string to parse</dd>
<dt>Returns:</dt>
<dd>True on success</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 311</div>
<h3 id="toString()">toString</h3>

```php
public  string **toString**(array parts)
```
<div class="details">
<p>Returns full uri string</p><dl>
<dt>Parameters:</dt>
<dd>parts - An array specifying the parts to render</dd>
<dt>Returns:</dt>
<dd>The rendered URI string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 337</div>
<h3 id="setprivate()">setprivate</h3>

```php
public  string **setprivate**(string name, string value)
```
<div class="details">
<p>Adds a query privateiable and value, replacing the value if it
already exists and returning the old value.</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of the query privateiable to set</dd>
<dd>value - Value of the query privateiable</dd>
<dt>Returns:</dt>
<dd>Previous value for the query privateiable</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 355</div>
<h3 id="getprivate()">getprivate</h3>

```php
public  array **getprivate**(string name, mixed default)
```
<div class="details">
<p>Returns a query privateiable by name</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of the query privateiable to get</dd>
<dt>Returns:</dt>
<dd>Query privateiables</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 369</div>
<h3 id="delprivate()">delprivate</h3>

```php
public  void **delprivate**(string name)
```
<div class="details">
<p>Removes an item from the query string privateiables if it exists</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of privateiable to remove</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 386</div>
<h3 id="setQuery()">setQuery</h3>

```php
public  void **setQuery**(mixed (array|string), mixed query)
```
<div class="details">
<p>Sets the query to a supplied string in format:
foo=bar&x=y</p><dl>
<dt>Parameters:</dt>
<dd>(array|string) - $query The query string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 409</div>
<h3 id="getQuery()">getQuery</h3>

```php
public  string **getQuery**(bool toArray)
```
<div class="details">
<p>Returns flat query string</p><dl>
<dt>Returns:</dt>
<dd>Query string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 430</div>
<h3 id="buildQuery()">buildQuery</h3>

```php
public  string **buildQuery**(mixed params, mixed akey)
```
<div class="details">
<p>Build a query from a array (reverse of the PHP parse_str())</p><dl>
<dt>Returns:</dt>
<dd>The resulting query string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
<dt>See Also:</dt>
<dd>parse_str()</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 464</div>
<h3 id="getScheme()">getScheme</h3>

```php
public  string **getScheme**()
```
<div class="details">
<p>Get URI scheme (protocol)
ie. http, https, ftp, etc...</p><dl>
<dt>Returns:</dt>
<dd>The URI scheme</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 476</div>
<h3 id="setScheme()">setScheme</h3>

```php
public  void **setScheme**(string scheme)
```
<div class="details">
<p>Set URI scheme (protocol)
ie. http, https, ftp, etc...</p><dl>
<dt>Parameters:</dt>
<dd>scheme - The URI scheme</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 488</div>
<h3 id="getUser()">getUser</h3>

```php
public  string **getUser**()
```
<div class="details">
<p>Get URI username
returns the username, or null if no username was specified</p><dl>
<dt>Returns:</dt>
<dd>The URI username</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 499</div>
<h3 id="setUser()">setUser</h3>

```php
public  void **setUser**(string user)
```
<div class="details">
<p>Set URI username</p><dl>
<dt>Parameters:</dt>
<dd>user - The URI username</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 511</div>
<h3 id="getPass()">getPass</h3>

```php
public  string **getPass**()
```
<div class="details">
<p>Get URI password
returns the password, or null if no password was specified</p><dl>
<dt>Returns:</dt>
<dd>The URI password</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 522</div>
<h3 id="setPass()">setPass</h3>

```php
public  void **setPass**(string pass)
```
<div class="details">
<p>Set URI password</p><dl>
<dt>Parameters:</dt>
<dd>pass - The URI password</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 534</div>
<h3 id="getHost()">getHost</h3>

```php
public  string **getHost**()
```
<div class="details">
<p>Get URI host
returns the hostname/ip, or null if no hostname/ip was specified</p><dl>
<dt>Returns:</dt>
<dd>The URI host</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 545</div>
<h3 id="setHost()">setHost</h3>

```php
public  void **setHost**(string host)
```
<div class="details">
<p>Set URI host</p><dl>
<dt>Parameters:</dt>
<dd>host - The URI host</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 556</div>
<h3 id="getPort()">getPort</h3>

```php
public  int **getPort**()
```
<div class="details">
<p>Get URI port
returns the port number, or null if no port was specified</p><dl>
<dt>Returns:</dt>
<dd>The URI port number</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 567</div>
<h3 id="setPort()">setPort</h3>

```php
public  void **setPort**(int port)
```
<div class="details">
<p>Set URI port</p><dl>
<dt>Parameters:</dt>
<dd>port - The URI port number</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 578</div>
<h3 id="getPath()">getPath</h3>

```php
public  string **getPath**()
```
<div class="details">
<p>Gets the URI path string</p><dl>
<dt>Returns:</dt>
<dd>The URI path string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 589</div>
<h3 id="setPath()">setPath</h3>

```php
public  void **setPath**(string path)
```
<div class="details">
<p>Set the URI path string</p><dl>
<dt>Parameters:</dt>
<dd>path - The URI path string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 601</div>
<h3 id="getFragment()">getFragment</h3>

```php
public  string **getFragment**()
```
<div class="details">
<p>Get the URI archor string
everything after the "#"</p><dl>
<dt>Returns:</dt>
<dd>The URI anchor string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 613</div>
<h3 id="setFragment()">setFragment</h3>

```php
public  void **setFragment**(string anchor)
```
<div class="details">
<p>Set the URI anchor string
everything after the "#"</p><dl>
<dt>Parameters:</dt>
<dd>anchor - The URI anchor string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 624</div>
<h3 id="isSSL()">isSSL</h3>

```php
public  boolean **isSSL**()
```
<div class="details">
<p>Checks whether the current URI is using HTTPS</p><dl>
<dt>Returns:</dt>
<dd>True if using SSL via HTTPS</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>
</div>

- - -

