- - -

**Symfony\Component\DependencyInjection\ContainerAware**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerAware.php.md#line21" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerAware.php at line 21</a>

# Class ContainerAware #

<pre class="tree">** ContainerAware **\n</pre>

<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/dependencyinjection/annotationsbaseddependenciesmanager.html">Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager</a> </dd>
</dl>

- - -

<p class="signature">public  class **ContainerAware**</p>

<div class="comment" id="overview_description"><p>A simple implementation of ContainerAwareInterface.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  <a href="../../../symfony/component/dependencyinjection/containerinterface.html">ContainerInterface</a></td>
<td class="description"><p class="name"><a href="#container">$container</a></p><p class="description"></p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setContainer()">setContainer</a>(<a href="../../../symfony/component/dependencyinjection/containerinterface.html">ContainerInterface</a> container)</p><p class="description">Sets the Container associated with this Controller.</p></td>
</tr>
</table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerAware.php.md#line28" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerAware.php at line 28</a>

<h3 id="container">container</h3>
```php
protected  <a href="../../../symfony/component/dependencyinjection/containerinterface.html">ContainerInterface</a> **$container** = EXCEPTION_ON_INVALID_REFERENCE```
<div class="details">
<p></p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerAware.php.md#line37" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerAware.php at line 37</a>

<h3 id="setContainer()">setContainer</h3>
```php
public  void **setContainer**(<a href="../../../symfony/component/dependencyinjection/containerinterface.html">ContainerInterface</a> container)```
<div class="details">
<p>Sets the Container associated with this Controller.</p><dl>
<dt>Parameters:</dt>
<dd>container - A ContainerInterface instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

