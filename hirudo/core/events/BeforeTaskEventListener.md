- - -

**Hirudo\Core\Events\BeforeTaskEventListener**
<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEventListener.php at line 37</div>
#Class BeforeTaskEventListener#

**BeforeTaskEventListener**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/sample/plugins/moduleenhableplugin.html">Sample\Plugins\ModuleEnhablePlugin</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **BeforeTaskEventListener**</p>

<div class="comment" id="overview_description"><p><p>Listens to the BeforeTaskEvent which iccurs before the task is executed and after
the task's requirements are satisfied.</p></p><p><p>The listener only needs to implement the beforeTask method in order to work.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#getSubscribedEvents">getSubscribedEvents</a>()</p><p class="description">Subscribes this event listener to the BeforeTaskEvent.</p></td>
</tr>
<tr>
<td class="type">protected abstract  void</td>
<td class="description"><p class="name"><a href="#beforeTask">beforeTask</a>(<a href="../../../hirudo/core/events/beforetaskevent.html">BeforeTaskEvent</a> e)</p><p class="description">This is the method that needs to be implemented by the event listener in
order to work. </p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#onBeforeTask">onBeforeTask</a>(<a href="../../../hirudo/core/events/beforetaskevent.html">BeforeTaskEvent</a> e)</p><p class="description">A wraper function for the beforeTask method. </p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEventListener.php at line 45</div>
<h3 id="getSubscribedEvents()">getSubscribedEvents</h3>
```php
public static  array **getSubscribedEvents**()```
<div class="details">
<p>Subscribes this event listener to the BeforeTaskEvent.</p><dl>
<dt>Returns:</dt>
<dd>An array indicating to the event dispatcher which events will it listen to and which method will manage the event.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEventListener.php at line 60</div>
<h3 id="beforeTask()">beforeTask</h3>
```php
protected abstract  void **beforeTask**(<a href="../../../hirudo/core/events/beforetaskevent.html">BeforeTaskEvent</a> e)```
<div class="details">
<p>This is the method that needs to be implemented by the event listener in
order to work. This method is invoked before the current task is executed
and has the posibility to change the parameters values and to raplace the
current call, thus restarting the task call process for the new ModuleCall.</p><dl>
<dt>Parameters:</dt>
<dd>e - The event with the information about the current call.</dd>
<dt>See Also:</dt>
<dd><a href="../../hirudo/core/events/beforetaskevent.html">BeforeTaskEvent</a></dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Events\BeforeTaskEventListener.php at line 70</div>
<h3 id="onBeforeTask()">onBeforeTask</h3>
```php
public  void **onBeforeTask**(<a href="../../../hirudo/core/events/beforetaskevent.html">BeforeTaskEvent</a> e)```
<div class="details">
<p>A wraper function for the beforeTask method. This method checks the annotations
associated to the event listener.</p><dl>
<dt>See Also:</dt>
<dd>Annotations\ForCall</dd>
</dl>
</div>

- - -

