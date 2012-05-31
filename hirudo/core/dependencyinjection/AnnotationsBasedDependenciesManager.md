- - -

**Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager**
<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 41</div>
#Class AnnotationsBasedDependenciesManager#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containeraware.html">ContainerAware</a>
    ***AnnotationsBasedDependenciesManager**


- - -

<p class="signature">public  class **AnnotationsBasedDependenciesManager**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containeraware.html">ContainerAware</a>

</p>

<div class="comment" id="overview_description"><p>A dependencies manager that uses the doctrine's doc-block annotations system
to determine dependencies and load services.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Api.</dt>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\ContainerAware</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containeraware.html#container">container</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addServices">addServices</a>(array implementationClasses)</p><p class="description">This method takes an array of fully qualified class names and registers them
in the container to inject them later. </p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#resolveDependencies">resolveDependencies</a>(mixed object)</p><p class="description">Resolves all dependencies in the given object. </p></td>
</tr>
<tr>
<td class="type"> array<mixed></td>
<td class="description"><p class="name"><a href="#getClassMetadata">getClassMetadata</a>(\ReflectionClass object)</p><p class="description">Gets the annotations associated to thie given class.</p></td>
</tr>
<tr>
<td class="type"> array<mixed></td>
<td class="description"><p class="name"><a href="#getMethodMetadata">getMethodMetadata</a>(\ReflectionMethod method)</p><p class="description">Gets the annotations associated to thie given method.</p></td>
</tr>
<tr>
<td class="type"> array<mixed></td>
<td class="description"><p class="name"><a href="#getPropertyMetadata">getPropertyMetadata</a>(\ReflectionProperty property)</p><p class="description">Gets the annotations associated to thie given property.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getClassMetadataById">getClassMetadataById</a>(\ReflectionClass object, string metaDataId)</p><p class="description">Gets an annotation associated to thie given class by it's fully qualified class name.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getMethodMetadataById">getMethodMetadataById</a>(\ReflectionMethod method, string metaDataId)</p><p class="description">Gets an annotation associated to thie given method by it's fully qualified class name.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getPropertyMetadataById">getPropertyMetadataById</a>(\ReflectionProperty property, string metaDataId)</p><p class="description">Gets an annotation associated to thie given property by it's fully qualified class name.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\ContainerAware</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containeraware.html#setContainer()">setContainer</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 49</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 63</div>
<h3 id="addServices()">addServices</h3>
```php
public  void **addServices**(array implementationClasses)```
<div class="details">
<p>This method takes an array of fully qualified class names and registers them
in the container to inject them later. Such classes must be annotated with
the @Export annotation in order to be injected.</p><dl>
<dt>Parameters:</dt>
<dd>implementationClasses - An array of fully qualified class names.</dd>
<dt>See Also:</dt>
<dd><a href="../../../hirudo/core/annotations/export.html">the @Export annotation for more information about exporting classes.</a></dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 86</div>
<h3 id="resolveDependencies()">resolveDependencies</h3>
```php
public  void **resolveDependencies**(mixed object)```
<div class="details">
<p>Resolves all dependencies in the given object. A dependency is announced
by using the @Import annotation on a public setter method or a property
regardless it's access level.</p><dl>
<dt>See Also:</dt>
<dd><a href="../../../hirudo/core/annotations/import.html">Import</a></dd>
<dd><a href="../../../hirudo/core/annotations/export.html">Export</a></dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 166</div>
<h3 id="getClassMetadata()">getClassMetadata</h3>
```php
public  array<mixed> **getClassMetadata**(\ReflectionClass object)```
<div class="details">
<p>Gets the annotations associated to thie given class.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 176</div>
<h3 id="getMethodMetadata()">getMethodMetadata</h3>
```php
public  array<mixed> **getMethodMetadata**(\ReflectionMethod method)```
<div class="details">
<p>Gets the annotations associated to thie given method.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 186</div>
<h3 id="getPropertyMetadata()">getPropertyMetadata</h3>
```php
public  array<mixed> **getPropertyMetadata**(\ReflectionProperty property)```
<div class="details">
<p>Gets the annotations associated to thie given property.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 197</div>
<h3 id="getClassMetadataById()">getClassMetadataById</h3>
```php
public  mixed **getClassMetadataById**(\ReflectionClass object, string metaDataId)```
<div class="details">
<p>Gets an annotation associated to thie given class by it's fully qualified class name.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>metaDataId - The annotation's fully qualified class name</dd>
<dt>Returns:</dt>
<dd>The annotation, or null if it doesn't exists for this class.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 208</div>
<h3 id="getMethodMetadataById()">getMethodMetadataById</h3>
```php
public  mixed **getMethodMetadataById**(\ReflectionMethod method, string metaDataId)```
<div class="details">
<p>Gets an annotation associated to thie given method by it's fully qualified class name.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>metaDataId - The annotation's fully qualified class name</dd>
<dt>Returns:</dt>
<dd>The annotation, or null if it doesn't exists for this method.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\DependencyInjection\AnnotationsBasedDependenciesManager.php at line 219</div>
<h3 id="getPropertyMetadataById()">getPropertyMetadataById</h3>
```php
public  mixed **getPropertyMetadataById**(\ReflectionProperty property, string metaDataId)```
<div class="details">
<p>Gets an annotation associated to thie given property by it's fully qualified class name.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>metaDataId - The annotation's fully qualified class name</dd>
<dt>Returns:</dt>
<dd>The annotation, or null if it doesn't exists for this property.</dd>
</dl>
</div>

- - -

