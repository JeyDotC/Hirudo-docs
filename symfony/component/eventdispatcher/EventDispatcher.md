

- - -

**Symfony\Component\EventDispatcher\EventDispatcher**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L29" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 29</a>

#Class EventDispatcher#

**EventDispatcher**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/ModulesManager.md">Hirudo\Core\ModulesManager</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>EventDispatcher</span></p>

<div class="comment" id="overview_description"><p>The EventDispatcherInterface is the central point of Symfony's event listener system.</p><p>Listeners are registered on the manager and events are dispatched through the
manager.</p></div>

<dl>
<dt>Author:</dt>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
<dd>Bernhard Schussek <bschussek@gmail.com></dd>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dd>Jordi Boggiano <j.boggiano@seld.be></dd>
<dt>Api.</dt>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#dispatch">dispatch</a>(mixed eventName, <a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/eventdispatcher/Event.md">Event</a> event)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getlisteners">getListeners</a>(mixed eventName)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#haslisteners">hasListeners</a>(mixed eventName)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addlistener">addListener</a>(mixed eventName, mixed listener, int priority)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#removelistener">removeListener</a>(mixed eventName, mixed listener)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addsubscriber">addSubscriber</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/eventdispatcher/EventSubscriberInterface.md">EventSubscriberInterface</a> subscriber)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#removesubscriber">removeSubscriber</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/eventdispatcher/EventSubscriberInterface.md">EventSubscriberInterface</a> subscriber)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#dodispatch">doDispatch</a>(array[callback] listeners, string eventName, <a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/eventdispatcher/Event.md">Event</a> event)</p><p class="description">Triggers the listeners of an event.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L39" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 39</a>

<h3 id="dispatch()">dispatch</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>dispatch</span> (mixed eventName, <a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/eventdispatcher/Event.md">Event</a> event)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#dispatch()">EventDispatcherInterface::dispatch</a></dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L54" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 54</a>

<h3 id="getListeners()">getListeners</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getListeners</span> (mixed eventName)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#getListeners()">EventDispatcherInterface::getListeners</a></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L75" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 75</a>

<h3 id="hasListeners()">hasListeners</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>hasListeners</span> (mixed eventName)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#hasListeners()">EventDispatcherInterface::hasListeners</a></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L84" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 84</a>

<h3 id="addListener()">addListener</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addListener</span> (mixed eventName, mixed listener, int priority)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#addListener()">EventDispatcherInterface::addListener</a></dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L92" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 92</a>

<h3 id="removeListener()">removeListener</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>removeListener</span> (mixed eventName, mixed listener)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#removeListener()">EventDispatcherInterface::removeListener</a></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L109" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 109</a>

<h3 id="addSubscriber()">addSubscriber</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addSubscriber</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/eventdispatcher/EventSubscriberInterface.md">EventSubscriberInterface</a> subscriber)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#addSubscriber()">EventDispatcherInterface::addSubscriber</a></dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L122" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 122</a>

<h3 id="removeSubscriber()">removeSubscriber</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>removeSubscriber</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/eventdispatcher/EventSubscriberInterface.md">EventSubscriberInterface</a> subscriber)

<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#removeSubscriber()">EventDispatcherInterface::removeSubscriber</a></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/EventDispatcher.php#L138" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 138</a>

<h3 id="doDispatch()">doDispatch</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>doDispatch</span> (array[callback] listeners, string eventName, <a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/eventdispatcher/Event.md">Event</a> event)

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

