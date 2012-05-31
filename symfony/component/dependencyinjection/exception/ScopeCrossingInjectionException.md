- - -

**Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ScopeCrossingInjectionException.php.md#line19" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 19</a>

# Class ScopeCrossingInjectionException #

<pre class="tree">\RuntimeException\n*<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/runtimeexception.html">RuntimeException</a>\n        *** ScopeCrossingInjectionException **\n</pre>

- - -

<p class="signature">public  class **ScopeCrossingInjectionException**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/runtimeexception.html">RuntimeException</a>

</p>

<div class="comment" id="overview_description"><p>This exception is thrown when the a scope crossing injection is detected.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(mixed sourceServiceId, mixed sourceScope, mixed destServiceId, mixed destScope)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getSourceServiceId()">getSourceServiceId</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getSourceScope()">getSourceScope</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDestServiceId()">getDestServiceId</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDestScope()">getDestScope</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ScopeCrossingInjectionException.php.md#line26" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 26</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(mixed sourceServiceId, mixed sourceScope, mixed destServiceId, mixed destScope)```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ScopeCrossingInjectionException.php.md#line46" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 46</a>

<h3 id="getSourceServiceId()">getSourceServiceId</h3>
```php
public  void **getSourceServiceId**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ScopeCrossingInjectionException.php.md#line51" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 51</a>

<h3 id="getSourceScope()">getSourceScope</h3>
```php
public  void **getSourceScope**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ScopeCrossingInjectionException.php.md#line56" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 56</a>

<h3 id="getDestServiceId()">getDestServiceId</h3>
```php
public  void **getDestServiceId**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Exception/ScopeCrossingInjectionException.php.md#line61" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 61</a>

<h3 id="getDestScope()">getDestScope</h3>
```php
public  void **getDestScope**()```
<div class="details">
</div>

- - -

