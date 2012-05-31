
- - -

**Symfony\Component\DependencyInjection\Extension\ExtensionInterface**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 23#L23 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 23</a>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load">load</a>(array config, <a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Loads a specific configuration.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getnamespace">getNamespace</a>()</p><p class="description">Returns the namespace to be used for this extension (XML namespace).</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getxsdvalidationbasepath">getXsdValidationBasePath</a>()</p><p class="description">Returns the base path for the XSD files.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getalias">getAlias</a>()</p><p class="description">Returns the recommended alias to use in XML.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 35#L35 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 35</a>

<h3 id="load()">load</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>load</span> (array config, <a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 44#L44 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 44</a>

<h3 id="getNamespace()">getNamespace</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getNamespace</span> ()

<div class="details">
<p>Returns the namespace to be used for this extension (XML namespace).</p><dl>
<dt>Returns:</dt>
<dd>The XML namespace</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 53#L53 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 53</a>

<h3 id="getXsdValidationBasePath()">getXsdValidationBasePath</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getXsdValidationBasePath</span> ()

<div class="details">
<p>Returns the base path for the XSD files.</p><dl>
<dt>Returns:</dt>
<dd>The XSD base path</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 64#L64 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Extension\ExtensionInterface.php at line 64</a>

<h3 id="getAlias()">getAlias</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getAlias</span> ()

<div class="details">
<p>Returns the recommended alias to use in XML.</p><p>This alias is also the mandatory prefix to use when using YAML.</p><dl>
<dt>Returns:</dt>
<dd>The alias</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

