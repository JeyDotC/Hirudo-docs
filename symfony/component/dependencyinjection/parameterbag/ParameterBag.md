- - -

**Symfony\Component\DependencyInjection\ParameterBag\ParameterBag**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 24</div>
#Class ParameterBag#

**ParameterBag**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/parameterbag/frozenparameterbag.html">FrozenParameterBag</a> </dd>
</dl>

- - -

<p class="signature">public  class **ParameterBag**</p>

<div class="comment" id="overview_description"><p></p></div>

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
<td class="description"><p class="name"><a href="#parameters">$parameters</a></p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#resolved">$resolved</a></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array parameters)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#clear">clear</a>()</p><p class="description">Clears all parameters.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#add">add</a>(array parameters)</p><p class="description">Adds parameters to the service container parameters.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#all">all</a>()</p><p class="description">Gets the service container parameters.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#get">get</a>(string name)</p><p class="description">Gets a service container parameter.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#set">set</a>(string name, mixed value)</p><p class="description">Sets a service container parameter.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#has">has</a>(string name)</p><p class="description">Returns true if a parameter name is defined.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#resolve">resolve</a>()</p><p class="description">Replaces parameter placeholders (%name%) by their values for all parameters.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#resolveValue">resolveValue</a>(mixed value, array resolving)</p><p class="description">Replaces parameter placeholders (%name%) by their values.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#resolveString">resolveString</a>(string value, array resolving)</p><p class="description">Resolves parameters inside a string</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#isResolved">isResolved</a>()</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 26</div>
<h3 id="parameters">parameters</h3>

```php
protected  mixed$parameters = null
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 27</div>
<h3 id="resolved">resolved</h3>

```php
protected  mixed$resolved
```
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 36</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(array parameters)
```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>parameters - An array of parameters</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 48</div>
<h3 id="clear()">clear</h3>

```php
public  void **clear**()
```
<div class="details">
<p>Clears all parameters.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 60</div>
<h3 id="add()">add</h3>

```php
public  void **add**(array parameters)
```
<div class="details">
<p>Adds parameters to the service container parameters.</p><dl>
<dt>Parameters:</dt>
<dd>parameters - An array of parameters</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 74</div>
<h3 id="all()">all</h3>

```php
public  array **all**()
```
<div class="details">
<p>Gets the service container parameters.</p><dl>
<dt>Returns:</dt>
<dd>An array of parameters</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 90</div>
<h3 id="get()">get</h3>

```php
public  mixed **get**(string name)
```
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

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 109</div>
<h3 id="set()">set</h3>

```php
public  void **set**(string name, mixed value)
```
<div class="details">
<p>Sets a service container parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dd>value - The parameter value</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 123</div>
<h3 id="has()">has</h3>

```php
public  Boolean **has**(string name)
```
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

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 131</div>
<h3 id="resolve()">resolve</h3>

```php
public  void **resolve**()
```
<div class="details">
<p>Replaces parameter placeholders (%name%) by their values for all parameters.</p></div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 165</div>
<h3 id="resolveValue()">resolveValue</h3>

```php
public  mixed **resolveValue**(mixed value, array resolving)
```
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

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 195</div>
<h3 id="resolveString()">resolveString</h3>

```php
public  string **resolveString**(string value, array resolving)
```
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

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBag.php at line 233</div>
<h3 id="isResolved()">isResolved</h3>

```php
public  void **isResolved**()
```
<div class="details">
</div>

- - -

