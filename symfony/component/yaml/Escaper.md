
- - -

**Symfony\Component\Yaml\Escaper**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 19#L19 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 19</a>

#Class Escaper#

**Escaper**




- - -

<p class="signature">public  class **Escaper**</p>

<div class="comment" id="overview_description"><p>Escaper encapsulates escaping rules for single and double-quoted
YAML strings.</p></div>

<dl>
<dt>Author:</dt>
<dd>Matthew Lewinski <matthew@lewinski.org></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#requiresdoublequoting">requiresDoubleQuoting</a>(string value)</p><p class="description">Determines if a PHP value would require double quoting in YAML.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#escapewithdoublequotes">escapeWithDoubleQuotes</a>(string value)</p><p class="description">Escapes and surrounds a PHP value with double quotes.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#requiressinglequoting">requiresSingleQuoting</a>(string value)</p><p class="description">Determines if a PHP value would require single quoting in YAML.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#escapewithsinglequotes">escapeWithSingleQuotes</a>(string value)</p><p class="description">Escapes and surrounds a PHP value with single quotes.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 32#L32 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 32</a>

<h3 id="requiresDoubleQuoting()">requiresDoubleQuoting</h3>
<span class='k'>static </span> <span class='nx'>Boolean</span> <span class='nf'>requiresDoubleQuoting</span> (string value)

<div class="details">
<p>Determines if a PHP value would require double quoting in YAML.</p><dl>
<dt>Parameters:</dt>
<dd>value - A PHP value</dd>
<dt>Returns:</dt>
<dd>True if the value would require double quotes.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 44#L44 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 44</a>

<h3 id="escapeWithDoubleQuotes()">escapeWithDoubleQuotes</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>escapeWithDoubleQuotes</span> (string value)

<div class="details">
<p>Escapes and surrounds a PHP value with double quotes.</p><dl>
<dt>Parameters:</dt>
<dd>value - A PHP value</dd>
<dt>Returns:</dt>
<dd>The quoted, escaped string</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 56#L56 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 56</a>

<h3 id="requiresSingleQuoting()">requiresSingleQuoting</h3>
<span class='k'>static </span> <span class='nx'>Boolean</span> <span class='nf'>requiresSingleQuoting</span> (string value)

<div class="details">
<p>Determines if a PHP value would require single quoting in YAML.</p><dl>
<dt>Parameters:</dt>
<dd>value - A PHP value</dd>
<dt>Returns:</dt>
<dd>True if the value would require single quotes.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 68#L68 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 68</a>

<h3 id="escapeWithSingleQuotes()">escapeWithSingleQuotes</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>escapeWithSingleQuotes</span> (string value)

<div class="details">
<p>Escapes and surrounds a PHP value with single quotes.</p><dl>
<dt>Parameters:</dt>
<dd>value - A PHP value</dd>
<dt>Returns:</dt>
<dd>The quoted, escaped string</dd>
</dl>
</div>

- - -

