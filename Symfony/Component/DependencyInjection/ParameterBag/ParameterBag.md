

- - -

**Symfony\Component\DependencyInjection\ParameterBag\ParameterBag**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L24" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 24</a>

#Class ParameterBag#

**ParameterBag**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/FrozenParameterBag.md">FrozenParameterBag</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>ParameterBag</span></p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#parameters"> $parameters</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.md#resolved"> $resolved</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array parameters)</p><p class="description">Constructor.</p></td>
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
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#all">all</a>()</p><p class="description">Gets the service container parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string name)</p><p class="description">Gets a service container parameter.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#set">set</a>(string name, mixed value)</p><p class="description">Sets a service container parameter.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#has">has</a>(string name)</p><p class="description">Returns true if a parameter name is defined.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#resolve">resolve</a>()</p><p class="description">Replaces parameter placeholders (%name%) by their values for all parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#resolvevalue">resolveValue</a>(mixed value, array resolving)</p><p class="description">Replaces parameter placeholders (%name%) by their values.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#resolvestring">resolveString</a>(string value, array resolving)</p><p class="description">Resolves parameters inside a string</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#isresolved">isResolved</a>()</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L26" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 26</a>

<h3 id="parameters">parameters</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $parameters</span><span class='o'> = null</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L27" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 27</a>

<h3 id="resolved">resolved</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $resolved</span><div class="details">

</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L36" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 36</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (array parameters)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>parameters - An array of parameters</dd>
<dt>Api.</dt>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L48" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 48</a>

<h3 id="clear()">clear</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>clear</span> ()

<div class="details">
<p>Clears all parameters.</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L60" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 60</a>

<h3 id="add()">add</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>add</span> (array parameters)

<div class="details">
<p>Adds parameters to the service container parameters.</p><dl>
<dt>Parameters:</dt>
<dd>parameters - An array of parameters</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L74" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 74</a>

<h3 id="all()">all</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>all</span> ()

<div class="details">
<p>Gets the service container parameters.</p><dl>
<dt>Returns:</dt>
<dd>An array of parameters</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L90" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 90</a>

<h3 id="get()">get</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>get</span> (string name)

<div class="details">
<p>Gets a service container parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>The parameter value</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/parameternotfoundexception.html">ParameterNotFoundException</a> - if the parameter is not defined</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L109" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 109</a>

<h3 id="set()">set</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>set</span> (string name, mixed value)

<div class="details">
<p>Sets a service container parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dd>value - The parameter value</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L123" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 123</a>

<h3 id="has()">has</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>has</span> (string name)

<div class="details">
<p>Returns true if a parameter name is defined.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>true if the parameter name is defined, false otherwise</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L131" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 131</a>

<h3 id="resolve()">resolve</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>resolve</span> ()

<div class="details">
<p>Replaces parameter placeholders (%name%) by their values for all parameters.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L165" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 165</a>

<h3 id="resolveValue()">resolveValue</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>resolveValue</span> (mixed value, array resolving)

<div class="details">
<p>Replaces parameter placeholders (%name%) by their values.</p><dl>
<dt>Parameters:</dt>
<dd>value - A value</dd>
<dd>resolving - An array of keys that are being resolved (used internally to detect circular references)</dd>
<dt>Returns:</dt>
<dd>The resolved value</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/parameternotfoundexception.html">ParameterNotFoundException</a> - if a placeholder references a parameter that does not exist</dd>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/parametercircularreferenceexception.html">ParameterCircularReferenceException</a> - if a circular reference if detected</dd>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/runtimeexception.html">RuntimeException</a> - when a given parameter has a type problem.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L195" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 195</a>

<h3 id="resolveString()">resolveString</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>resolveString</span> (string value, array resolving)

<div class="details">
<p>Resolves parameters inside a string</p><dl>
<dt>Parameters:</dt>
<dd>value - The string to resolve</dd>
<dd>resolving - An array of keys that are being resolved (used internally to detect circular references)</dd>
<dt>Returns:</dt>
<dd>The resolved string</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/parameternotfoundexception.html">ParameterNotFoundException</a> - if a placeholder references a parameter that does not exist</dd>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/parametercircularreferenceexception.html">ParameterCircularReferenceException</a> - if a circular reference if detected</dd>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/runtimeexception.html">RuntimeException</a> - when a given parameter has a type problem.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ParameterBag/ParameterBag.php#L233" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 233</a>

<h3 id="isResolved()">isResolved</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>isResolved</span> ()

<div class="details">

</div>

- - -

