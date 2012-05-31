
- - -

**Symfony\Component\Yaml\Dumper**
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Dumper.php at line 19</div>
#Class Dumper#

**Dumper**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/graphvizdumper.html">Symfony\Component\DependencyInjection\Dumper\GraphvizDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/phpdumper.html">Symfony\Component\DependencyInjection\Dumper\PhpDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/xmldumper.html">Symfony\Component\DependencyInjection\Dumper\XmlDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/yamldumper.html">Symfony\Component\DependencyInjection\Dumper\YamlDumper</a> </dd>
</dl>

- - -

<p class="signature">public  class **Dumper**</p>

<div class="comment" id="overview_description"><p>Dumper dumps PHP variables to YAML strings.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#dump">dump</a>(mixed input, integer inline, integer indent)</p><p class="description">Dumps a PHP value to YAML.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Dumper.php at line 30</div>
<h3 id="dump()">dump</h3>

public  string **dump** (mixed input, integer inline, integer indent)<div class="details">
<p>Dumps a PHP value to YAML.</p><dl>
<dt>Parameters:</dt>
<dd>input - The PHP value</dd>
<dd>inline - The level where you switch to inline YAML</dd>
<dd>indent - The level of indentation (used internally)</dd>
<dt>Returns:</dt>
<dd>The YAML representation of the PHP value</dd>
</dl>
</div>

- - -

