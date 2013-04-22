

- - -

**Hirudo\Core\Context\Routing**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L30" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 30</a>

#Class Routing#

**Routing**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Drupal/DrupalRouting.md">Hirudo\Impl\Drupal\DrupalRouting</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Joomla/V15/JoomlaRouting.md">Hirudo\Impl\Joomla\V15\JoomlaRouting</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Joomla/V30/JoomlaRouting.md">Hirudo\Impl\Joomla\V30\JoomlaRouting</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/StandAlone/SARouting.md">Hirudo\Impl\StandAlone\SARouting</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>Routing</span></p>

<div class="comment" id="overview_description"><p>A class to create internal routes. An instance of this class can be bound
to a certain module in a certain appplication.</p></div>

<dl>
<dt>Author:</dt>
<dd>Virtualidad</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#action">action</a>(string task, array params)</p><p class="description">Creates a route to the given task using the current application name
and the current module name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#moduleaction">moduleAction</a>(string module, string task, array params)</p><p class="description">Creates a route to the given task using the current application name
and the given module name.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#appaction">appAction</a>(string app, string module, string task, array params)</p><p class="description">Creates a route to the given task using the given application name
and the given module name.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getbaseurl">getBaseURL</a>()</p><p class="description">Gets the current base URL.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#redirect">redirect</a>(string url)</p><p class="description">Makes an HTTP redirect to the given absolute URL.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getmodulename">getModuleName</a>()</p><p class="description">Gets the current module name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setmodulename">setModuleName</a>(string moduleName)</p><p class="description">Sets the current module name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getappname">getAppName</a>()</p><p class="description">Gets the current application name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setappname">setAppName</a>(string appName)</p><p class="description">Sets the current application name.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L44" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 44</a>

<h3 id="action()">action</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>action</span> (string task, array params)

<div class="details">
<p>Creates a route to the given task using the current application name
and the current module name.</p><dl>
<dt>Parameters:</dt>
<dd>task - The task to be executed.</dd>
<dd>params - An array of key/value pairs of values to be appended as URL values.</dd>
<dt>Returns:</dt>
<dd>The resulting absolute URL.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L58" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 58</a>

<h3 id="moduleAction()">moduleAction</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>moduleAction</span> (string module, string task, array params)

<div class="details">
<p>Creates a route to the given task using the current application name
and the given module name.</p><dl>
<dt>Parameters:</dt>
<dd>module - A module name that belongs to the current application.</dd>
<dd>task - The task to be executed.</dd>
<dd>params - An array of key/value pairs of values to be appended as URL values.</dd>
<dt>Returns:</dt>
<dd>The resulting absolute URL.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L73" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 73</a>

<h3 id="appAction()">appAction</h3>
<span class='k'>abstract </span> <span class='nx'>string</span> <span class='nf'>appAction</span> (string app, string module, string task, array params)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L80" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 80</a>

<h3 id="getBaseURL()">getBaseURL</h3>
<span class='k'>abstract </span> <span class='nx'>string</span> <span class='nf'>getBaseURL</span> ()

<div class="details">
<p>Gets the current base URL.</p><dl>
<dt>Returns:</dt>
<dd>The current base URL</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L87" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 87</a>

<h3 id="redirect()">redirect</h3>
<span class='k'>abstract </span> <span class='nx'>void</span> <span class='nf'>redirect</span> (string url)

<div class="details">
<p>Makes an HTTP redirect to the given absolute URL.</p><dl>
<dt>Parameters:</dt>
<dd>url - The absolute URL to make the redirection.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L94" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 94</a>

<h3 id="getModuleName()">getModuleName</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getModuleName</span> ()

<div class="details">
<p>Gets the current module name.</p><dl>
<dt>Returns:</dt>
<dd>The name of the current module.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L103" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 103</a>

<h3 id="setModuleName()">setModuleName</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setModuleName</span> (string moduleName)

<div class="details">
<p>Sets the current module name.</p><dl>
<dt>Parameters:</dt>
<dd>moduleName - The name of the module.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L112" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 112</a>

<h3 id="getAppName()">getAppName</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getAppName</span> ()

<div class="details">
<p>Gets the current application name.</p><dl>
<dt>Returns:</dt>
<dd>The current app name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Routing.php#L121" target='_blank'>framework\Hirudo\Core\Context\Routing.php at line 121</a>

<h3 id="setAppName()">setAppName</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setAppName</span> (string appName)

<div class="details">
<p>Sets the current application name.</p><dl>
<dt>Parameters:</dt>
<dd>appName - The current application name.</dd>
</dl>

</div>

- - -

