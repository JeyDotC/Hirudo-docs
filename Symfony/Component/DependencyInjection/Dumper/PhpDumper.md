

- - -

**Symfony\Component\DependencyInjection\Dumper\PhpDumper**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/PhpDumper.php#L31" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\PhpDumper.php at line 31</a>

#Class PhpDumper#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Dumper/Dumper.md">Dumper</a>
 &gt; **PhpDumper**




- - -

<p><strong>public  class</strong> <span>PhpDumper</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Dumper/Dumper.md">Dumper</a>

</p>

<div class="comment" id="overview_description"><p>PhpDumper dumps a service container as a PHP class.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Dumper\Dumper</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Dumper/Dumper.md#container">container</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#dump">dump</a>(array options)</p><p class="description">Dumps the service container as a PHP class.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#dumpparameter">dumpParameter</a>(string name)</p><p class="description">Dumps a parameter</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Dumper\Dumper</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Dumper/Dumper.md#__construct">__construct</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/PhpDumper.php#L44" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\PhpDumper.php at line 44</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>Constructor.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>container - The service container to dump</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/PhpDumper.php#L65" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\PhpDumper.php at line 65</a>

<h3 id="dump()">dump</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>dump</span> (array options)

<div class="details">
<p>Dumps the service container as a PHP class.</p><p>Available options:</p><p>* class:      The class name
* base_class: The base class name</p><dl>
<dt>Parameters:</dt>
<dd>options - An array of options</dd>
<dt>Returns:</dt>
<dd>A PHP class representing of the service container</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/PhpDumper.php#L1030" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\PhpDumper.php at line 1030</a>

<h3 id="dumpParameter()">dumpParameter</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>dumpParameter</span> (string name)

<div class="details">
<p>Dumps a parameter</p>
</div>

- - -
