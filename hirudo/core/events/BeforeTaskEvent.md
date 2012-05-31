- - -

**Hirudo\Core\Events\BeforeTaskEvent**
<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 34</div>
#Class BeforeTaskEvent#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/event.html">Event</a>
    ***BeforeTaskEvent**


- - -

<p class="signature">public  class **BeforeTaskEvent**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/event.html">Event</a>

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
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setParam">setParam</a>(string name, mixed value)</p><p class="description">Sets or replaces a task's param value.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getParam">getParam</a>(string name)</p><p class="description">Gets a task's parameter value.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#replaceCall">replaceCall</a>(<a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> call)</p><p class="description">Replaces the call to be executed thus restarting the module execution
process to work acordingly to the new ModuleCall.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a></td>
<td class="description"><p class="name"><a href="#getCall">getCall</a>()</p><p class="description">Gets the current call.</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#getCallReplaced">getCallReplaced</a>()</p><p class="description">Says if the call has been replaced. </p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\EventDispatcher\Event</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/event.html#isPropagationStopped()">isPropagationStopped</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/event.html#stopPropagation()">stopPropagation</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 47</div>
<h3 id="setParam()">setParam</h3>
```php
public  void **setParam**(string name, mixed value)```
<div class="details">
<p>Sets or replaces a task's param value.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the parameter.</dd>
<dd>value - The new parameter value.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 58</div>
<h3 id="getParam()">getParam</h3>
```php
public  mixed **getParam**(string name)```
<div class="details">
<p>Gets a task's parameter value.</p><dl>
<dt>Parameters:</dt>
<dd>name - The task's parameter name</dd>
<dt>Returns:</dt>
<dd>The value of the parameter.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 68</div>
<h3 id="replaceCall()">replaceCall</h3>
```php
public  void **replaceCall**(<a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> call)```
<div class="details">
<p>Replaces the call to be executed thus restarting the module execution
process to work acordingly to the new ModuleCall.</p><dl>
<dt>Parameters:</dt>
<dd>call - The new call to be executed.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 78</div>
<h3 id="getCall()">getCall</h3>
```php
public  <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> **getCall**()```
<div class="details">
<p>Gets the current call.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEvent.php at line 88</div>
<h3 id="getCallReplaced()">getCallReplaced</h3>
```php
public  boolean **getCallReplaced**()```
<div class="details">
<p>Says if the call has been replaced. This is true when the
replaceCall method has been called.</p><dl>
<dt>Returns:</dt>
<dd>True if the call have been replaced, false otherwise.</dd>
</dl>
</div>

- - -

