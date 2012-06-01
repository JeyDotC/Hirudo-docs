

- - -

**Hirudo\Core\ModulesManager**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/ModulesManager.php#L41" >framework\hirudo\Hirudo\Core\ModulesManager.php at line 41</a>

#Class ModulesManager#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">EventDispatcher</a>
    * **ModulesManager**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>ModulesManager</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">EventDispatcher</a>

</p>

<div class="comment" id="overview_description"><p>This class serves as a front controller in Hirudo, is the main entry
point of the framework.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Api.</dt>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array<string> implementationClasses)</p><p class="description">Creates a new modules manager.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#run">run</a>()</p><p class="description">Executes the requested action based on the request parameters or the
default configuration.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#executecall">executeCall</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/ModuleCall.md">ModuleCall</a> call)</p><p class="description">Executes a ModuleCall.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setautoloader">setAutoLoader</a>(type loader)</p><p class="description">Sets the autoloader class.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#resolvetaskrequirements">resolveTaskRequirements</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/Task.md">Task</a> task)</p><p class="description">Resolves the task's requirements from request.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\EventDispatcher\EventDispatcher</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">addListener</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">addSubscriber</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">dispatch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">doDispatch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">getListeners</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">hasListeners</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">removeListener</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.md">removeSubscriber</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/ModulesManager.php#L73" >framework\hirudo\Hirudo\Core\ModulesManager.php at line 73</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (array<string> implementationClasses)

<div class="details">
<p>Creates a new modules manager.</p><dl>
<dt>Parameters:</dt>
<dd>implementationClasses - A list of fully qualified class names that implement the core functionalities of Hirudo.</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/ModulesManager.php#L93" >framework\hirudo\Hirudo\Core\ModulesManager.php at line 93</a>

<h3 id="run()">run</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>run</span> ()

<div class="details">
<p>Executes the requested action based on the request parameters or the
default configuration.</p><dl>
<dt>Returns:</dt>
<dd>The program's output.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/ModulesManager.php#L123" >framework\hirudo\Hirudo\Core\ModulesManager.php at line 123</a>

<h3 id="executeCall()">executeCall</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>executeCall</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/ModuleCall.md">ModuleCall</a> call)

<div class="details">
<p>Executes a ModuleCall.</p><dl>
<dt>Parameters:</dt>
<dd>call - The call to be executed.</dd>
<dt>Returns:</dt>
<dd>The resulting output.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/ModulesManager.php#L153" >framework\hirudo\Hirudo\Core\ModulesManager.php at line 153</a>

<h3 id="setAutoLoader()">setAutoLoader</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>setAutoLoader</span> (type loader)

<div class="details">
<p>Sets the autoloader class.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/ModulesManager.php#L163" >framework\hirudo\Hirudo\Core\ModulesManager.php at line 163</a>

<h3 id="resolveTaskRequirements()">resolveTaskRequirements</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>resolveTaskRequirements</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/Task.md">Task</a> task)

<div class="details">
<p>Resolves the task's requirements from request.</p><dl>
<dt>Throws:</dt>
<dd>Exception</dd>
</dl>

</div>

- - -

