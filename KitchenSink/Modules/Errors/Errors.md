

- - -

**KitchenSink\Modules\Errors\Errors**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/Errors/Errors.php#L16" target='_blank'>src\KitchenSink\Modules\Errors\Errors.php at line 16</a>

#Class Errors#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>
 &gt; **Errors**




- - -

<p><strong>public  class</strong> <span>Errors</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>

</p>

<div class="comment" id="overview_description"><p>This module is called in case of any exception. Or if a module is not found.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#context">context</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#currentuser">currentUser</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#headers">headers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#page">page</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#request">request</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#route">route</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#session">session</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#onerror">onError</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/TaskErrorEvent.md">TaskErrorEvent</a> e)</p><p class="description">This method is called when there is an exception.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#notfound">notFound</a>()</p><p class="description">This method is called when the requested module doesn't exist</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#addmessage">addMessage</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assignmany">assignMany</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#component">component</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#createmodulefromclassname">createModuleFromClassName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getappname">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getmoduledir">getModuleDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getname">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#gettask">getTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#onmoduleready">onModuleReady</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#redirect">redirect</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#setdefaulttask">setDefaultTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/Errors/Errors.php#L36" target='_blank'>src\KitchenSink\Modules\Errors\Errors.php at line 36</a>

<h3 id="onError()">onError</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>onError</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/TaskErrorEvent.md">TaskErrorEvent</a> e)

<div class="details">
<p>This method is called when there is an exception.</p><p>The Listen annotation tells to Hirudo that this method listens to
the "taskError" event.</p><p>The OverridesListener indicates that this listener overrides any virtual
listener with the id "error_listener". An event listener can be declared
as virtual which means that it can be overriden for other listeners instead
of being called along them.</p><p>The IgnoreCall annotation prevents this method from being called through
HTTP</p><dl>
<dt>Listen(to="taskError").</dt>
<dt>OverridesListener(id="error_listener").</dt>
<dt>IgnoreCall.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/Errors/Errors.php#L46" target='_blank'>src\KitchenSink\Modules\Errors\Errors.php at line 46</a>

<h3 id="notFound()">notFound</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>notFound</span> ()

<div class="details">
<p>This method is called when the requested module doesn't exist</p>
</div>

- - -

