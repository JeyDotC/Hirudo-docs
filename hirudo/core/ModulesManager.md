- - -

**Hirudo\Core\ModulesManager** 
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/ModulesManager.php.md#line41" class="location">framework\hirudo\Hirudo\Core\ModulesManager.php at line 41</a>

#Class ModulesManager

* <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html">EventDispatcher</a>
    * **ModulesManager**

- - -

<p class="signature">public  class **ModulesManager**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html">EventDispatcher</a>

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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array<string> implementationClasses)</p><p class="description">Creates a new modules manager.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#run">run</a>()</p><p class="description">Executes the requested action based on the request parameters or the
default configuration.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#executeCall">executeCall</a>(<a href="../../hirudo/core/context/modulecall.html">ModuleCall</a> call)</p><p class="description">Executes a ModuleCall.</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#setAutoLoader()">setAutoLoader</a>(type loader)</p><p class="description">Sets the autoloader class.</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#resolveTaskRequirements()">resolveTaskRequirements</a>(<a href="../../hirudo/core/task.html">Task</a> task)</p><p class="description">Resolves the task's requirements from request.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\EventDispatcher\EventDispatcher</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html#addListener()">addListener</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html#addSubscriber()">addSubscriber</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html#dispatch()">dispatch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html#doDispatch()">doDispatch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html#getListeners()">getListeners</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html#hasListeners()">hasListeners</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html#removeListener()">removeListener</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/eventdispatcher/eventdispatcher.html#removeSubscriber()">removeSubscriber</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/ModulesManager.php.md#line73" class="location">framework\hirudo\Hirudo\Core\ModulesManager.php at line 73</a>

<h3 id="__construct">__construct</h3>

```php
public  void **__construct**(array<string> implementationClasses)
```

<div class="details">
<p>Creates a new modules manager.</p><dl>
<dt>Parameters:</dt>
<dd>implementationClasses - A list of fully qualified class names that implement the core functionalities of Hirudo.</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/ModulesManager.php.md#line93" class="location">framework\hirudo\Hirudo\Core\ModulesManager.php at line 93</a>

<h3 id="run()">run</h3>

```php
public  string run()
```

<div class="details">
<p>Executes the requested action based on the request parameters or the
default configuration.</p><dl>
<dt>Returns:</dt>
<dd>The program's output.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/ModulesManager.php.md#line123" class="location">framework\hirudo\Hirudo\Core\ModulesManager.php at line 123</a>

<h3 id="executeCall()">executeCall</h3>

```php
public  string executeCall(ModuleCall call)
```

<div class="details">
<p>Executes a ModuleCall.</p><dl>
<dt>Parameters:</dt>
<dd>call - The call to be executed.</dd>
<dt>Returns:</dt>
<dd>The resulting output.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/ModulesManager.php.md#line153" class="location">framework\hirudo\Hirudo\Core\ModulesManager.php at line 153</a>

<h3 id="setAutoLoader()">setAutoLoader</h3>
```php
public static  void **setAutoLoader**(type loader)```
<div class="details">
<p>Sets the autoloader class.</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/ModulesManager.php.md#line163" class="location">framework\hirudo\Hirudo\Core\ModulesManager.php at line 163</a>

<h3 id="resolveTaskRequirements()">resolveTaskRequirements</h3>
```php
protected  void **resolveTaskRequirements**(<a href="../../hirudo/core/task.html">Task</a> task)```
<div class="details">
<p>Resolves the task's requirements from request.</p><dl>
<dt>Throws:</dt>
<dd>Exception</dd>
</dl>
</div>

- - -

