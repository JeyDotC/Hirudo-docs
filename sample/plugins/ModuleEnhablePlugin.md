- - -

**Sample\Plugins\ModuleEnhablePlugin**
<div class="location">ext\libs\SampleExtension\Sample\Plugins\ModuleEnhablePlugin.php at line 15</div>
#Class ModuleEnhablePlugin#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/events/beforetaskeventlistener.html">BeforeTaskEventListener</a>
    ***ModuleEnhablePlugin**


- - -

<p class="signature">public  class **ModuleEnhablePlugin**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/events/beforetaskeventlistener.html">BeforeTaskEventListener</a>

</p>

<div class="comment" id="overview_description"><p>Description of ModuleEnhablePlugin</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#beforeTask">beforeTask</a>(<a href="../../hirudo/core/events/beforetaskevent.html">BeforeTaskEvent</a> e)</p><p class="description">This is the method that needs to be implemented by the event listener in
order to work. </p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Events\BeforeTaskEventListener</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/events/beforetaskeventlistener.html#beforeTask()">beforeTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/events/beforetaskeventlistener.html#getSubscribedEvents()">getSubscribedEvents</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/events/beforetaskeventlistener.html#onBeforeTask()">onBeforeTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">ext\libs\SampleExtension\Sample\Plugins\ModuleEnhablePlugin.php at line 17</div>
<h3 id="beforeTask()">beforeTask</h3>
```php
protected  void **beforeTask**(<a href="../../hirudo/core/events/beforetaskevent.html">BeforeTaskEvent</a> e)```
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
