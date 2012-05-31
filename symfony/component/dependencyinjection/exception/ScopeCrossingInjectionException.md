- - -

**Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 19</div>
#Class ScopeCrossingInjectionException#

\RuntimeException
*<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/runtimeexception.html">RuntimeException</a>
        ***ScopeCrossingInjectionException**


- - -

<p class="signature">public  class **ScopeCrossingInjectionException**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/runtimeexception.html">RuntimeException</a>

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
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed sourceServiceId, mixed sourceScope, mixed destServiceId, mixed destScope)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getSourceServiceId">getSourceServiceId</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getSourceScope">getSourceScope</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDestServiceId">getDestServiceId</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDestScope">getDestScope</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 26</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(mixed sourceServiceId, mixed sourceScope, mixed destServiceId, mixed destScope)
```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 46</div>
<h3 id="getSourceServiceId()">getSourceServiceId</h3>

```php
public  void **getSourceServiceId**()
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 51</div>
<h3 id="getSourceScope()">getSourceScope</h3>

```php
public  void **getSourceScope**()
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 56</div>
<h3 id="getDestServiceId()">getDestServiceId</h3>

```php
public  void **getDestServiceId**()
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ScopeCrossingInjectionException.php at line 61</div>
<h3 id="getDestScope()">getDestScope</h3>

```php
public  void **getDestScope**()
```
<div class="details">
</div>

- - -

