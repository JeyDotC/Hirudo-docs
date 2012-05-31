- - -

**Hirudo\Core\Context\SessionStates**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Session.php.md#line27" class="location">framework\hirudo\Hirudo\Core\Context\Session.php at line 27</a>

# Class SessionStates #

<pre class="tree">\PseudoEnum\n*** SessionStates **\n</pre>

- - -

<p class="signature">public final  class **SessionStates**\nextends \PseudoEnum

</p>

<div class="comment" id="overview_description"><p>An enum representing the different sessions states.</p></div>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#get()">get</a>(string key, mixed default)</p><p class="description">Gets the value for the given key, or the given default value if there is no such
value that key.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#remove()">remove</a>(string key)</p><p class="description">Attempts to remove the object associated to the given key from session.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#state()">state</a>()</p><p class="description">Gets the current session state.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Session.php.md#line43" class="location">framework\hirudo\Hirudo\Core\Context\Session.php at line 43</a>

<h3 id="get()">get</h3>
```php
public  mixed **get**(string key, mixed default)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Session.php.md#line52" class="location">framework\hirudo\Hirudo\Core\Context\Session.php at line 52</a>

<h3 id="remove()">remove</h3>
```php
public  mixed **remove**(string key)```
<div class="details">
<p>Attempts to remove the object associated to the given key from session.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key for the object to be removed.</dd>
<dt>Returns:</dt>
<dd>The previous value. If there were no value for the given key, null is returned.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Context/Session.php.md#line62" class="location">framework\hirudo\Hirudo\Core\Context\Session.php at line 62</a>

<h3 id="state()">state</h3>
```php
public  string **state**()```
<div class="details">
<p>Gets the current session state.</p><dl>
<dt>Returns:</dt>
<dd>An string representing the current session state. The string can be any of the constants given in the SessionStates pseudoenum.</dd>
<dt>See Also:</dt>
<dd><a href="../../../hirudo/core/context/sessionstates.html">To know more about the possible session states.</a></dd>
</dl>
</div>

- - -

