

- - -

**Hirudo\Core\Events\Dispatcher\HirudoDispatcher**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.php#L20" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\HirudoDispatcher.php at line 20</a>

#Class HirudoDispatcher#

EventDispatcher &gt; **HirudoDispatcher**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/CachedHirudoDispatcher.md">CachedHirudoDispatcher</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/FileCachedHirudoDispatcher.md">FileCachedHirudoDispatcher</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>HirudoDispatcher</span>
<strong>extends</strong> EventDispatcher

</p>

<div class="comment" id="overview_description"><p>Description of HirudoDispatcher</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addlistener">addListener</a>(mixed eventName, mixed listener, int priority)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#subscribeobject">subscribeObject</a>(mixed object)</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadobjectlisteners">loadObjectListeners</a>(ReflectionClass reflectedObject, mixed object)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#removelistener">removeListener</a>(mixed eventName, mixed listener)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#dodispatch">doDispatch</a>(array[callback] listeners, string eventName, Event event)</p><p class="description">Triggers the listeners of an event.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.php#L33" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\HirudoDispatcher.php at line 33</a>

<h3 id="addListener()">addListener</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addListener</span> (mixed eventName, mixed listener, int priority)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd>EventDispatcherInterface::addListener</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.php#L56" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\HirudoDispatcher.php at line 56</a>

<h3 id="subscribeObject()">subscribeObject</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>subscribeObject</span> (mixed object)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.php#L67" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\HirudoDispatcher.php at line 67</a>

<h3 id="loadObjectListeners()">loadObjectListeners</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>loadObjectListeners</span> (ReflectionClass reflectedObject, mixed object)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.php#L86" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\HirudoDispatcher.php at line 86</a>

<h3 id="removeListener()">removeListener</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>removeListener</span> (mixed eventName, mixed listener)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd>EventDispatcherInterface::removeListener</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.php#L118" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\HirudoDispatcher.php at line 118</a>

<h3 id="doDispatch()">doDispatch</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>doDispatch</span> (array[callback] listeners, string eventName, Event event)

<div class="details">
<p>Triggers the listeners of an event.</p><p>This method can be overridden to add functionality that is executed
for each listener.</p><dl>
<dt>Parameters:</dt>
<dd>listeners - The event listeners.</dd>
<dd>eventName - The name of the event to dispatch.</dd>
<dd>event - The event object to pass to the event handlers/listeners.</dd>
</dl>

</div>

- - -

