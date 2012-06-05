

- - -

**Sample\Plugins\ModuleEnhablePlugin**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ext/libs/SampleExtension/Sample/Plugins/ModuleEnhablePlugin.php#L15" target='_blank'>ext\libs\SampleExtension\Sample\Plugins\ModuleEnhablePlugin.php at line 15</a>

#Class ModuleEnhablePlugin#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEventListener.md">BeforeTaskEventListener</a>
 &gt; **ModuleEnhablePlugin**




- - -

<p><strong>public  class</strong> <span>ModuleEnhablePlugin</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEventListener.md">BeforeTaskEventListener</a>

</p>

<div class="comment" id="overview_description"><p>Description of ModuleEnhablePlugin</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#beforetask">beforeTask</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEvent.md">BeforeTaskEvent</a> e)</p><p class="description">This is the method that needs to be implemented by the event listener in
order to work. </p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Events\BeforeTaskEventListener</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEventListener.md#beforeTask">beforeTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEventListener.md#getSubscribedEvents">getSubscribedEvents</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEventListener.md#onBeforeTask">onBeforeTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/ext/libs/SampleExtension/Sample/Plugins/ModuleEnhablePlugin.php#L17" target='_blank'>ext\libs\SampleExtension\Sample\Plugins\ModuleEnhablePlugin.php at line 17</a>

<h3 id="beforeTask()">beforeTask</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>beforeTask</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEvent.md">BeforeTaskEvent</a> e)

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

