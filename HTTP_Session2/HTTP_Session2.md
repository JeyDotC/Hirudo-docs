

- - -

**HTTP_Session2\HTTP_Session2**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L112" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 112</a>

#Class HTTP_Session2#

**HTTP_Session2**




- - -

<p><strong>public  class</strong> <span>HTTP_Session2</span></p>

<div class="comment" id="overview_description"><p>Class for managing HTTP sessions</p><p>Provides access to session-state values as well as session-level
settings and lifetime management methods.
Based on the standart PHP session handling mechanism
it provides for you more advanced features such as
database container, idle and expire timeouts, etc.</p><p>Expample 1:</p><p><code>
// Setting some options and detecting of a new session
HTTP_Session2::useCookies(false);
HTTP_Session2::start('MySessionID');
HTTP_Session2::set('variable', 'The string');
if (HTTP_Session2::isNew()) {
echo 'new session was created with the current request';
$visitors++; // Increase visitors count
}</p><p>//HTTP_Session2::regenerateId();
</code></p><p>Example 2:</p><p><code>
// Using database container
HTTP_Session2::setContainer('DB');
HTTP_Session2::start();
</code></p><p>Example 3:</p><p><code>
// Setting timeouts
HTTP_Session2::start();
HTTP_Session2::setExpire(time() + 60 * 60); // expires in one hour
HTTP_Session2::setIdle(10 * 60);            // idles in ten minutes
if (HTTP_Session2::isExpired()) {
// expired
echo('Your session is expired!');
HTTP_Session2::destroy();
}
if (HTTP_Session2::isIdle()) {
// idle
echo('You've been idle for too long!');
HTTP_Session2::destroy();
}
HTTP_Session2::updateIdle();
</code></p></div>

<dl>
<dt>Category:</dt>
<dd>HTTP</dd>
<dt>Author:</dt>
<dd>Alexander Radivaniovich <info@wwwlab.net></dd>
<dd>Tony Bibbs <tony@geeklog.net></dd>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/bsd-license.php The BSD License</dd>
<dt>Version:</dt>
<dd>Release: @package_version@</dd>
<dt>See Also:</dt>
<dd><code><a href="http://pear.php.net/package/HTTP_Session2">http://pear.php.net/package/HTTP_Session2</a></code></dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Constant Summary</th></tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>int</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2.md#continued">CONTINUED</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>int</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2.md#err_not_implemented">ERR_NOT_IMPLEMENTED</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>int</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2.md#err_system_perm">ERR_SYSTEM_PERM</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>int</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2.md#err_system_precondition">ERR_SYSTEM_PRECONDITION</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>int</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2.md#err_unknown_container">ERR_UNKNOWN_CONTAINER</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>int</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2.md#started">STARTED</a>
                                </p><p class="description"></p></td>
</tr>
</table>



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2.md#container"> $container</a>
                                </p><p class="description">Container instance</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setcontainer">setContainer</a>(string container, array container_options)</p><p class="description">Sets user-defined session storage functionsSets the user-defined session storage functions which are used
for storing and retrieving data associated with a session.
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#start">start</a>(string name, string id)</p><p class="description">Initializes session dataCreates a session (or resumes the current one
based on the session id being passed
via a GET variable or a cookie).
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#pause">pause</a>()</p><p class="description">Writes session data and ends sessionSession data is usually stored after your script
terminated without the need to call HTTP_Session2::stop(),
but as session data is locked to prevent concurrent
writes only one script may operate on a session at any time.
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#destroy">destroy</a>()</p><p class="description">Frees all session variables and destroys all data
registered to a sessionThis method resets the $_SESSION variable and
destroys all of the data associated
with the current session in its storage (file or DB).
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#clear">clear</a>()</p><p class="description">Free all session variables</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#detectid">detectID</a>()</p><p class="description">Tries to find any session id in $_GET, $_POST or $_COOKIE</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#name">name</a>(string name)</p><p class="description">Sets new name of a session</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#id">id</a>(string id)</p><p class="description">Sets new ID of a session</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setexpire">setExpire</a>(integer time, bool add)</p><p class="description">Sets the maximum expire time</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setidle">setIdle</a>(integer time, bool add)</p><p class="description">Sets the maximum idle timeSets the time-out period allowed
between requests before the session-state
provider terminates the session.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#sessionvalidthru">sessionValidThru</a>()</p><p class="description">Returns the time up to the session is valid</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isexpired">isExpired</a>()</p><p class="description">Check if session is expired</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isidle">isIdle</a>()</p><p class="description">Check if session is idle</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#updateidle">updateIdle</a>()</p><p class="description">Updates the idletime</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#usecookies">useCookies</a>(boolean useCookies)</p><p class="description">If optional parameter is specified it indicates whether the module will
use cookies to store the session id on the client side in a cookie.
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isnew">isNew</a>()</p><p class="description">Gets a value indicating whether the session
was created with the current requestYou MUST call this method only after you have started
the session with the HTTP_Session2::start() method.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register">register</a>(string name)</p><p class="description">Register variable with the current session</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#unregister">unregister</a>(string name)</p><p class="description">Unregister a variable from the current session</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string name, mixed default)</p><p class="description">Returns session variable</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#set">set</a>(string name, mixed value)</p><p class="description">Sets session variable</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getlocal">getLocal</a>(string name, mixed default)</p><p class="description">Returns local variable of a scriptTwo scripts can have local variables with the same names</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#setlocal">setLocal</a>(string name, mixed value)</p><p class="description">Sets local variable of a script.
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#usetranssid">useTransSID</a>(boolean useTransSID)</p><p class="description">set the usage of transparent SID</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#localname">localName</a>(string name)</p><p class="description">Sets new local name</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#init">init</a>()</p><p class="description">init</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#regenerateid">regenerateId</a>(boolean deleteOldSessionData)</p><p class="description">Regenrates session idIf session_regenerate_id() is not available emulates its functionality</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#replicate">replicate</a>(string target, string id)</p><p class="description">This function copies session data of specified id to specified table</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#setgcmaxlifetime">setGcMaxLifetime</a>(int gcMaxLifetime)</p><p class="description">If optional parameter is specified it determines the number of seconds
after which session data will be seen as 'garbage' and cleaned upIt returns the previous value of this property</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#setgcprobability">setGcProbability</a>(int gcProbability)</p><p class="description">If optional parameter is specified it determines the
probability that the gc (garbage collection) routine is started
and session data is cleaned upIt returns the previous value of this property</p></td>
</tr>
</table>

##Constant Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L122" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 122</a>

<h3 id="CONTINUED">CONTINUED</h3>
<span class='k'>final static </span> <span class='nx'>int</span><span class='no'>CONTINUED</span><span class='o'> = 2</span>

<div class="details">
<p></p><dl>
<dt>Const:</dt>
<dd>CONTINUE - No new session was started with the current request</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L144" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 144</a>

<h3 id="ERR_NOT_IMPLEMENTED">ERR_NOT_IMPLEMENTED</h3>
<span class='k'>final static </span> <span class='nx'>int</span><span class='no'>ERR_NOT_IMPLEMENTED</span><span class='o'> = 670</span>

<div class="details">
<p></p><dl>
<dt>Const:</dt>
<dd>ERR_NOT_IMPLEMENTED Feature is not yet Implement in the container.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L133" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 133</a>

<h3 id="ERR_SYSTEM_PERM">ERR_SYSTEM_PERM</h3>
<span class='k'>final static </span> <span class='nx'>int</span><span class='no'>ERR_SYSTEM_PERM</span><span class='o'> = 668</span>

<div class="details">
<p></p><dl>
<dt>Const:</dt>
<dd>ERR_SYSTEM_PERM - System permissions not sufficient. E.g. Not enough permissions to override ini-settings.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L139" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 139</a>

<h3 id="ERR_SYSTEM_PRECONDITION">ERR_SYSTEM_PRECONDITION</h3>
<span class='k'>final static </span> <span class='nx'>int</span><span class='no'>ERR_SYSTEM_PRECONDITION</span><span class='o'> = 669</span>

<div class="details">
<p></p><dl>
<dt>Const:</dt>
<dd>ERR_SYSTEM_PRECONDITION - Precondition failed. E.g. error occured and HTTP_Session2 can't start up, etc..</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L127" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 127</a>

<h3 id="ERR_UNKNOWN_CONTAINER">ERR_UNKNOWN_CONTAINER</h3>
<span class='k'>final static </span> <span class='nx'>int</span><span class='no'>ERR_UNKNOWN_CONTAINER</span><span class='o'> = 667</span>

<div class="details">
<p></p><dl>
<dt>Const:</dt>
<dd>ERR_UNKNOWN_CONTAINER - Container not found.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L117" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 117</a>

<h3 id="STARTED">STARTED</h3>
<span class='k'>final static </span> <span class='nx'>int</span><span class='no'>STARTED</span><span class='o'> = 1</span>

<div class="details">
<p></p><dl>
<dt>Const:</dt>
<dd>STARTED - The session was started with the current request</dd>
</dl>

</div>

- - -

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L149" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 149</a>

<h3 id="container">container</h3>
<span class='k'>static </span> <span class='nx'>mixed</span><span class='no'> $container</span><div class="details">
<p>Container instance</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L166" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 166</a>

<h3 id="setContainer()">setContainer</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>setContainer</span> (string container, array container_options)

<div class="details">
<p>Sets user-defined session storage functions</p><p>Sets the user-defined session storage functions which are used
for storing and retrieving data associated with a session.
This is most useful when a storage method other than
those supplied by PHP sessions is preferred.
i.e. Storing the session data in a local database.</p><dl>
<dt>Parameters:</dt>
<dd>container - Name of the container (e.g. DB, MDB, ...).</dd>
<dd>container_options - Options, most likely an array.</dd>
<dt>See Also:</dt>
<dd>session_set_save_handler()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L200" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 200</a>

<h3 id="start()">start</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>start</span> (string name, string id)

<div class="details">
<p>Initializes session data</p><p>Creates a session (or resumes the current one
based on the session id being passed
via a GET variable or a cookie).
You can provide your own name and/or id for a session.</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of a session, default is 'SessionID'</dd>
<dd>id - Id of a session which will be used only when the session is new</dd>
<dt>See Also:</dt>
<dd>session_name()</dd>
<dd>session_id()</dd>
<dd>session_start()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L233" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 233</a>

<h3 id="pause()">pause</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>pause</span> ()

<div class="details">
<p>Writes session data and ends session</p><p>Session data is usually stored after your script
terminated without the need to call HTTP_Session2::stop(),
but as session data is locked to prevent concurrent
writes only one script may operate on a session at any time.
When using framesets together with sessions you will
experience the frames loading one by one due to this
locking. You can reduce the time needed to load all the
frames by ending the session as soon as all changes
to session variables are done.</p><dl>
<dt>See Also:</dt>
<dd>session_write_close()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L251" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 251</a>

<h3 id="destroy()">destroy</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>destroy</span> ()

<div class="details">
<p>Frees all session variables and destroys all data
registered to a session</p><p>This method resets the $_SESSION variable and
destroys all of the data associated
with the current session in its storage (file or DB).
It forces new session to be started after this method
is called. It does not unset the session cookie.</p><dl>
<dt>See Also:</dt>
<dd>session_unset()</dd>
<dd>session_destroy()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L262" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 262</a>

<h3 id="clear()">clear</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>clear</span> ()

<div class="details">
<p>Free all session variables</p><dl>
<dt>Todo:</dt>
<dd>TODO Save expire and idle timestamps?</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L275" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 275</a>

<h3 id="detectID()">detectID</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>detectID</span> ()

<div class="details">
<p>Tries to find any session id in $_GET, $_POST or $_COOKIE</p><dl>
<dt>Returns:</dt>
<dd>Session ID (if exists) or null</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L299" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 299</a>

<h3 id="name()">name</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>name</span> (string name)

<div class="details">
<p>Sets new name of a session</p><dl>
<dt>Parameters:</dt>
<dd>name - New name of a sesion</dd>
<dt>Returns:</dt>
<dd>Previous name of a session</dd>
<dt>See Also:</dt>
<dd>session_name()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L314" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 314</a>

<h3 id="id()">id</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>id</span> (string id)

<div class="details">
<p>Sets new ID of a session</p><dl>
<dt>Parameters:</dt>
<dd>id - New ID of a sesion</dd>
<dt>Returns:</dt>
<dd>Previous ID of a session</dd>
<dt>See Also:</dt>
<dd>session_id()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L329" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 329</a>

<h3 id="setExpire()">setExpire</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>setExpire</span> (integer time, bool add)

<div class="details">
<p>Sets the maximum expire time</p><dl>
<dt>Parameters:</dt>
<dd>time - Time in seconds</dd>
<dd>add - Add time to current expire time or not</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L352" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 352</a>

<h3 id="setIdle()">setIdle</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>setIdle</span> (integer time, bool add)

<div class="details">
<p>Sets the maximum idle time</p><p>Sets the time-out period allowed
between requests before the session-state
provider terminates the session.</p><dl>
<dt>Parameters:</dt>
<dd>time - Time in seconds</dd>
<dd>add - Add time to current maximum idle time or not</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L368" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 368</a>

<h3 id="sessionValidThru()">sessionValidThru</h3>
<span class='k'>static </span> <span class='nx'>integer</span> <span class='nf'>sessionValidThru</span> ()

<div class="details">
<p>Returns the time up to the session is valid</p><dl>
<dt>Returns:</dt>
<dd>Time when the session idles</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L383" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 383</a>

<h3 id="isExpired()">isExpired</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>isExpired</span> ()

<div class="details">
<p>Check if session is expired</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L403" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 403</a>

<h3 id="isIdle()">isIdle</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>isIdle</span> ()

<div class="details">
<p>Check if session is idle</p><dl>
<dt>Returns:</dt>
<dd>Obvious</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L422" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 422</a>

<h3 id="updateIdle()">updateIdle</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>updateIdle</span> ()

<div class="details">
<p>Updates the idletime</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L450" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 450</a>

<h3 id="useCookies()">useCookies</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>useCookies</span> (boolean useCookies)

<div class="details">
<p>If optional parameter is specified it indicates whether the module will
use cookies to store the session id on the client side in a cookie.</p><p>By default this cookie will be deleted when the browser is closed!</p><p>It will throw an Exception if it's not able to set the session.use_cookie
property.</p><p>It returns the previous value of this property.</p><dl>
<dt>Parameters:</dt>
<dd>useCookies - If specified it will replace the previous value of this property. By default 'null', which doesn't change any setting on your system. If you supply a parameter, please supply 'boolean'.</dd>
<dt>Returns:</dt>
<dd>The previous value of the property</dd>
<dt>Throws:</dt>
<dd><a href="../http_session2/http_session2_exception.html">HTTP_Session2_Exception</a> - If ini_set() fails!</dd>
<dt>See Also:</dt>
<dd>session_set_cookie_params()</dd>
<dt>See Also:</dt>
<dd><code><a href="http://php.net/manual/en/function.session-set-cookie-params.php">http://php.net/manual/en/function.session-set-cookie-params.php</a></code></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L484" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 484</a>

<h3 id="isNew()">isNew</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>isNew</span> ()

<div class="details">
<p>Gets a value indicating whether the session
was created with the current request</p><p>You MUST call this method only after you have started
the session with the HTTP_Session2::start() method.</p><dl>
<dt>Returns:</dt>
<dd>true when the session was created with the current request false otherwise</dd>
<dt>See Also:</dt>
<dd>self::start()</dd>
<dt>Uses:</dt>
<dd>self::STARTED</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L502" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 502</a>

<h3 id="register()">register</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>register</span> (string name)

<div class="details">
<p>Register variable with the current session</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of a global variable</dd>
<dt>See Also:</dt>
<dd>session_register()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L514" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 514</a>

<h3 id="unregister()">unregister</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>unregister</span> (string name)

<div class="details">
<p>Unregister a variable from the current session</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of a global variable</dd>
<dt>See Also:</dt>
<dd>session_unregister()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L526" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 526</a>

<h3 id="get()">get</h3>
<span class='k'>static </span> <span class='nx'>mixed</span> <span class='nf'>get</span> (string name, mixed default)

<div class="details">
<p>Returns session variable</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of a variable</dd>
<dd>default - Default value of a variable if not set</dd>
<dt>Returns:</dt>
<dd>Value of a variable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L541" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 541</a>

<h3 id="set()">set</h3>
<span class='k'>static </span> <span class='nx'>mixed</span> <span class='nf'>set</span> (string name, mixed value)

<div class="details">
<p>Sets session variable</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of a variable</dd>
<dd>value - Value of a variable</dd>
<dt>Returns:</dt>
<dd>Old value of a variable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L561" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 561</a>

<h3 id="getLocal()">getLocal</h3>
<span class='k'>static </span> <span class='nx'>mixed</span> <span class='nf'>getLocal</span> (string name, mixed default)

<div class="details">
<p>Returns local variable of a script</p><p>Two scripts can have local variables with the same names</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of a variable</dd>
<dd>default - Default value of a variable if not set</dd>
<dt>Returns:</dt>
<dd>Value of a local variable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L581" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 581</a>

<h3 id="setLocal()">setLocal</h3>
<span class='k'>static </span> <span class='nx'>mixed</span> <span class='nf'>setLocal</span> (string name, mixed value)

<div class="details">
<p>Sets local variable of a script.
Two scripts can have local variables with the same names.</p><dl>
<dt>Parameters:</dt>
<dd>name - Name of a local variable</dd>
<dd>value - Value of a local variable</dd>
<dt>Returns:</dt>
<dd>Old value of a local variable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L602" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 602</a>

<h3 id="useTransSID()">useTransSID</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>useTransSID</span> (boolean useTransSID)

<div class="details">
<p>set the usage of transparent SID</p><dl>
<dt>Parameters:</dt>
<dd>useTransSID - Flag to use transparent SID</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L617" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 617</a>

<h3 id="localName()">localName</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>localName</span> (string name)

<div class="details">
<p>Sets new local name</p><dl>
<dt>Parameters:</dt>
<dd>name - New local name</dd>
<dt>Returns:</dt>
<dd>Previous local name</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L633" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 633</a>

<h3 id="init()">init</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>init</span> ()

<div class="details">
<p>init</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L650" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 650</a>

<h3 id="regenerateId()">regenerateId</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>regenerateId</span> (boolean deleteOldSessionData)

<div class="details">
<p>Regenrates session id</p><p>If session_regenerate_id() is not available emulates its functionality</p><dl>
<dt>Parameters:</dt>
<dd>deleteOldSessionData - Whether to delete data of old session</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L679" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 679</a>

<h3 id="replicate()">replicate</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>replicate</span> (string target, string id)

<div class="details">
<p>This function copies session data of specified id to specified table</p><dl>
<dt>Parameters:</dt>
<dd>target - Target to replicate to</dd>
<dd>id - Id of record to replicate</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L694" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 694</a>

<h3 id="setGcMaxLifetime()">setGcMaxLifetime</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>setGcMaxLifetime</span> (int gcMaxLifetime)

<div class="details">
<p>If optional parameter is specified it determines the number of seconds
after which session data will be seen as 'garbage' and cleaned up</p><p>It returns the previous value of this property</p><dl>
<dt>Parameters:</dt>
<dd>gcMaxLifetime - If specified it will replace the previous value of this property, and must be integer.</dd>
<dt>Returns:</dt>
<dd>The previous value of the property</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2.php#L714" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2.php at line 714</a>

<h3 id="setGcProbability()">setGcProbability</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>setGcProbability</span> (int gcProbability)

<div class="details">
<p>If optional parameter is specified it determines the
probability that the gc (garbage collection) routine is started
and session data is cleaned up</p><p>It returns the previous value of this property</p><dl>
<dt>Parameters:</dt>
<dd>gcProbability - If specified it will replace the previous value of this property.</dd>
<dt>Returns:</dt>
<dd>The previous value of the property</dd>
</dl>

</div>

- - -

