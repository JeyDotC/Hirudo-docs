

- - -

**Doctrine\Common\Annotations\DocParser**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/DocParser.php#L41" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 41</a>

#Class DocParser#

**DocParser**




- - -

<p><strong>public final  class</strong> <span>DocParser</span></p>

<div class="comment" id="overview_description"><p>A parser for docblock annotations.</p><p>It is strongly discouraged to change the default annotation parsing process.</p></div>

<dl>
<dt>Author:</dt>
<dd>Benjamin Eberlei <kontakt@beberlei.de></dd>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dd>Fabio B. Silva <fabio.bat.silva@gmail.com></dd>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Constructs a new DocParser.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setignoredannotationnames">setIgnoredAnnotationNames</a>(array names)</p><p class="description">Sets the annotation names that are ignored during the parsing process.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setignorenotimportedannotations">setIgnoreNotImportedAnnotations</a>(mixed bool)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addnamespace">addNamespace</a>(array namespaces, mixed namespace)</p><p class="description">Sets the default namespaces.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setimports">setImports</a>(mixed imports)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#settarget">setTarget</a>(integer target)</p><p class="description">Sets current target context as bitmask.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#parse">parse</a>(string input, string context)</p><p class="description">Parses the given docblock string for annotations.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/DocParser.php#L139" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 139</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Constructs a new DocParser.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/DocParser.php#L151" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 151</a>

<h3 id="setIgnoredAnnotationNames()">setIgnoredAnnotationNames</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setIgnoredAnnotationNames</span> (array names)

<div class="details">
<p>Sets the annotation names that are ignored during the parsing process.</p><p>The names are supposed to be the raw names as used in the class, not the
fully qualified class names.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/DocParser.php#L155" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 155</a>

<h3 id="setIgnoreNotImportedAnnotations()">setIgnoreNotImportedAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setIgnoreNotImportedAnnotations</span> (mixed bool)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/DocParser.php#L163" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 163</a>

<h3 id="addNamespace()">addNamespace</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addNamespace</span> (array namespaces, mixed namespace)

<div class="details">
<p>Sets the default namespaces.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/DocParser.php#L170" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 170</a>

<h3 id="setImports()">setImports</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setImports</span> (mixed imports)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/DocParser.php#L182" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 182</a>

<h3 id="setTarget()">setTarget</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setTarget</span> (integer target)

<div class="details">
<p>Sets current target context as bitmask.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/DocParser.php#L193" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 193</a>

<h3 id="parse()">parse</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>parse</span> (string input, string context)

<div class="details">
<p>Parses the given docblock string for annotations.</p><dl>
<dt>Parameters:</dt>
<dd>input - The docblock string to parse.</dd>
<dd>context - The parsing context.</dd>
<dt>Returns:</dt>
<dd>Array of annotations. If no annotations are found, an empty array is returned.</dd>
</dl>

</div>

- - -

