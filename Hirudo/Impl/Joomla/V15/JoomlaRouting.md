

- - -

**Hirudo\Impl\Joomla\V15\JoomlaRouting**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Joomla/V15/JoomlaRouting.php#L32" target='_blank'>framework\Hirudo\Impl\Joomla\V15\JoomlaRouting.php at line 32</a>

#Class JoomlaRouting#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md">Routing</a>
 &gt; **JoomlaRouting**




- - -

<p><strong>public  class</strong> <span>JoomlaRouting</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md">Routing</a>

</p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Export(id="routing").</dt>
<dt>Author:</dt>
<dd>Virtualidad</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#appaction">appAction</a>(string app, string module, str task, array params)</p><p class="description">Creates a route to the given task using the given application name
and the given module name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#redirect">redirect</a>(string url)</p><p class="description">Makes an HTTP redirect to the given absolute URL.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getbaseurl">getBaseURL</a>()</p><p class="description">Gets the current base URL.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\Routing</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#action">action</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#appaction">appAction</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#getappname">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#getbaseurl">getBaseURL</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#getmodulename">getModuleName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#moduleaction">moduleAction</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#redirect">redirect</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#setappname">setAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md#setmodulename">setModuleName</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Joomla/V15/JoomlaRouting.php#L34" target='_blank'>framework\Hirudo\Impl\Joomla\V15\JoomlaRouting.php at line 34</a>

<h3 id="appAction()">appAction</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>appAction</span> (string app, string module, str task, array params)

<div class="details">
<p>Creates a route to the given task using the given application name
and the given module name.</p><dl>
<dt>Parameters:</dt>
<dd>app - Aa application name.</dd>
<dd>module - A module name that belongs to the given application.</dd>
<dd>task - The task to be executed.</dd>
<dd>params - An array of key/value pairs of values to be appended as URL values.</dd>
<dt>Returns:</dt>
<dd>The resulting absolute URL.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Joomla/V15/JoomlaRouting.php#L51" target='_blank'>framework\Hirudo\Impl\Joomla\V15\JoomlaRouting.php at line 51</a>

<h3 id="redirect()">redirect</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>redirect</span> (string url)

<div class="details">
<p>Makes an HTTP redirect to the given absolute URL.</p><dl>
<dt>Parameters:</dt>
<dd>url - The absolute URL to make the redirection.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Joomla/V15/JoomlaRouting.php#L56" target='_blank'>framework\Hirudo\Impl\Joomla\V15\JoomlaRouting.php at line 56</a>

<h3 id="getBaseURL()">getBaseURL</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getBaseURL</span> ()

<div class="details">
<p>Gets the current base URL.</p><dl>
<dt>Returns:</dt>
<dd>The current base URL</dd>
</dl>

</div>

- - -

