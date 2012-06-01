

- - -

**Hirudo\Core\Context\SessionStates**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Session.php#L27" >framework\hirudo\Hirudo\Core\Context\Session.php at line 27</a>

#Class SessionStates#

\PseudoEnum
* **SessionStates**




- - -

<p class="signature"><span class='k'>public final  class</span> <span class='nx'>SessionStates</span>
extends \PseudoEnum

</p>

<div class="comment" id="overview_description"><p>An enum representing the different sessions states.</p></div>



- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
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

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Session.php#L43" >framework\hirudo\Hirudo\Core\Context\Session.php at line 43</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Session.php#L52" >framework\hirudo\Hirudo\Core\Context\Session.php at line 52</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Session.php#L62" >framework\hirudo\Hirudo\Core\Context\Session.php at line 62</a>

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

