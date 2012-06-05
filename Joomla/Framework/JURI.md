

- - -

**Joomla.Framework\JURI**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L30" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 30</a>

#Class JURI#

**JURI**




- - -

<p><strong>public  class</strong> <span>JURI</span></p>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string uri)</p><p class="description">Constructor.
</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Joomla/Framework/JURI.md#getInstance>JURI</a></span></td>
<td class="description"><p class="name"><a href="#getinstance">getInstance</a>(string uri)</p><p class="description">Returns a reference to a global JURI object, only creating it
if it doesn't already exist.
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#base">base</a>(boolean pathonly)</p><p class="description">Returns the base URI for the request.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#root">root</a>(boolean pathonly, mixed path)</p><p class="description">Returns the root URI for the request.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#current">current</a>()</p><p class="description">Returns the URL for the request, minus the query</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#parse">parse</a>(string uri)</p><p class="description">Parse a given URI and populate the class fields</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#tostring">toString</a>(array parts)</p><p class="description">Returns full uri string</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#setprivate">setprivate</a>(string name, string value)</p><p class="description">Adds a query privateiable and value, replacing the value if it
already exists and returning the old value.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getprivate">getprivate</a>(string name, mixed default)</p><p class="description">Returns a query privateiable by name</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#delprivate">delprivate</a>(string name)</p><p class="description">Removes an item from the query string privateiables if it exists</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setquery">setQuery</a>(mixed (array|string), mixed query)</p><p class="description">Sets the query to a supplied string in format:
foo=bar&x=y</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getquery">getQuery</a>(bool toArray)</p><p class="description">Returns flat query string</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#buildquery">buildQuery</a>(mixed params, mixed akey)</p><p class="description">Build a query from a array (reverse of the PHP parse_str())</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getscheme">getScheme</a>()</p><p class="description">Get URI scheme (protocol)
ie. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setscheme">setScheme</a>(string scheme)</p><p class="description">Set URI scheme (protocol)
ie. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getuser">getUser</a>()</p><p class="description">Get URI username
returns the username, or null if no username was specified</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setuser">setUser</a>(string user)</p><p class="description">Set URI username</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getpass">getPass</a>()</p><p class="description">Get URI password
returns the password, or null if no password was specified</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setpass">setPass</a>(string pass)</p><p class="description">Set URI password</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#gethost">getHost</a>()</p><p class="description">Get URI host
returns the hostname/ip, or null if no hostname/ip was specified</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#sethost">setHost</a>(string host)</p><p class="description">Set URI host</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name"><a href="#getport">getPort</a>()</p><p class="description">Get URI port
returns the port number, or null if no port was specified</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setport">setPort</a>(int port)</p><p class="description">Set URI port</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getpath">getPath</a>()</p><p class="description">Gets the URI path string</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setpath">setPath</a>(string path)</p><p class="description">Set the URI path string</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getfragment">getFragment</a>()</p><p class="description">Get the URI archor string
everything after the "#"</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setfragment">setFragment</a>(string anchor)</p><p class="description">Set the URI anchor string
everything after the "#"</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isssl">isSSL</a>()</p><p class="description">Checks whether the current URI is using HTTPS</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L112" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 112</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string uri)

<div class="details">
<p>Constructor.
You can pass a URI string to the constructor to initialize a specific URI.</p><dl>
<dt>Parameters:</dt>
<dd>uri - The optional URI string</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L130" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 130</a>

<h3 id="getInstance()">getInstance</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Joomla/Framework/JURI.md#getInstance>JURI</a></span> <span class='nf'>getInstance</span> (string uri)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L197" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 197</a>

<h3 id="base()">base</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>base</span> (boolean pathonly)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L224" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 224</a>

<h3 id="root()">root</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>root</span> (boolean pathonly, mixed path)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L247" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 247</a>

<h3 id="current()">current</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>current</span> ()

<div class="details">
<p>Returns the URL for the request, minus the query</p><dl>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L267" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 267</a>

<h3 id="parse()">parse</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>parse</span> (string uri)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L311" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 311</a>

<h3 id="toString()">toString</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>toString</span> (array parts)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L337" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 337</a>

<h3 id="setprivate()">setprivate</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>setprivate</span> (string name, string value)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L355" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 355</a>

<h3 id="getprivate()">getprivate</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getprivate</span> (string name, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L369" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 369</a>

<h3 id="delprivate()">delprivate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>delprivate</span> (string name)

<div class="details">
<p>Removes an item from the query string privateiables if it exists</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of privateiable to remove</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L386" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 386</a>

<h3 id="setQuery()">setQuery</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setQuery</span> (mixed (array|string), mixed query)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L409" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 409</a>

<h3 id="getQuery()">getQuery</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getQuery</span> (bool toArray)

<div class="details">
<p>Returns flat query string</p><dl>
<dt>Returns:</dt>
<dd>Query string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L430" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 430</a>

<h3 id="buildQuery()">buildQuery</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>buildQuery</span> (mixed params, mixed akey)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L464" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 464</a>

<h3 id="getScheme()">getScheme</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getScheme</span> ()

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L476" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 476</a>

<h3 id="setScheme()">setScheme</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setScheme</span> (string scheme)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L488" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 488</a>

<h3 id="getUser()">getUser</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getUser</span> ()

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L499" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 499</a>

<h3 id="setUser()">setUser</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setUser</span> (string user)

<div class="details">
<p>Set URI username</p><dl>
<dt>Parameters:</dt>
<dd>user - The URI username</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L511" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 511</a>

<h3 id="getPass()">getPass</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getPass</span> ()

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L522" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 522</a>

<h3 id="setPass()">setPass</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setPass</span> (string pass)

<div class="details">
<p>Set URI password</p><dl>
<dt>Parameters:</dt>
<dd>pass - The URI password</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L534" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 534</a>

<h3 id="getHost()">getHost</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getHost</span> ()

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L545" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 545</a>

<h3 id="setHost()">setHost</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setHost</span> (string host)

<div class="details">
<p>Set URI host</p><dl>
<dt>Parameters:</dt>
<dd>host - The URI host</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L556" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 556</a>

<h3 id="getPort()">getPort</h3>
<span class='k'></span> <span class='nx'>int</span> <span class='nf'>getPort</span> ()

<div class="details">
<p>Get URI port
returns the port number, or null if no port was specified</p><dl>
<dt>Returns:</dt>
<dd>The URI port number</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L567" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 567</a>

<h3 id="setPort()">setPort</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setPort</span> (int port)

<div class="details">
<p>Set URI port</p><dl>
<dt>Parameters:</dt>
<dd>port - The URI port number</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L578" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 578</a>

<h3 id="getPath()">getPath</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getPath</span> ()

<div class="details">
<p>Gets the URI path string</p><dl>
<dt>Returns:</dt>
<dd>The URI path string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L589" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 589</a>

<h3 id="setPath()">setPath</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setPath</span> (string path)

<div class="details">
<p>Set the URI path string</p><dl>
<dt>Parameters:</dt>
<dd>path - The URI path string</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L601" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 601</a>

<h3 id="getFragment()">getFragment</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getFragment</span> ()

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L613" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 613</a>

<h3 id="setFragment()">setFragment</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setFragment</span> (string anchor)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/lib/JURI.php#L624" target='_blank'>framework\hirudo\Hirudo\Impl\StandAlone\lib\JURI.php at line 624</a>

<h3 id="isSSL()">isSSL</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isSSL</span> ()

<div class="details">
<p>Checks whether the current URI is using HTTPS</p><dl>
<dt>Returns:</dt>
<dd>True if using SSL via HTTPS</dd>
<dt>Since:</dt>
<dd>1.5</dd>
</dl>

</div>

- - -

