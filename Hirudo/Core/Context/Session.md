

- - -

**Hirudo\Core\Context\Session**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L56" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 56</a>

#Interface Session#

**Session**




- - -

<p><strong>public  interface</strong> <span>Session</span></p>

<div class="comment" id="overview_description"><p>Represents a session, the way the data is stored depends on the implementation.</p></div>

<dl>
<dt>Author:</dt>
<dd>Virtualidad</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#id">id</a>()</p><p class="description">Gets the session id.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#has">has</a>(string key)</p><p class="description">Tells if there is a value for the given key.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#put">put</a>(string key, mixed value)</p><p class="description">Sets a value with the given key. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string key, mixed default)</p><p class="description">Gets the value for the given key, or the given default value if there is no such
value that key.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#remove">remove</a>(string key)</p><p class="description">Attempts to remove the object associated to the given key from session.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#state">state</a>()</p><p class="description">Gets the current session state.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L63" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 63</a>

<h3 id="id()">id</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>id</span> ()

<div class="details">
<p>Gets the session id.</p><dl>
<dt>Returns:</dt>
<dd>The session id.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L72" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 72</a>

<h3 id="has()">has</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>has</span> (string key)

<div class="details">
<p>Tells if there is a value for the given key.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key for the requested value.</dd>
<dt>Returns:</dt>
<dd>True if there is a value for the given key, false otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L81" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 81</a>

<h3 id="put()">put</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>put</span> (string key, mixed value)

<div class="details">
<p><p>Sets a value with the given key. If there is a value already,
the former gets replaced.</p></p><dl>
<dt>Parameters:</dt>
<dd>key - The key for the new value.</dd>
<dd>value - The new value.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L92" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 92</a>

<h3 id="get()">get</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>get</span> (string key, mixed default)

<div class="details">
<p>Gets the value for the given key, or the given default value if there is no such
value that key.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key corresponding to the requested value.</dd>
<dd>default - A default value which is returned if there is no value associated to the given key.</dd>
<dt>Returns:</dt>
<dd>The value stored in session or the default value if there is no value associated to the given key.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L101" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 101</a>

<h3 id="remove()">remove</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>remove</span> (string key)

<div class="details">
<p>Attempts to remove the object associated to the given key from session.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key for the object to be removed.</dd>
<dt>Returns:</dt>
<dd>The previous value. If there were no value for the given key, null is returned.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L111" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 111</a>

<h3 id="state()">state</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>state</span> ()

<div class="details">
<p>Gets the current session state.</p><dl>
<dt>Returns:</dt>
<dd>An string representing the current session state. The string can be any of the constants given in the SessionStates pseudoenum.</dd>
<dt>See Also:</dt>
<dd><a href="../../../hirudo/core/context/sessionstates.html">To know more about the possible session states.</a></dd>
</dl>

</div>

- - -

