- - -

**Symfony\Component\DependencyInjection\Dumper\Dumper**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/Dumper.php.md#line23" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\Dumper.php at line 23</a>

# Class Dumper #

<pre class="tree">** Dumper **\n</pre>

<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/graphvizdumper.html">GraphvizDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/phpdumper.html">PhpDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/xmldumper.html">XmlDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/yamldumper.html">YamlDumper</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Dumper**</p>

<div class="comment" id="overview_description"><p>Dumper is the abstract class for all built-in dumpers.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#container">$container</a></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Constructor.</p></td>
</tr>
</table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/Dumper.php.md#line25" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\Dumper.php at line 25</a>

<h3 id="container">container</h3>
```php
protected  mixed **$container**```
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/Dumper.php.md#line34" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\Dumper.php at line 34</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>container - The service container to dump</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

