
- - -

**Doctrine\Common\Annotations\AnnotationException**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/doctrine/common/annotations/annotationexception.php#L31 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationException.php at line 31</a>

#Class AnnotationException#

\Exception
* **AnnotationException**




- - -

<p class="signature">public  class **AnnotationException**
extends \Exception

</p>

<div class="comment" id="overview_description"><p>Description of AnnotationException</p></div>

<dl>
<dt>Since:</dt>
<dd>2.0</dd>
<dt>Author:</dt>
<dd>Benjamin Eberlei <kontakt@beberlei.de></dd>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span></td>
<td class="description"><p class="name"><a href="#syntaxerror">syntaxError</a>(string message)</p><p class="description">Creates a new AnnotationException describing a Syntax error.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span></td>
<td class="description"><p class="name"><a href="#semanticalerror">semanticalError</a>(string message)</p><p class="description">Creates a new AnnotationException describing a Semantical error.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span></td>
<td class="description"><p class="name"><a href="#creationerror">creationError</a>(string message)</p><p class="description">Creates a new AnnotationException describing an error which occurred during
the creation of the annotation.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span></td>
<td class="description"><p class="name"><a href="#typeerror">typeError</a>(string attributeName, string annotationName, string context, string expected, mixed actual)</p><p class="description">Creates a new AnnotationException describing an type error of an attribute.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span></td>
<td class="description"><p class="name"><a href="#requirederror">requiredError</a>(string attributeName, string annotationName, string context, string expected)</p><p class="description">Creates a new AnnotationException describing an required error of an attribute.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/doctrine/common/annotations/annotationexception.php#L39 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationException.php at line 39</a>

<h3 id="syntaxError()">syntaxError</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span> <span class='nf'>syntaxError</span> (string message)

<div class="details">
<p>Creates a new AnnotationException describing a Syntax error.</p><dl>
<dt>Parameters:</dt>
<dd>message - Exception message</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/doctrine/common/annotations/annotationexception.php#L50 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationException.php at line 50</a>

<h3 id="semanticalError()">semanticalError</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span> <span class='nf'>semanticalError</span> (string message)

<div class="details">
<p>Creates a new AnnotationException describing a Semantical error.</p><dl>
<dt>Parameters:</dt>
<dd>message - Exception message</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/doctrine/common/annotations/annotationexception.php#L63 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationException.php at line 63</a>

<h3 id="creationError()">creationError</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span> <span class='nf'>creationError</span> (string message)

<div class="details">
<p>Creates a new AnnotationException describing an error which occurred during
the creation of the annotation.</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/doctrine/common/annotations/annotationexception.php#L79 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationException.php at line 79</a>

<h3 id="typeError()">typeError</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span> <span class='nf'>typeError</span> (string attributeName, string annotationName, string context, string expected, mixed actual)

<div class="details">
<p>Creates a new AnnotationException describing an type error of an attribute.</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/doctrine/common/annotations/annotationexception.php#L101 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationException.php at line 101</a>

<h3 id="requiredError()">requiredError</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/annotationexception.html>AnnotationException</a></span> <span class='nf'>requiredError</span> (string attributeName, string annotationName, string context, string expected)

<div class="details">
<p>Creates a new AnnotationException describing an required error of an attribute.</p><dl>
<dt>Since:</dt>
<dd>2.2</dd>
</dl>
</div>

- - -

