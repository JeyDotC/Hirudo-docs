
- - -

**Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 20</div>
#Class FrozenParameterBag#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html">ParameterBag</a>
    ***FrozenParameterBag**


- - -

<p class="signature">public  class **FrozenParameterBag**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html">ParameterBag</a>

</p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>

- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\ParameterBag\ParameterBag</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#parameters">parameters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#resolved">resolved</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array parameters)</p><p class="description">Constructor.
</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#clear">clear</a>()</p><p class="description">Clears all parameters.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#add">add</a>(array parameters)</p><p class="description">Adds parameters to the service container parameters.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#set">set</a>(string name, mixed value)</p><p class="description">Sets a service container parameter.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\ParameterBag\ParameterBag</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#add()">add</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#all()">all</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#clear()">clear</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#get()">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#has()">has</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#isResolved()">isResolved</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#resolve()">resolve</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#resolveString()">resolveString</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#resolveValue()">resolveValue</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/parameterbag.html#set()">set</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 34</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(array parameters)
```
<div class="details">
<p>Constructor.</p><p>For performance reasons, the constructor assumes that
all keys are already lowercased.</p><p>This is always the case when used internally.</p><dl>
<dt>Parameters:</dt>
<dd>parameters - An array of parameters</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 45</div>
<h3 id="clear()">clear</h3>

public  void **clear** ()<div class="details">
<p>Clears all parameters.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 55</div>
<h3 id="add()">add</h3>

public  void **add** (array parameters)<div class="details">
<p>Adds parameters to the service container parameters.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>parameters - An array of parameters</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 65</div>
<h3 id="set()">set</h3>

public  void **set** (string name, mixed value)<div class="details">
<p>Sets a service container parameter.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dd>value - The parameter value</dd>
</dl>
</div>

- - -

