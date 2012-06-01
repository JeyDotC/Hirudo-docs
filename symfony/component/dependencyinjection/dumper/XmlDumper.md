

- - -

**Symfony\Component\DependencyInjection\Dumper\XmlDumper**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/XmlDumper.php#L27" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\XmlDumper.php at line 27</a>

#Class XmlDumper#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/dumper.md">Dumper</a>
    * **XmlDumper**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>XmlDumper</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/dumper.md">Dumper</a>

</p>

<div class="comment" id="overview_description"><p>XmlDumper dumps a service container as an XML string.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dd>Martin Hasoň <martin.hason@gmail.com></dd>
<dt>Api.</dt>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Dumper\Dumper</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/dumper.md">container</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#dump">dump</a>(array options)</p><p class="description">Dumps the service container as an XML string.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#phptoxml">phpToXml</a>(mixed value)</p><p class="description">Converts php types to xml types.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Dumper\Dumper</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/dumper.md">__construct</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/XmlDumper.php#L43" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\XmlDumper.php at line 43</a>

<h3 id="dump()">dump</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>dump</span> (array options)

<div class="details">
<p>Dumps the service container as an XML string.</p><dl>
<dt>Parameters:</dt>
<dd>options - An array of options</dd>
<dt>Returns:</dt>
<dd>An xml string representing of the service container</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/XmlDumper.php#L288" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\XmlDumper.php at line 288</a>

<h3 id="phpToXml()">phpToXml</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>phpToXml</span> (mixed value)

<div class="details">
<p>Converts php types to xml types.</p><dl>
<dt>Parameters:</dt>
<dd>value - Value to convert</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/runtimeexception.html">\RuntimeException</a> - When trying to dump object or resource</dd>
</dl>

</div>

- - -

