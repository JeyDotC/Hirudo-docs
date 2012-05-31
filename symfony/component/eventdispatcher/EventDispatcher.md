- - -

**Symfony\Component\EventDispatcher\EventDispatcher**
<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 29</div>
#Class EventDispatcher#

**EventDispatcher**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/modulesmanager.html">Hirudo\Core\ModulesManager</a> </dd>
</dl>

- - -

<p class="signature">public  class **EventDispatcher**</p>

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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#dispatch">dispatch</a>(mixed eventName, <a href="../../../symfony/component/eventdispatcher/event.html">Event</a> event)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getListeners">getListeners</a>(mixed eventName)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#hasListeners">hasListeners</a>(mixed eventName)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addListener">addListener</a>(mixed eventName, mixed listener, int priority)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#removeListener">removeListener</a>(mixed eventName, mixed listener)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addSubscriber">addSubscriber</a>(<a href="../../../symfony/component/eventdispatcher/eventsubscriberinterface.html">EventSubscriberInterface</a> subscriber)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#removeSubscriber">removeSubscriber</a>(<a href="../../../symfony/component/eventdispatcher/eventsubscriberinterface.html">EventSubscriberInterface</a> subscriber)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#doDispatch">doDispatch</a>(array[callback] listeners, string eventName, <a href="../../../symfony/component/eventdispatcher/event.html">Event</a> event)</p><p class="description">Triggers the listeners of an event.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 39</div>
<h3 id="dispatch()">dispatch</h3>
```php
public  void **dispatch**(mixed eventName, <a href="../../../symfony/component/eventdispatcher/event.html">Event</a> event)```
<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#dispatch()">EventDispatcherInterface::dispatch</a></dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 54</div>
<h3 id="getListeners()">getListeners</h3>
```php
public  void **getListeners**(mixed eventName)```
<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#getListeners()">EventDispatcherInterface::getListeners</a></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 75</div>
<h3 id="hasListeners()">hasListeners</h3>
```php
public  void **hasListeners**(mixed eventName)```
<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#hasListeners()">EventDispatcherInterface::hasListeners</a></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 84</div>
<h3 id="addListener()">addListener</h3>
```php
public  void **addListener**(mixed eventName, mixed listener, int priority)```
<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#addListener()">EventDispatcherInterface::addListener</a></dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 92</div>
<h3 id="removeListener()">removeListener</h3>
```php
public  void **removeListener**(mixed eventName, mixed listener)```
<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#removeListener()">EventDispatcherInterface::removeListener</a></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 109</div>
<h3 id="addSubscriber()">addSubscriber</h3>
```php
public  void **addSubscriber**(<a href="../../../symfony/component/eventdispatcher/eventsubscriberinterface.html">EventSubscriberInterface</a> subscriber)```
<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#addSubscriber()">EventDispatcherInterface::addSubscriber</a></dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 122</div>
<h3 id="removeSubscriber()">removeSubscriber</h3>
```php
public  void **removeSubscriber**(<a href="../../../symfony/component/eventdispatcher/eventsubscriberinterface.html">EventSubscriberInterface</a> subscriber)```
<div class="details">
<p></p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/eventdispatcherinterface.html#removeSubscriber()">EventDispatcherInterface::removeSubscriber</a></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcher.php at line 138</div>
<h3 id="doDispatch()">doDispatch</h3>
```php
protected  void **doDispatch**(array[callback] listeners, string eventName, <a href="../../../symfony/component/eventdispatcher/event.html">Event</a> event)```
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

