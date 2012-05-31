
- - -

**Hirudo\Core\Module**
<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 109</div>
#Class Module#

**Module**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sampleapp/modules/errorpage.html">SampleApp\Modules\ErrorPage</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sampleapp/modules/frontpage.html">SampleApp\Modules\FrontPage</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sampleapp/modules/httptester.html">SampleApp\Modules\HttpTester</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sampleapp/modules/simplesqltest.html">SampleApp\Modules\SimpleSqlTest</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Module**</p>

<div class="comment" id="overview_description"><p>A module represents a single use case in the business logic.</p></div>


- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  <a href="../../hirudo/core/context/modulescontext.html">ModulesContext</a></td>
<td class="description"><p class="name"><a href="#context">$context</a></p><p class="description">An internal ModulesContext instance.</p></td>
</tr>
<tr>
<td class="type">protected  <a href="../../hirudo/core/context/principal.html">Principal</a></td>
<td class="description"><p class="name"><a href="#currentuser">$currentUser</a></p><p class="description">The current user of this session.</p></td>
</tr>
<tr>
<td class="type">protected  <a href="../../hirudo/core/headerbag.html">HeaderBag</a></td>
<td class="description"><p class="name"><a href="#headers">$headers</a></p><p class="description">An utility object for response header edition.</p></td>
</tr>
<tr>
<td class="type">protected  <a href="../../hirudo/core/context/request.html">Request</a></td>
<td class="description"><p class="name"><a href="#request">$request</a></p><p class="description">Gives access to the request arrays such as GET, POST or SESSION.</p></td>
</tr>
<tr>
<td class="type">protected  <a href="../../hirudo/core/context/routing.html">Routing</a></td>
<td class="description"><p class="name"><a href="#route">$route</a></p><p class="description">A helper class for managing urls.</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a module.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> protected  void</td>
<td class="description"><p class="name"><a href="#assign">assign</a>(string name, mixed value)</p><p class="description">Adds a variable to the view so it can access it via the name.</p></td>
</tr>
<tr>
<td class="type"> protected  void</td>
<td class="description"><p class="name"><a href="#assignmany">assignMany</a>(array array)</p><p class="description">Batch assign.</p></td>
</tr>
<tr>
<td class="type"> protected  mixed</td>
<td class="description"><p class="name"><a href="#component">component</a>(string name)</p><p class="description">Retreives a component instance.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../hirudo/core/task.html">Task</a></td>
<td class="description"><p class="name"><a href="#gettask">getTask</a>(string taskName)</p><p class="description">Builds a task from it's name. </p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#getrendered">getRendered</a>()</p><p class="description">Returns the result of the view rendering as a string.</p></td>
</tr>
<tr>
<td class="type"> protected  void</td>
<td class="description"><p class="name"><a href="#onmoduleready">onModuleReady</a>()</p><p class="description">This function is called before a task execution, is
useful for taking actions prior the execution of any task such as
initializing objects common to all tasks.</p></td>
</tr>
<tr>
<td class="type"> protected  void</td>
<td class="description"><p class="name"><a href="#display">display</a>(string view)</p><p class="description">Displays the given view to the browser.</p></td>
</tr>
<tr>
<td class="type"> protected  string</td>
<td class="description"><p class="name"><a href="#renderget">renderGet</a>(string view)</p><p class="description">Renders the given view and returns it as a string without sending it to
the browser.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#addmessage">addMessage</a>(<a href="../../hirudo/core/util/message.html">Message</a> message)</p><p class="description">Adds a message to the view which normally will be rendered as a notification.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setdefaulttask">setDefaultTask</a>(string defaultTask)</p><p class="description">Sets the name of the default task. </p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#getmoduledir">getModuleDir</a>(mixed appName, mixed name)</p><p class="description">Gets the directory in which this module is located.</p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#getname">getName</a>()</p><p class="description">Gets the module's name.</p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#getappname">getAppName</a>()</p><p class="description">Gets the name of the app this module belongs to.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setappname">setAppName</a>(string appName)</p><p class="description">Sets the name of the app this module belongs to.</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 180</div>
<h3 id="context">context</h3>

protected  <a href="../../hirudo/core/context/modulescontext.html">ModulesContext</a> $context
<div class="details">
<p>An internal ModulesContext instance.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 159</div>
<h3 id="currentUser">currentUser</h3>

protected  <a href="../../hirudo/core/context/principal.html">Principal</a> $currentUser
<div class="details">
<p>The current user of this session.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 187</div>
<h3 id="headers">headers</h3>

protected  <a href="../../hirudo/core/headerbag.html">HeaderBag</a> $headers
<div class="details">
<p>An utility object for response header edition.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 173</div>
<h3 id="request">request</h3>

protected  <a href="../../hirudo/core/context/request.html">Request</a> $request
<div class="details">
<p>Gives access to the request arrays such as GET, POST or SESSION.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 166</div>
<h3 id="route">route</h3>

protected  <a href="../../hirudo/core/context/routing.html">Routing</a> $route
<div class="details">
<p>A helper class for managing urls.</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 367</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**()
```
<div class="details">
<p>Creates a module.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 204</div>
<h3 id="assign()">assign</h3>

protected  void **assign** (string name, mixed value)<div class="details">
<p>Adds a variable to the view so it can access it via the name.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the variable.</dd>
<dd>value - The value of the variable.</dd>
<dt>See Also:</dt>
<dd>TemplatingInterface->assign()</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 213</div>
<h3 id="assignMany()">assignMany</h3>

protected  void **assignMany** (array array)<div class="details">
<p>Batch assign.</p><dl>
<dt>Parameters:</dt>
<dd>array - A list of key/value pairs where keys are the variable names.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 227</div>
<h3 id="component()">component</h3>

protected  mixed **component** (string name)<div class="details">
<p>Retreives a component instance.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the component in "ComponentName" or "AppName::ComponentName" format.</dd>
<dt>Returns:</dt>
<dd>The resulting component.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 257</div>
<h3 id="getTask()">getTask</h3>

public  <a href="../../hirudo/core/task.html">Task</a> **getTask** (string taskName)<div class="details">
<p>Builds a task from it's name. If the module doesn't have a corresponding
method, the default task is returned, normally the "index" task.</p><dl>
<dt>Parameters:</dt>
<dd>taskName - Thask's name.</dd>
<dt>Returns:</dt>
<dd>The representation of the task to be executed.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 277</div>
<h3 id="getRendered()">getRendered</h3>

public  string **getRendered** ()<div class="details">
<p>Returns the result of the view rendering as a string.</p><dl>
<dt>Returns:</dt>
<dd>The rendered view.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 286</div>
<h3 id="onModuleReady()">onModuleReady</h3>

protected  void **onModuleReady** ()<div class="details">
<p>This function is called before a task execution, is
useful for taking actions prior the execution of any task such as
initializing objects common to all tasks.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 318</div>
<h3 id="display()">display</h3>

protected  void **display** (string view)<div class="details">
<p><p>Displays the given view to the browser.</p></p><p><p>In adition to the data provided by the module, the view will have these
variables available.</p></p><p><dl>
<dt>Module</dt>
<dd>
An array with data about this module. The array consists of these
values:</p>
<ul>
<li>meta =&gt; The metadata asociated to this module. (MetadataCollection)</li>
<li>appName =&gt; The the name of the application this module belongs to.</li>
<li>name =&gt; The name of this module.</li>
<li>context =&gt; A reference to the ModulesContext instance.</li>
<li>views =&gt; The absolute path to the views folder for this module.</li>
<li>baseURL =&gt; The current base URL</li>
<li>messages =&gt; The list of added <code><a href="../../hirudo/core/util/message.html">Message</a></code> objects</li>
</ul>
<p></dd>
</dl></p><dl>
<dt>Parameters:</dt>
<dd>view - The view name. It can be just the view name if it belongs to the current module or a string with the "AppName::ModuleName::viewName" format if the view belongs to another module.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 330</div>
<h3 id="renderGet()">renderGet</h3>

protected  string **renderGet** (string view)<div class="details">
<p><p>Renders the given view and returns it as a string without sending it to
the browser.</p></p><dl>
<dt>Parameters:</dt>
<dd>view - The view name</dd>
<dt>Returns:</dt>
<dd>The result of the rendering.</dd>
<dt>See Also:</dt>
<dd>Module->display()</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 351</div>
<h3 id="addMessage()">addMessage</h3>

public  void **addMessage** (<a href="../../hirudo/core/util/message.html">Message</a> message)<div class="details">
<p>Adds a message to the view which normally will be rendered as a notification.</p><dl>
<dt>Parameters:</dt>
<dd>message - The message to be displayed.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 360</div>
<h3 id="setDefaultTask()">setDefaultTask</h3>

public  void **setDefaultTask** (string defaultTask)<div class="details">
<p>Sets the name of the default task. By default is "index".</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 405</div>
<h3 id="getModuleDir()">getModuleDir</h3>

public  string **getModuleDir** (mixed appName, mixed name)<div class="details">
<p>Gets the directory in which this module is located.</p><dl>
<dt>Returns:</dt>
<dd>The directory that contains this module.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 420</div>
<h3 id="getName()">getName</h3>

public  string **getName** ()<div class="details">
<p>Gets the module's name.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 429</div>
<h3 id="getAppName()">getAppName</h3>

public  string **getAppName** ()<div class="details">
<p>Gets the name of the app this module belongs to.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Module.php at line 438</div>
<h3 id="setAppName()">setAppName</h3>

public  void **setAppName** (string appName)<div class="details">
<p>Sets the name of the app this module belongs to.</p></div>

- - -

