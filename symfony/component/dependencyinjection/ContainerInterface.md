- - -

**Symfony\Component\DependencyInjection\ContainerInterface**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 22</div>
#Interface ContainerInterface#

**ContainerInterface**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/taggedcontainerinterface.html">TaggedContainerInterface</a> </dd>
</dl>

- - -

<p class="signature">public  interface **ContainerInterface**</p>

<div class="comment" id="overview_description"><p>ContainerInterface is the interface implemented by service container classes.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#get">get</a>(string id, int invalidBehavior)</p><p class="description">Gets a service.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#has">has</a>(string id)</p><p class="description">Returns true if the given service is defined.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getParameter">getParameter</a>(string name)</p><p class="description">Gets a parameter.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#hasParameter">hasParameter</a>(string name)</p><p class="description">Checks if a parameter exists.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setParameter">setParameter</a>(string name, mixed value)</p><p class="description">Sets a parameter.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#enterScope">enterScope</a>(string name)</p><p class="description">Enters the given scope</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#leaveScope">leaveScope</a>(string name)</p><p class="description">Leaves the current scope, and re-enters the parent scope</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addScope">addScope</a>(<a href="../../../symfony/component/dependencyinjection/scopeinterface.html">ScopeInterface</a> scope)</p><p class="description">Adds a scope to the container</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#hasScope">hasScope</a>(string name)</p><p class="description">Whether this container has the given scope</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#isScopeActive">isScopeActive</a>(string name)</p><p class="description">Determines whether the given scope is currently active.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 40</div>
<h3 id="get()">get</h3>
```php
public  object **get**(string id, int invalidBehavior)```
<div class="details">
<p>Gets a service.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>invalidBehavior - The behavior when the service does not exist</dd>
<dt>Returns:</dt>
<dd>The associated service</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the service is not defined</dd>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/reference.html">Reference</a></dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 51</div>
<h3 id="has()">has</h3>
```php
public  Boolean **has**(string id)```
<div class="details">
<p>Returns true if the given service is defined.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dt>Returns:</dt>
<dd>true if the service is defined, false otherwise</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 64</div>
<h3 id="getParameter()">getParameter</h3>
```php
public  mixed **getParameter**(string name)```
<div class="details">
<p>Gets a parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>The parameter value</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the parameter is not defined</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 75</div>
<h3 id="hasParameter()">hasParameter</h3>
```php
public  Boolean **hasParameter**(string name)```
<div class="details">
<p>Checks if a parameter exists.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>The presence of parameter in container</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 85</div>
<h3 id="setParameter()">setParameter</h3>
```php
public  void **setParameter**(string name, mixed value)```
<div class="details">
<p>Sets a parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dd>value - The parameter value</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 95</div>
<h3 id="enterScope()">enterScope</h3>
```php
public  void **enterScope**(string name)```
<div class="details">
<p>Enters the given scope</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 105</div>
<h3 id="leaveScope()">leaveScope</h3>
```php
public  void **leaveScope**(string name)```
<div class="details">
<p>Leaves the current scope, and re-enters the parent scope</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 115</div>
<h3 id="addScope()">addScope</h3>
```php
public  void **addScope**(<a href="../../../symfony/component/dependencyinjection/scopeinterface.html">ScopeInterface</a> scope)```
<div class="details">
<p>Adds a scope to the container</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 125</div>
<h3 id="hasScope()">hasScope</h3>
```php
public  Boolean **hasScope**(string name)```
<div class="details">
<p>Whether this container has the given scope</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 137</div>
<h3 id="isScopeActive()">isScopeActive</h3>
```php
public  Boolean **isScopeActive**(string name)```
<div class="details">
<p>Determines whether the given scope is currently active.</p><p>It does however not check if the scope actually exists.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

