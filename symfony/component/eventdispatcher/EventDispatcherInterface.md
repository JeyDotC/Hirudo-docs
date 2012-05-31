- - -

**Symfony\Component\EventDispatcher\EventDispatcherInterface**
<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcherInterface.php at line 23</div>
#Interface EventDispatcherInterface#

**EventDispatcherInterface**


- - -

<p class="signature">public  interface **EventDispatcherInterface**</p>

<div class="comment" id="overview_description"><p>The EventDispatcherInterface is the central point of Symfony's event listener system.
Listeners are registered on the manager and events are dispatched through the
manager.</p></div>

<dl>
<dt>Author:</dt>
<dd>Bernhard Schussek <bschussek@gmail.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#dispatch">dispatch</a>(string eventName, <a href="../../../symfony/component/eventdispatcher/event.html">Event</a> event)</p><p class="description">Dispatches an event to all registered listeners.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addListener">addListener</a>(string eventName, callable listener, integer priority)</p><p class="description">Adds an event listener that listens on the specified events.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addSubscriber">addSubscriber</a>(<a href="../../../symfony/component/eventdispatcher/eventsubscriberinterface.html">EventSubscriberInterface</a> subscriber)</p><p class="description">Adds an event subscriber. </p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#removeListener">removeListener</a>(string|array eventName, object listener)</p><p class="description">Removes an event listener from the specified events.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#removeSubscriber">removeSubscriber</a>(<a href="../../../symfony/component/eventdispatcher/eventsubscriberinterface.html">EventSubscriberInterface</a> subscriber)</p><p class="description">Removes an event subscriber.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getListeners">getListeners</a>(string eventName)</p><p class="description">Gets the listeners of a specific event or all listeners.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#hasListeners">hasListeners</a>(string eventName)</p><p class="description">Checks whether an event has any registered listeners.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcherInterface.php at line 36</div>
<h3 id="dispatch()">dispatch</h3>
```php
public  void **dispatch**(string eventName, <a href="../../../symfony/component/eventdispatcher/event.html">Event</a> event)```
<div class="details">
<p>Dispatches an event to all registered listeners.</p><dl>
<dt>Parameters:</dt>
<dd>eventName - The name of the event to dispatch. The name of the event is the name of the method that is invoked on listeners.</dd>
<dd>event - The event to pass to the event handlers/listeners. If not supplied, an empty Event instance is created.</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcherInterface.php at line 48</div>
<h3 id="addListener()">addListener</h3>
```php
public  void **addListener**(string eventName, callable listener, integer priority)```
<div class="details">
<p>Adds an event listener that listens on the specified events.</p><dl>
<dt>Parameters:</dt>
<dd>eventName - The event to listen on</dd>
<dd>listener - The listener</dd>
<dd>priority - The higher this value, the earlier an event listener will be triggered in the chain (defaults to 0)</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcherInterface.php at line 58</div>
<h3 id="addSubscriber()">addSubscriber</h3>
```php
public  void **addSubscriber**(<a href="../../../symfony/component/eventdispatcher/eventsubscriberinterface.html">EventSubscriberInterface</a> subscriber)```
<div class="details">
<p>Adds an event subscriber. The subscriber is asked for all the events he is
interested in and added as a listener for these events.</p><dl>
<dt>Parameters:</dt>
<dd>subscriber - The subscriber.</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcherInterface.php at line 66</div>
<h3 id="removeListener()">removeListener</h3>
```php
public  void **removeListener**(string|array eventName, object listener)```
<div class="details">
<p>Removes an event listener from the specified events.</p><dl>
<dt>Parameters:</dt>
<dd>eventName - The event(s) to remove a listener from.</dd>
<dd>listener - The listener object to remove.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcherInterface.php at line 73</div>
<h3 id="removeSubscriber()">removeSubscriber</h3>
```php
public  void **removeSubscriber**(<a href="../../../symfony/component/eventdispatcher/eventsubscriberinterface.html">EventSubscriberInterface</a> subscriber)```
<div class="details">
<p>Removes an event subscriber.</p><dl>
<dt>Parameters:</dt>
<dd>subscriber - The subscriber.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcherInterface.php at line 83</div>
<h3 id="getListeners()">getListeners</h3>
```php
public  array **getListeners**(string eventName)```
<div class="details">
<p>Gets the listeners of a specific event or all listeners.</p><dl>
<dt>Parameters:</dt>
<dd>eventName - The name of the event.</dd>
<dt>Returns:</dt>
<dd>The event listeners for the specified event, or all event listeners by event name.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventDispatcherInterface.php at line 93</div>
<h3 id="hasListeners()">hasListeners</h3>
```php
public  Boolean **hasListeners**(string eventName)```
<div class="details">
<p>Checks whether an event has any registered listeners.</p><dl>
<dt>Parameters:</dt>
<dd>eventName - The name of the event.</dd>
<dt>Returns:</dt>
<dd>TRUE if the specified event has any listeners, FALSE otherwise.</dd>
</dl>
</div>

- - -
