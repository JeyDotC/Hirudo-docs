

- - -

**Hirudo\Core\Module**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L125" target='_blank'>framework\Hirudo\Core\Module.php at line 125</a>

#Class Module#

**Module**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Modules/ApiModule/ApiModule.md">KitchenSink\Modules\ApiModule\ApiModule</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Modules/CrudModule/CrudModule.md">KitchenSink\Modules\CrudModule\CrudModule</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Modules/Errors/Errors.md">KitchenSink\Modules\Errors\Errors</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Modules/EventListening/EventListening.md">KitchenSink\Modules\EventListening\EventListening</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Modules/Welcome/Welcome.md">KitchenSink\Modules\Welcome\Welcome</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>Module</span></p>

<div class="comment" id="overview_description"><p>A module represents a single use case in the business logic.</p></div>



<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md'>ModulesContext</a></span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#context"> $context</a>
                                </p><p class="description">An internal ModulesContext instance.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>Context\Principal</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#currentuser"> $currentUser</a>
                                </p><p class="description">The current user of this session.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/HeaderBag.md'>HeaderBag</a></span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#headers"> $headers</a>
                                </p><p class="description">An utility object for response header edition.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>Context\Page</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#page"> $page</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Request.md'>Request</a></span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#request"> $request</a>
                                </p><p class="description">Gives access to the request arrays such as GET, POST or SESSION.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md'>Routing</a></span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#route"> $route</a>
                                </p><p class="description">A helper class for managing urls.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Session.md'>Session</a></span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#session"> $session</a>
                                </p><p class="description"></p></td>
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
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Task.md>Task</a></span></td>
<td class="description"><p class="name"><a href="#gettask">getTask</a>(string taskName)</p><p class="description">Builds a task from it's name. </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#onmoduleready">onModuleReady</a>()</p><p class="description">This function is called before a task execution, is
useful for taking actions prior the execution of any task such as
initializing objects common to all tasks.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#display">display</a>(string view, mixed data)</p><p class="description">Displays the given view to the browser.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addmessage">addMessage</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Util/Message.md">Message</a> message)</p><p class="description">Adds a message to the view which normally will be rendered as a notification.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setdefaulttask">setDefaultTask</a>(string defaultTask)</p><p class="description">Sets the name of the default task. </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#createmodulefromclassname">createModuleFromClassName</a>(string className)</p><p class="description">I don't trust PHP constructors anymore ¬¬</p></td>
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
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#redirect">redirect</a>(mixed url)</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L189" target='_blank'>framework\Hirudo\Core\Module.php at line 189</a>

<h3 id="context">context</h3>
<span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md'>ModulesContext</a></span><span class='no'> $context</span><div class="details">
<p>An internal ModulesContext instance.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L168" target='_blank'>framework\Hirudo\Core\Module.php at line 168</a>

<h3 id="currentUser">currentUser</h3>
<span class='k'>protected </span> <span class='nx'>Context\Principal</span><span class='no'> $currentUser</span><div class="details">
<p>The current user of this session.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L196" target='_blank'>framework\Hirudo\Core\Module.php at line 196</a>

<h3 id="headers">headers</h3>
<span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/HeaderBag.md'>HeaderBag</a></span><span class='no'> $headers</span><div class="details">
<p>An utility object for response header edition.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L208" target='_blank'>framework\Hirudo\Core\Module.php at line 208</a>

<h3 id="page">page</h3>
<span class='k'>protected </span> <span class='nx'>Context\Page</span><span class='no'> $page</span><div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L182" target='_blank'>framework\Hirudo\Core\Module.php at line 182</a>

<h3 id="request">request</h3>
<span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Request.md'>Request</a></span><span class='no'> $request</span><div class="details">
<p>Gives access to the request arrays such as GET, POST or SESSION.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L175" target='_blank'>framework\Hirudo\Core\Module.php at line 175</a>

<h3 id="route">route</h3>
<span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Routing.md'>Routing</a></span><span class='no'> $route</span><div class="details">
<p>A helper class for managing urls.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L202" target='_blank'>framework\Hirudo\Core\Module.php at line 202</a>

<h3 id="session">session</h3>
<span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Session.md'>Session</a></span><span class='no'> $session</span><div class="details">
<p></p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L231" target='_blank'>framework\Hirudo\Core\Module.php at line 231</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L240" target='_blank'>framework\Hirudo\Core\Module.php at line 240</a>

<h3 id="assignMany()">assignMany</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>assignMany</span> (array array)

<div class="details">
<p>Batch assign.</p><dl>
<dt>Parameters:</dt>
<dd>array - A list of key/value pairs where keys are the variable names.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L254" target='_blank'>framework\Hirudo\Core\Module.php at line 254</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L284" target='_blank'>framework\Hirudo\Core\Module.php at line 284</a>

<h3 id="getTask()">getTask</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Task.md>Task</a></span> <span class='nf'>getTask</span> (string taskName)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L304" target='_blank'>framework\Hirudo\Core\Module.php at line 304</a>

<h3 id="onModuleReady()">onModuleReady</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>onModuleReady</span> ()

<div class="details">
<p>This function is called before a task execution, is
useful for taking actions prior the execution of any task such as
initializing objects common to all tasks.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L336" target='_blank'>framework\Hirudo\Core\Module.php at line 336</a>

<h3 id="display()">display</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>display</span> (string view, mixed data)

<div class="details">
<p><p>Displays the given view to the browser.</p></p><p><p>In adition to the data provided by the module, the view will have these
variables available.</p></p><p><dl>
<dt>Module</dt>
<dd>
An array with data about this module. The array consists of these
values:</p>
<ul>
<li>appName =&gt; The the name of the application this module belongs to.</li>
<li>name =&gt; The name of this module.</li>
<li>task =&gt; The task that have been requested.</li>
<li>context =&gt; A reference to the ModulesContext instance.</li>
<li>views =&gt; The absolute path to the views folder for this module. [This value seems to be unnecesary, is left for historical reasons]</li>
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L359" target='_blank'>framework\Hirudo\Core\Module.php at line 359</a>

<h3 id="addMessage()">addMessage</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addMessage</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Util/Message.md">Message</a> message)

<div class="details">
<p>Adds a message to the view which normally will be rendered as a notification.</p><dl>
<dt>Parameters:</dt>
<dd>message - The message to be displayed.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L368" target='_blank'>framework\Hirudo\Core\Module.php at line 368</a>

<h3 id="setDefaultTask()">setDefaultTask</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setDefaultTask</span> (string defaultTask)

<div class="details">
<p>Sets the name of the default task. By default is "index".</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L377" target='_blank'>framework\Hirudo\Core\Module.php at line 377</a>

<h3 id="createModuleFromClassName()">createModuleFromClassName</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>createModuleFromClassName</span> (string className)

<div class="details">
<p>I don't trust PHP constructors anymore ¬¬</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L437" target='_blank'>framework\Hirudo\Core\Module.php at line 437</a>

<h3 id="getModuleDir()">getModuleDir</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getModuleDir</span> (mixed appName, mixed name)

<div class="details">
<p>Gets the directory in which this module is located.</p><dl>
<dt>Returns:</dt>
<dd>The directory that contains this module.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L447" target='_blank'>framework\Hirudo\Core\Module.php at line 447</a>

<h3 id="getName()">getName</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getName</span> ()

<div class="details">
<p>Gets the module's name.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L456" target='_blank'>framework\Hirudo\Core\Module.php at line 456</a>

<h3 id="getAppName()">getAppName</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getAppName</span> ()

<div class="details">
<p>Gets the name of the app this module belongs to.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Module.php#L460" target='_blank'>framework\Hirudo\Core\Module.php at line 460</a>

<h3 id="redirect()">redirect</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>redirect</span> (mixed url)

<div class="details">

</div>

- - -

