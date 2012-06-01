

- - -

**Symfony\Component\EventDispatcher\Event**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/Event.php#L33" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\Event.php at line 33</a>

#Class Event#

**Event**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/events/BeforeTaskEvent.md">Hirudo\Core\Events\BeforeTaskEvent</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Event</span></p>

<div class="comment" id="overview_description"><p>Event is the base class for classes containing event data.</p><p>This class contains no event data. It is used by events that do not pass
state information to an event handler when an event is raised.</p><p>You can call the method stopPropagation() to abort the execution of
further listeners in your event listener.</p></div>

<dl>
<dt>See Also:</dt>
<dd><code>www.doctrine-project.org</code></dd>
<dt>Since:</dt>
<dd>2.0</dd>
<dt>Version:</dt>
<dd>$Revision: 3938 $</dd>
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
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#ispropagationstopped">isPropagationStopped</a>()</p><p class="description">Returns whether further event listeners should be triggered.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#stoppropagation">stopPropagation</a>()</p><p class="description">Stops the propagation of the event to further event listeners.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/Event.php#L48" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\Event.php at line 48</a>

<h3 id="isPropagationStopped()">isPropagationStopped</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>isPropagationStopped</span> ()

<div class="details">
<p>Returns whether further event listeners should be triggered.</p><dl>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/eventdispatcher/event.html#stopPropagation()">Event::stopPropagation</a></dd>
<dt>Returns:</dt>
<dd>Whether propagation was already stopped for this event.</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/EventDispatcher/Event.php#L62" >framework\libs\symfony-components\Symfony\Component\EventDispatcher\Event.php at line 62</a>

<h3 id="stopPropagation()">stopPropagation</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>stopPropagation</span> ()

<div class="details">
<p>Stops the propagation of the event to further event listeners.</p><p>If multiple event listeners are connected to the same event, no
further event listener will be triggered once any trigger calls
stopPropagation().</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -

