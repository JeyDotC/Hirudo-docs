
- - -

**Symfony\Component\EventDispatcher\EventSubscriberInterface**
<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventSubscriberInterface.php at line 29</div>
#Interface EventSubscriberInterface#

**EventSubscriberInterface**


- - -

<p class="signature">public  interface **EventSubscriberInterface**</p>

<div class="comment" id="overview_description"><p>An EventSubscriber knows himself what events he is interested in.
If an EventSubscriber is added to an EventDispatcherInterface, the manager invokes
<code><a href="../../../hirudo/core/events/beforetaskeventlistener.html#getSubscribedEvents()">getSubscribedEvents</a></code> and registers the subscriber as a listener for all
returned events.</p></div>

<dl>
<dt>See Also:</dt>
<dd><code>www.doctrine-project.org</code></dd>
<dt>Since:</dt>
<dd>2.0</dd>
<dt>Author:</dt>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
<dd>Bernhard Schussek <bschussek@gmail.com></dd>
<dt>Api.</dt>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> static  array</td>
<td class="description"><p class="name"><a href="#getsubscribedevents">getSubscribedEvents</a>()</p><p class="description">Returns an array of event names this subscriber wants to listen to.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\EventDispatcher\EventSubscriberInterface.php at line 48</div>
<h3 id="getSubscribedEvents()">getSubscribedEvents</h3>

public static  array **getSubscribedEvents** ()<div class="details">
<p>Returns an array of event names this subscriber wants to listen to.</p><p>The array keys are event names and the value can be:</p><p>* The method name to call (priority defaults to 0)
* An array composed of the method name to call and the priority</p><p>For instance:</p><p>* array('eventName' => 'methodName')
* array('eventName' => array('methodName', $priority))</p><dl>
<dt>Returns:</dt>
<dd>The event names to listen to</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

