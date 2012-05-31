
- - -

**Hirudo\Core\DependencyInjection\DependenciesManager**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 10#L10 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 10</a>

#Interface DependenciesManager#

**DependenciesManager**




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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addservices">addServices</a>(array implementationClasses)</p><p class="description">This method takes an array of fully qualified class names and registers them
in the container to inject them later.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#resolvedependencies">resolveDependencies</a>(mixed object)</p><p class="description">Resolves all dependencies in the given object.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<mixed></span></td>
<td class="description"><p class="name"><a href="#getclassmetadata">getClassMetadata</a>(\ReflectionClass object)</p><p class="description">Gets the metadata associated to the given object.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<mixed></span></td>
<td class="description"><p class="name"><a href="#getmethodmetadata">getMethodMetadata</a>(\ReflectionMethod method)</p><p class="description">Gets the metadata associated to the given method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<mixed></span></td>
<td class="description"><p class="name"><a href="#getpropertymetadata">getPropertyMetadata</a>(\ReflectionProperty property)</p><p class="description">Gets the metadata associated to the given property.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getclassmetadatabyid">getClassMetadataById</a>(\ReflectionClass object, string metadataId, mixed metaDataId)</p><p class="description">Gets a single metadata object by id from
a class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getmethodmetadatabyid">getMethodMetadataById</a>(\ReflectionMethod method, string metadataId, mixed metaDataId)</p><p class="description">Gets a single metadata object by id from
a method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getpropertymetadatabyid">getPropertyMetadataById</a>(\ReflectionProperty property, string metadataId, mixed metaDataId)</p><p class="description">Gets a single metadata object by its id from
a property.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 18#L18 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 18</a>

<h3 id="addServices()">addServices</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addServices</span> (array implementationClasses)

<div class="details">
<p>This method takes an array of fully qualified class names and registers them
in the container to inject them later.</p><dl>
<dt>Parameters:</dt>
<dd>implementationClasses - An array of fully qualified class names.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 25#L25 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 25</a>

<h3 id="resolveDependencies()">resolveDependencies</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>resolveDependencies</span> (mixed object)

<div class="details">
<p>Resolves all dependencies in the given object.</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 34#L34 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 34</a>

<h3 id="getClassMetadata()">getClassMetadata</h3>
<span class='k'></span> <span class='nx'>array<mixed></span> <span class='nf'>getClassMetadata</span> (\ReflectionClass object)

<div class="details">
<p>Gets the metadata associated to the given object.</p><dl>
<dt>Returns:</dt>
<dd>The metadata values, normally objects with plain information about the class.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 43#L43 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 43</a>

<h3 id="getMethodMetadata()">getMethodMetadata</h3>
<span class='k'></span> <span class='nx'>array<mixed></span> <span class='nf'>getMethodMetadata</span> (\ReflectionMethod method)

<div class="details">
<p>Gets the metadata associated to the given method.</p><dl>
<dt>Returns:</dt>
<dd>The metadata values, normally objects with plain information about the method.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 52#L52 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 52</a>

<h3 id="getPropertyMetadata()">getPropertyMetadata</h3>
<span class='k'></span> <span class='nx'>array<mixed></span> <span class='nf'>getPropertyMetadata</span> (\ReflectionProperty property)

<div class="details">
<p>Gets the metadata associated to the given property.</p><dl>
<dt>Returns:</dt>
<dd>The metadata values, normally objects with plain information about the property.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 63#L63 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 63</a>

<h3 id="getClassMetadataById()">getClassMetadataById</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getClassMetadataById</span> (\ReflectionClass object, string metadataId, mixed metaDataId)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 74#L74 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 74</a>

<h3 id="getMethodMetadataById()">getMethodMetadataById</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getMethodMetadataById</span> (\ReflectionMethod method, string metadataId, mixed metaDataId)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 85#L85 class="location">framework\hirudo\Hirudo\Core\DependencyInjection\DependenciesManager.php at line 85</a>

<h3 id="getPropertyMetadataById()">getPropertyMetadataById</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getPropertyMetadataById</span> (\ReflectionProperty property, string metadataId, mixed metaDataId)

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

