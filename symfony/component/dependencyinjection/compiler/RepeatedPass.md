
- - -

**Symfony\Component\DependencyInjection\Compiler\RepeatedPass**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 21#L21 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 21</a>

#Class RepeatedPass#

**RepeatedPass**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> </dd>
</dl>



- - -

<p class="signature">public  class **RepeatedPass**</p>

<div class="comment" id="overview_description"><p>A pass that might be run repeatedly.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array passes)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Process the repeatable passes that run more than once.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setrepeat">setRepeat</a>()</p><p class="description">Sets if the pass should repeat</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getpasses">getPasses</a>()</p><p class="description">Returns the passes</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 31#L31 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 31</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (array passes)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>passes - An array of RepeatablePassInterface objects</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 49#L49 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 49</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)

<div class="details">
<p>Process the repeatable passes that run more than once.</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 65#L65 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 65</a>

<h3 id="setRepeat()">setRepeat</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setRepeat</span> ()

<div class="details">
<p>Sets if the pass should repeat</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 75#L75 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RepeatedPass.php at line 75</a>

<h3 id="getPasses()">getPasses</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getPasses</span> ()

<div class="details">
<p>Returns the passes</p><dl>
<dt>Returns:</dt>
<dd>An array of RepeatablePassInterface objects</dd>
</dl>
</div>

- - -

