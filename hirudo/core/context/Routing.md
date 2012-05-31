
- - -

**Hirudo\Core\Context\Routing**
<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 30</div>
#Class Routing#

**Routing**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/joomla/joomlarouting.html">Hirudo\Impl\Joomla\JoomlaRouting</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/standalone/sarouting.html">Hirudo\Impl\StandAlone\SARouting</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Routing**</p>

<div class="comment" id="overview_description"><p>A class to create internal routes. An instance of this class can be bound
to a certain module in a certain appplication.</p></div>

<dl>
<dt>Author:</dt>
<dd>Virtualidad</dd>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#action">action</a>(string task, array params)</p><p class="description">Creates a route to the given task using the current application name
and the current module name.</p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#moduleaction">moduleAction</a>(string module, string task, array params)</p><p class="description">Creates a route to the given task using the current application name
and the given module name.</p></td>
</tr>
<tr>
<td class="type"> abstract  string</td>
<td class="description"><p class="name"><a href="#appaction">appAction</a>(string app, string module, string task, array params)</p><p class="description">Creates a route to the given task using the given application name
and the given module name.</p></td>
</tr>
<tr>
<td class="type"> abstract  string</td>
<td class="description"><p class="name"><a href="#getbaseurl">getBaseURL</a>()</p><p class="description">Gets the current base URL.</p></td>
</tr>
<tr>
<td class="type"> abstract  void</td>
<td class="description"><p class="name"><a href="#redirect">redirect</a>(string url)</p><p class="description">Makes an HTTP redirect to the given absolute URL.</p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#getmodulename">getModuleName</a>()</p><p class="description">Gets the current module name.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setmodulename">setModuleName</a>(string moduleName)</p><p class="description">Sets the current module name.</p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#getappname">getAppName</a>()</p><p class="description">Gets the current application name.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setappname">setAppName</a>(string appName)</p><p class="description">Sets the current application name.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 44</div>
<h3 id="action()">action</h3>

public  string **action** (string task, array params)<div class="details">
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

<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 58</div>
<h3 id="moduleAction()">moduleAction</h3>

public  string **moduleAction** (string module, string task, array params)<div class="details">
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

<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 73</div>
<h3 id="appAction()">appAction</h3>

public abstract  string **appAction** (string app, string module, string task, array params)<div class="details">
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

<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 80</div>
<h3 id="getBaseURL()">getBaseURL</h3>

public abstract  string **getBaseURL** ()<div class="details">
<p>Gets the current base URL.</p><dl>
<dt>Returns:</dt>
<dd>The current base URL</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 87</div>
<h3 id="redirect()">redirect</h3>

public abstract  void **redirect** (string url)<div class="details">
<p>Makes an HTTP redirect to the given absolute URL.</p><dl>
<dt>Parameters:</dt>
<dd>url - The absolute URL to make the redirection.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 94</div>
<h3 id="getModuleName()">getModuleName</h3>

public  string **getModuleName** ()<div class="details">
<p>Gets the current module name.</p><dl>
<dt>Returns:</dt>
<dd>The name of the current module.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 103</div>
<h3 id="setModuleName()">setModuleName</h3>

public  void **setModuleName** (string moduleName)<div class="details">
<p>Sets the current module name.</p><dl>
<dt>Parameters:</dt>
<dd>moduleName - The name of the module.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 112</div>
<h3 id="getAppName()">getAppName</h3>

public  string **getAppName** ()<div class="details">
<p>Gets the current application name.</p><dl>
<dt>Returns:</dt>
<dd>The current app name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Routing.php at line 121</div>
<h3 id="setAppName()">setAppName</h3>

public  void **setAppName** (string appName)<div class="details">
<p>Sets the current application name.</p><dl>
<dt>Parameters:</dt>
<dd>appName - The current application name.</dd>
</dl>
</div>

- - -

