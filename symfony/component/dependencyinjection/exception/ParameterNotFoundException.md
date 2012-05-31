- - -

**Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException.php at line 19</div>
#Class ParameterNotFoundException#

BaseInvalidArgumentException
*<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/invalidargumentexception.html">InvalidArgumentException</a>
        ***ParameterNotFoundException**


- - -

<p class="signature">public  class **ParameterNotFoundException**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/invalidargumentexception.html">InvalidArgumentException</a>

</p>

<div class="comment" id="overview_description"><p>This exception is thrown when a non-existent parameter is used.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string key, string sourceId, string sourceKey)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#updateRepr">updateRepr</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getKey">getKey</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getSourceId">getSourceId</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getSourceKey">getSourceKey</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setSourceId">setSourceId</a>(mixed sourceId)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setSourceKey">setSourceKey</a>(mixed sourceKey)</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException.php at line 32</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(string key, string sourceId, string sourceKey)```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>key - The requested parameter key</dd>
<dd>sourceId - The service id that references the non-existent parameter</dd>
<dd>sourceKey - The parameter key that references the non-existent parameter</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException.php at line 41</div>
<h3 id="updateRepr()">updateRepr</h3>
```php
public  void **updateRepr**()```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException.php at line 52</div>
<h3 id="getKey()">getKey</h3>
```php
public  void **getKey**()```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException.php at line 57</div>
<h3 id="getSourceId()">getSourceId</h3>
```php
public  void **getSourceId**()```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException.php at line 62</div>
<h3 id="getSourceKey()">getSourceKey</h3>
```php
public  void **getSourceKey**()```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException.php at line 67</div>
<h3 id="setSourceId()">setSourceId</h3>
```php
public  void **setSourceId**(mixed sourceId)```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Exception\ParameterNotFoundException.php at line 74</div>
<h3 id="setSourceKey()">setSourceKey</h3>
```php
public  void **setSourceKey**(mixed sourceKey)```
<div class="details">
</div>

- - -

