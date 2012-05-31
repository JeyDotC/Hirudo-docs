- - -

**Hirudo\Impl\StandAlone\SARouting**
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARouting.php at line 31</div>
#Class SARouting#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html">Routing</a>
    ***SARouting**


- - -

<p class="signature">public  class **SARouting**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html">Routing</a>

</p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Hirudo\Core\Annotations\Export(id="routing").</dt>
<dt>Author:</dt>
<dd>Virtualidad</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#appAction">appAction</a>(string app, string module, str task, array params)</p><p class="description">Creates a route to the given task using the given application name
and the given module name.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#redirect">redirect</a>(string url)</p><p class="description">Makes an HTTP redirect to the given absolute URL.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getBaseURL">getBaseURL</a>()</p><p class="description">Gets the current base URL.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\Routing</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#action()">action</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#appAction()">appAction</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#getAppName()">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#getBaseURL()">getBaseURL</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#getModuleName()">getModuleName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#moduleAction()">moduleAction</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#redirect()">redirect</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#setAppName()">setAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/routing.html#setModuleName()">setModuleName</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARouting.php at line 33</div>
<h3 id="appAction()">appAction</h3>
```php
public  string **appAction**(string app, string module, str task, array params)```
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

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARouting.php at line 46</div>
<h3 id="redirect()">redirect</h3>
```php
public  void **redirect**(string url)```
<div class="details">
<p>Makes an HTTP redirect to the given absolute URL.</p><dl>
<dt>Parameters:</dt>
<dd>url - The absolute URL to make the redirection.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\SARouting.php at line 50</div>
<h3 id="getBaseURL()">getBaseURL</h3>
```php
public  string **getBaseURL**()```
<div class="details">
<p>Gets the current base URL.</p><dl>
<dt>Returns:</dt>
<dd>The current base URL</dd>
</dl>
</div>

- - -
