

- - -

**Symfony\Component\DependencyInjection\Loader\XmlFileLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/XmlFileLoader.php#L29" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\XmlFileLoader.php at line 29</a>

#Class XmlFileLoader#

BaseFileLoader
* <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/FileLoader.md">FileLoader</a>
        * **XmlFileLoader**




- - -

<p><strong>public  class</strong> <span>XmlFileLoader</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/FileLoader.md">FileLoader</a>

</p>

<div class="comment" id="overview_description"><p>XmlFileLoader loads XML files service definitions.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/FileLoader.md#container">container</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load">load</a>(mixed file, string type)</p><p class="description">Loads an XML file.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#supports">supports</a>(mixed resource, string type)</p><p class="description">Returns true if this class supports the given resource.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#convertdomelementtoarray">convertDomElementToArray</a>(\DomElement element)</p><p class="description">Converts a \DomElement object to a PHP array.
</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/FileLoader.md#__construct">__construct</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/XmlFileLoader.php#L37" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\XmlFileLoader.php at line 37</a>

<h3 id="load()">load</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>load</span> (mixed file, string type)

<div class="details">
<p>Loads an XML file.</p><dl>
<dt>Parameters:</dt>
<dd>file - The resource</dd>
<dd>type - The resource type</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/XmlFileLoader.php#L70" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\XmlFileLoader.php at line 70</a>

<h3 id="supports()">supports</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>supports</span> (mixed resource, string type)

<div class="details">
<p>Returns true if this class supports the given resource.</p><dl>
<dt>Parameters:</dt>
<dd>resource - A resource</dd>
<dd>type - The resource type</dd>
<dt>Returns:</dt>
<dd>true if this class supports the given resource, false otherwise</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/XmlFileLoader.php#L462" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\XmlFileLoader.php at line 462</a>

<h3 id="convertDomElementToArray()">convertDomElementToArray</h3>
<span class='k'>static </span> <span class='nx'>array</span> <span class='nf'>convertDomElementToArray</span> (\DomElement element)

<div class="details">
<p>Converts a \DomElement object to a PHP array.</p><p>The following rules applies during the conversion:</p><p>* Each tag is converted to a key value or an array
if there is more than one "value"</p><p>* The content of a tag is set under a "value" key (<foo>bar</foo>)
if the tag also has some nested tags</p><p>* The attributes are converted to keys (<foo foo="bar"/>)</p><p>* The nested-tags are converted to keys (<foo><foo>bar</foo></foo>)</p><dl>
<dt>Parameters:</dt>
<dd>element - A \DomElement instance</dd>
<dt>Returns:</dt>
<dd>A PHP array</dd>
</dl>

</div>

- - -

