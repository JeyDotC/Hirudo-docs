- - -

**Hirudo\Core\DependencyInjection\DependenciesManager**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line10" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 10</a>

# Interface DependenciesManager #

<pre class="tree">** DependenciesManager **\n</pre>

- - -

<p class="signature">public  interface **DependenciesManager**</p>

<div class="comment" id="overview_description"><p>This is the interface for all dependency injection managers.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addServices()">addServices</a>(array implementationClasses)</p><p class="description">This method takes an array of fully qualified class names and registers them
in the container to inject them later.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#resolveDependencies()">resolveDependencies</a>(mixed object)</p><p class="description">Resolves all dependencies in the given object.</p></td>
</tr>
<tr>
<td class="type"> array<mixed></td>
<td class="description"><p class="name"><a href="#getClassMetadata()">getClassMetadata</a>(\ReflectionClass object)</p><p class="description">Gets the metadata associated to the given object.</p></td>
</tr>
<tr>
<td class="type"> array<mixed></td>
<td class="description"><p class="name"><a href="#getMethodMetadata()">getMethodMetadata</a>(\ReflectionMethod method)</p><p class="description">Gets the metadata associated to the given method.</p></td>
</tr>
<tr>
<td class="type"> array<mixed></td>
<td class="description"><p class="name"><a href="#getPropertyMetadata()">getPropertyMetadata</a>(\ReflectionProperty property)</p><p class="description">Gets the metadata associated to the given property.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getClassMetadataById()">getClassMetadataById</a>(\ReflectionClass object, string metadataId, mixed metaDataId)</p><p class="description">Gets a single metadata object by id from
a class.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getMethodMetadataById()">getMethodMetadataById</a>(\ReflectionMethod method, string metadataId, mixed metaDataId)</p><p class="description">Gets a single metadata object by id from
a method.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getPropertyMetadataById()">getPropertyMetadataById</a>(\ReflectionProperty property, string metadataId, mixed metaDataId)</p><p class="description">Gets a single metadata object by its id from
a property.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line18" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 18</a>

<h3 id="addServices()">addServices</h3>
```php
public  void **addServices**(array implementationClasses)```
<div class="details">
<p>This method takes an array of fully qualified class names and registers them
in the container to inject them later.</p><dl>
<dt>Parameters:</dt>
<dd>implementationClasses - An array of fully qualified class names.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line25" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 25</a>

<h3 id="resolveDependencies()">resolveDependencies</h3>
```php
public  void **resolveDependencies**(mixed object)```
<div class="details">
<p>Resolves all dependencies in the given object.</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line34" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 34</a>

<h3 id="getClassMetadata()">getClassMetadata</h3>
```php
public  array<mixed> **getClassMetadata**(\ReflectionClass object)```
<div class="details">
<p>Gets the metadata associated to the given object.</p><dl>
<dt>Returns:</dt>
<dd>The metadata values, normally objects with plain information about the class.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line43" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 43</a>

<h3 id="getMethodMetadata()">getMethodMetadata</h3>
```php
public  array<mixed> **getMethodMetadata**(\ReflectionMethod method)```
<div class="details">
<p>Gets the metadata associated to the given method.</p><dl>
<dt>Returns:</dt>
<dd>The metadata values, normally objects with plain information about the method.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line52" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 52</a>

<h3 id="getPropertyMetadata()">getPropertyMetadata</h3>
```php
public  array<mixed> **getPropertyMetadata**(\ReflectionProperty property)```
<div class="details">
<p>Gets the metadata associated to the given property.</p><dl>
<dt>Returns:</dt>
<dd>The metadata values, normally objects with plain information about the property.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line63" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 63</a>

<h3 id="getClassMetadataById()">getClassMetadataById</h3>
```php
public  mixed **getClassMetadataById**(\ReflectionClass object, string metadataId, mixed metaDataId)```
<div class="details">
<p>Gets a single metadata object by id from
a class.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>metadataId - The metadata id (usually an annotation class name)</dd>
<dt>Returns:</dt>
<dd>The metadata value, normally an object with plain information about the class.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line74" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 74</a>

<h3 id="getMethodMetadataById()">getMethodMetadataById</h3>
```php
public  mixed **getMethodMetadataById**(\ReflectionMethod method, string metadataId, mixed metaDataId)```
<div class="details">
<p>Gets a single metadata object by id from
a method.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>metadataId - The metadata id (usually an annotation class name)</dd>
<dt>Returns:</dt>
<dd>The metadata value, normally an object with plain information about the method.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/DependencyInjection/DependenciesManager.php.md#line85" class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 85</a>

<h3 id="getPropertyMetadataById()">getPropertyMetadataById</h3>
```php
public  mixed **getPropertyMetadataById**(\ReflectionProperty property, string metadataId, mixed metaDataId)```
<div class="details">
<p>Gets a single metadata object by its id from
a property.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>metadataId - The metadata id (usually an annotation class name)</dd>
<dt>Returns:</dt>
<dd>The metadata value, normally an object with plain information about the property.</dd>
</dl>
</div>

- - -

