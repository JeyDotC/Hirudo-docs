

- - -

**Hirudo\Core\Module**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L109" >framework\hirudo\Hirudo\Core\Module.php at line 109</a>

#Class Module#

**Module**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sampleapp/modules/ErrorPage.md">SampleApp\Modules\ErrorPage</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sampleapp/modules/FrontPage.md">SampleApp\Modules\FrontPage</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sampleapp/modules/HttpTester.md">SampleApp\Modules\HttpTester</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sampleapp/modules/SimpleSqlTest.md">SampleApp\Modules\SimpleSqlTest</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>Module</span></p>

<div class="comment" id="overview_description"><p>A module represents a single use case in the business logic.</p></div>



- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/ModulesContext'>ModulesContext</a></span></td>
<td class="description"><p class="name" ><a href="#context"> $context</a>
                                </p><p class="description">An internal ModulesContext instance.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/Principal'>Principal</a></span></td>
<td class="description"><p class="name" ><a href="#currentUser"> $currentUser</a>
                                </p><p class="description">The current user of this session.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/HeaderBag'>HeaderBag</a></span></td>
<td class="description"><p class="name" ><a href="#headers"> $headers</a>
                                </p><p class="description">An utility object for response header edition.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/Request'>Request</a></span></td>
<td class="description"><p class="name" ><a href="#request"> $request</a>
                                </p><p class="description">Gives access to the request arrays such as GET, POST or SESSION.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/Routing'>Routing</a></span></td>
<td class="description"><p class="name" ><a href="#route"> $route</a>
                                </p><p class="description">A helper class for managing urls.</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a module.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#assign">assign</a>(string name, mixed value)</p><p class="description">Adds a variable to the view so it can access it via the name.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#assignmany">assignMany</a>(array array)</p><p class="description">Batch assign.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#component">component</a>(string name)</p><p class="description">Retreives a component instance.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/Task>Task</a></span></td>
<td class="description"><p class="name"><a href="#gettask">getTask</a>(string taskName)</p><p class="description">Builds a task from it's name. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getrendered">getRendered</a>()</p><p class="description">Returns the result of the view rendering as a string.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#onmoduleready">onModuleReady</a>()</p><p class="description">This function is called before a task execution, is
useful for taking actions prior the execution of any task such as
initializing objects common to all tasks.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#display">display</a>(string view)</p><p class="description">Displays the given view to the browser.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#renderget">renderGet</a>(string view)</p><p class="description">Renders the given view and returns it as a string without sending it to
the browser.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addmessage">addMessage</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/util/Message.md">Message</a> message)</p><p class="description">Adds a message to the view which normally will be rendered as a notification.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setdefaulttask">setDefaultTask</a>(string defaultTask)</p><p class="description">Sets the name of the default task. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getmoduledir">getModuleDir</a>(mixed appName, mixed name)</p><p class="description">Gets the directory in which this module is located.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getname">getName</a>()</p><p class="description">Gets the module's name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getappname">getAppName</a>()</p><p class="description">Gets the name of the app this module belongs to.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setappname">setAppName</a>(string appName)</p><p class="description">Sets the name of the app this module belongs to.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L367" >framework\hirudo\Hirudo\Core\Module.php at line 367</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a module.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L204" >framework\hirudo\Hirudo\Core\Module.php at line 204</a>

<h3 id="assign()">assign</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>assign</span> (string name, mixed value)

<div class="details">
<p>Adds a variable to the view so it can access it via the name.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the variable.</dd>
<dd>value - The value of the variable.</dd>
<dt>See Also:</dt>
<dd>TemplatingInterface->assign()</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L213" >framework\hirudo\Hirudo\Core\Module.php at line 213</a>

<h3 id="assignMany()">assignMany</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>assignMany</span> (array array)

<div class="details">
<p>Batch assign.</p><dl>
<dt>Parameters:</dt>
<dd>array - A list of key/value pairs where keys are the variable names.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L227" >framework\hirudo\Hirudo\Core\Module.php at line 227</a>

<h3 id="component()">component</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span> <span class='nf'>component</span> (string name)

<div class="details">
<p>Retreives a component instance.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the component in "ComponentName" or "AppName::ComponentName" format.</dd>
<dt>Returns:</dt>
<dd>The resulting component.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L257" >framework\hirudo\Hirudo\Core\Module.php at line 257</a>

<h3 id="getTask()">getTask</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/Task>Task</a></span> <span class='nf'>getTask</span> (string taskName)

<div class="details">
<p>Builds a task from it's name. If the module doesn't have a corresponding
method, the default task is returned, normally the "index" task.</p><dl>
<dt>Parameters:</dt>
<dd>taskName - Thask's name.</dd>
<dt>Returns:</dt>
<dd>The representation of the task to be executed.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L277" >framework\hirudo\Hirudo\Core\Module.php at line 277</a>

<h3 id="getRendered()">getRendered</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getRendered</span> ()

<div class="details">
<p>Returns the result of the view rendering as a string.</p><dl>
<dt>Returns:</dt>
<dd>The rendered view.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L286" >framework\hirudo\Hirudo\Core\Module.php at line 286</a>

<h3 id="onModuleReady()">onModuleReady</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>onModuleReady</span> ()

<div class="details">
<p>This function is called before a task execution, is
useful for taking actions prior the execution of any task such as
initializing objects common to all tasks.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L318" >framework\hirudo\Hirudo\Core\Module.php at line 318</a>

<h3 id="display()">display</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>display</span> (string view)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L330" >framework\hirudo\Hirudo\Core\Module.php at line 330</a>

<h3 id="renderGet()">renderGet</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>renderGet</span> (string view)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L351" >framework\hirudo\Hirudo\Core\Module.php at line 351</a>

<h3 id="addMessage()">addMessage</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addMessage</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/util/Message.md">Message</a> message)

<div class="details">
<p>Adds a message to the view which normally will be rendered as a notification.</p><dl>
<dt>Parameters:</dt>
<dd>message - The message to be displayed.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L360" >framework\hirudo\Hirudo\Core\Module.php at line 360</a>

<h3 id="setDefaultTask()">setDefaultTask</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setDefaultTask</span> (string defaultTask)

<div class="details">
<p>Sets the name of the default task. By default is "index".</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L405" >framework\hirudo\Hirudo\Core\Module.php at line 405</a>

<h3 id="getModuleDir()">getModuleDir</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getModuleDir</span> (mixed appName, mixed name)

<div class="details">
<p>Gets the directory in which this module is located.</p><dl>
<dt>Returns:</dt>
<dd>The directory that contains this module.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L420" >framework\hirudo\Hirudo\Core\Module.php at line 420</a>

<h3 id="getName()">getName</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getName</span> ()

<div class="details">
<p>Gets the module's name.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L429" >framework\hirudo\Hirudo\Core\Module.php at line 429</a>

<h3 id="getAppName()">getAppName</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getAppName</span> ()

<div class="details">
<p>Gets the name of the app this module belongs to.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Module.php#L438" >framework\hirudo\Hirudo\Core\Module.php at line 438</a>

<h3 id="setAppName()">setAppName</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setAppName</span> (string appName)

<div class="details">
<p>Sets the name of the app this module belongs to.</p>
</div>

- - -

