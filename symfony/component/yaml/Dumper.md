

- - -

**Symfony\Component\Yaml\Dumper**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Dumper.php#L19" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Dumper.php at line 19</a>

#Class Dumper#

**Dumper**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/GraphvizDumper.md">Symfony\Component\DependencyInjection\Dumper\GraphvizDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/PhpDumper.md">Symfony\Component\DependencyInjection\Dumper\PhpDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/XmlDumper.md">Symfony\Component\DependencyInjection\Dumper\XmlDumper</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/YamlDumper.md">Symfony\Component\DependencyInjection\Dumper\YamlDumper</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>Dumper</span></p>

<div class="comment" id="overview_description"><p>Dumper dumps PHP variables to YAML strings.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#dump">dump</a>(mixed input, integer inline, integer indent)</p><p class="description">Dumps a PHP value to YAML.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Dumper.php#L30" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Dumper.php at line 30</a>

<h3 id="dump()">dump</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>dump</span> (mixed input, integer inline, integer indent)

<div class="details">
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

