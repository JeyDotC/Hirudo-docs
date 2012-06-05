

- - -

**Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/FrozenParameterBag.php#L20" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 20</a>

#Class FrozenParameterBag#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md">ParameterBag</a>
 &gt; **FrozenParameterBag**




- - -

<p><strong>public  class</strong> <span>FrozenParameterBag</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md">ParameterBag</a>

</p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\ParameterBag\ParameterBag</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#parameters">parameters</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#resolved">resolved</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array parameters)</p><p class="description">Constructor.
</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#clear">clear</a>()</p><p class="description">Clears all parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#add">add</a>(array parameters)</p><p class="description">Adds parameters to the service container parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#set">set</a>(string name, mixed value)</p><p class="description">Sets a service container parameter.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\ParameterBag\ParameterBag</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#add">add</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#all">all</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#clear">clear</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#get">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#has">has</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#isResolved">isResolved</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#resolve">resolve</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#resolveString">resolveString</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#resolveValue">resolveValue</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#set">set</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/FrozenParameterBag.php#L34" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 34</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (array parameters)

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

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/FrozenParameterBag.php#L45" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 45</a>

<h3 id="clear()">clear</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>clear</span> ()

<div class="details">
<p>Clears all parameters.</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/FrozenParameterBag.php#L55" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 55</a>

<h3 id="add()">add</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>add</span> (array parameters)

<div class="details">
<p>Adds parameters to the service container parameters.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>parameters - An array of parameters</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/FrozenParameterBag.php#L65" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\FrozenParameterBag.php at line 65</a>

<h3 id="set()">set</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>set</span> (string name, mixed value)

<div class="details">
<p>Sets a service container parameter.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dd>value - The parameter value</dd>
</dl>

</div>

- - -
