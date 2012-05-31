- - -

**Symfony\Component\DependencyInjection\Exception\ServiceCircularReferenceException**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ServiceCircularReferenceException.php.md#line19" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ServiceCircularReferenceException.php at line 19</a>

# Class ServiceCircularReferenceException #

<pre class="tree">\RuntimeException\n*<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/runtimeexception.html">RuntimeException</a>\n        *** ServiceCircularReferenceException **\n</pre>

- - -

<p class="signature">public  class **ServiceCircularReferenceException**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/runtimeexception.html">RuntimeException</a>

</p>

<div class="comment" id="overview_description"><p>This exception is thrown when a circular reference is detected.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(mixed serviceId, mixed path)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getServiceId()">getServiceId</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getPath()">getPath</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ServiceCircularReferenceException.php.md#line24" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ServiceCircularReferenceException.php at line 24</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(mixed serviceId, mixed path)```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ServiceCircularReferenceException.php.md#line32" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ServiceCircularReferenceException.php at line 32</a>

<h3 id="getServiceId()">getServiceId</h3>
```php
public  void **getServiceId**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ServiceCircularReferenceException.php.md#line37" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ServiceCircularReferenceException.php at line 37</a>

<h3 id="getPath()">getPath</h3>
```php
public  void **getPath**()```
<div class="details">
</div>

- - -

