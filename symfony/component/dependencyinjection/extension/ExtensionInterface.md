- - -

**Symfony\Component\DependencyInjection\Extension\ExtensionInterface**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 23</div>
#Interface ExtensionInterface#

**ExtensionInterface**


- - -

<p class="signature">public  interface **ExtensionInterface**</p>

<div class="comment" id="overview_description"><p>ExtensionInterface is the interface implemented by container extension classes.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#load">load</a>(array config, <a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Loads a specific configuration.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getNamespace">getNamespace</a>()</p><p class="description">Returns the namespace to be used for this extension (XML namespace).</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getXsdValidationBasePath">getXsdValidationBasePath</a>()</p><p class="description">Returns the base path for the XSD files.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getAlias">getAlias</a>()</p><p class="description">Returns the recommended alias to use in XML.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 35</div>
<h3 id="load()">load</h3>
```php
public  void **load**(array config, <a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)```
<div class="details">
<p>Loads a specific configuration.</p><dl>
<dt>Parameters:</dt>
<dd>config - An array of configuration values</dd>
<dd>container - A ContainerBuilder instance</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - When provided tag is not defined in this extension</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 44</div>
<h3 id="getNamespace()">getNamespace</h3>
```php
public  string **getNamespace**()```
<div class="details">
<p>Returns the namespace to be used for this extension (XML namespace).</p><dl>
<dt>Returns:</dt>
<dd>The XML namespace</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 53</div>
<h3 id="getXsdValidationBasePath()">getXsdValidationBasePath</h3>
```php
public  string **getXsdValidationBasePath**()```
<div class="details">
<p>Returns the base path for the XSD files.</p><dl>
<dt>Returns:</dt>
<dd>The XSD base path</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 64</div>
<h3 id="getAlias()">getAlias</h3>
```php
public  string **getAlias**()```
<div class="details">
<p>Returns the recommended alias to use in XML.</p><p>This alias is also the mandatory prefix to use when using YAML.</p><dl>
<dt>Returns:</dt>
<dd>The alias</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

