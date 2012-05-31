
- - -

**Symfony\Component\Yaml\Parser**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\Yaml\Parser.php at line 20#L20 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Parser.php at line 20</a>

#Class Parser#

**Parser**




- - -

<p class="signature">public  class **Parser**</p>

<div class="comment" id="overview_description"><p>Parser parses YAML strings to convert them to PHP arrays.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(integer offset)</p><p class="description">Constructor</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#parse">parse</a>(string value)</p><p class="description">Parses a YAML string to a PHP value.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\Yaml\Parser.php at line 33#L33 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Parser.php at line 33</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (integer offset)

<div class="details">
<p>Constructor</p><dl>
<dt>Parameters:</dt>
<dd>offset - The offset of YAML document (used for line numbers in error messages)</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\Yaml\Parser.php at line 47#L47 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Parser.php at line 47</a>

<h3 id="parse()">parse</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>parse</span> (string value)

<div class="details">
<p>Parses a YAML string to a PHP value.</p><dl>
<dt>Parameters:</dt>
<dd>value - A YAML string</dd>
<dt>Returns:</dt>
<dd>A PHP value</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/yaml/exception/parseexception.html">ParseException</a> - If the YAML is not valid</dd>
</dl>
</div>

- - -

