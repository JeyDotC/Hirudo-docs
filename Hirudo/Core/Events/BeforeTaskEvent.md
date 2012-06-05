

- - -

**Hirudo\Core\Events\BeforeTaskEvent**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/BeforeTaskEvent.php#L34" target='_blank'>framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 34</a>

#Class BeforeTaskEvent#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/EventDispatcher/Event.md">Event</a>
 &gt; **BeforeTaskEvent**




- - -

<p><strong>public  class</strong> <span>BeforeTaskEvent</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/EventDispatcher/Event.md">Event</a>

</p>

<div class="comment" id="overview_description"><p>This event is triggered before a task is executed and after it's requirements
are resolved.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>See Also:</dt>
<dd><code>www.doctrine-project.org</code></dd>
<dt>Since:</dt>
<dd>2.0</dd>
<dt>Version:</dt>
<dd>$Revision: 3938 $</dd>
<dt>Api.</dt>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setparam">setParam</a>(string name, mixed value)</p><p class="description">Sets or replaces a task's param value.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getparam">getParam</a>(string name)</p><p class="description">Gets a task's parameter value.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#replacecall">replaceCall</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModuleCall.md">ModuleCall</a> call)</p><p class="description">Replaces the call to be executed thus restarting the module execution
process to work acordingly to the new ModuleCall.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEvent.md#getcall>ModuleCall</a></span></td>
<td class="description"><p class="name"><a href="#getcall">getCall</a>()</p><p class="description">Gets the current call.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#getcallreplaced">getCallReplaced</a>()</p><p class="description">Says if the call has been replaced. </p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\EventDispatcher\Event</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/EventDispatcher/Event.md#ispropagationstopped">isPropagationStopped</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/EventDispatcher/Event.md#stoppropagation">stopPropagation</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/BeforeTaskEvent.php#L47" target='_blank'>framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 47</a>

<h3 id="setParam()">setParam</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setParam</span> (string name, mixed value)

<div class="details">
<p>Sets or replaces a task's param value.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the parameter.</dd>
<dd>value - The new parameter value.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/BeforeTaskEvent.php#L58" target='_blank'>framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 58</a>

<h3 id="getParam()">getParam</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getParam</span> (string name)

<div class="details">
<p>Gets a task's parameter value.</p><dl>
<dt>Parameters:</dt>
<dd>name - The task's parameter name</dd>
<dt>Returns:</dt>
<dd>The value of the parameter.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/BeforeTaskEvent.php#L68" target='_blank'>framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 68</a>

<h3 id="replaceCall()">replaceCall</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>replaceCall</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModuleCall.md">ModuleCall</a> call)

<div class="details">
<p>Replaces the call to be executed thus restarting the module execution
process to work acordingly to the new ModuleCall.</p><dl>
<dt>Parameters:</dt>
<dd>call - The new call to be executed.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/BeforeTaskEvent.php#L78" target='_blank'>framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 78</a>

<h3 id="getCall()">getCall</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEvent.md#getcall>ModuleCall</a></span> <span class='nf'>getCall</span> ()

<div class="details">
<p>Gets the current call.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/BeforeTaskEvent.php#L88" target='_blank'>framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 88</a>

<h3 id="getCallReplaced()">getCallReplaced</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>getCallReplaced</span> ()

<div class="details">
<p>Says if the call has been replaced. This is true when the
replaceCall method has been called.</p><dl>
<dt>Returns:</dt>
<dd>True if the call have been replaced, false otherwise.</dd>
</dl>

</div>

- - -

