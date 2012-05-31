
- - -

**Doctrine\Common\Annotations\PhpParser**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\PhpParser.php at line 30#L30 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\PhpParser.php at line 30</a>

#Class PhpParser#

**PhpParser**




- - -

<p class="signature">public final  class **PhpParser**</p>

<div class="comment" id="overview_description"><p>Parses a file for namespaces/use/class declarations.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dd>Christian Kaps <christian.kaps@mohiva.com></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#parseclass">parseClass</a>(\ReflectionClass class)</p><p class="description">Parses a class.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\PhpParser.php at line 59#L59 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\PhpParser.php at line 59</a>

<h3 id="parseClass()">parseClass</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>parseClass</span> (\ReflectionClass class)

<div class="details">
<p>Parses a class.</p><dl>
<dt>Parameters:</dt>
<dd>class - A <code>ReflectionClass</code> object.</dd>
<dt>Returns:</dt>
<dd>A list with use statements in the form (Alias => FQN).</dd>
</dl>
</div>

- - -

