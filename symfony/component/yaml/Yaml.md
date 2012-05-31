
- - -

**Symfony\Component\Yaml\Yaml**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/yaml/yaml.php#L23 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 23</a>

#Class Yaml#

**Yaml**




- - -

<p class="signature">public  class **Yaml**</p>

<div class="comment" id="overview_description"><p>Yaml offers convenience methods to load and dump YAML.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#enablePhpParsing"> $enablePhpParsing</a>
                                </p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#enablephpparsing">enablePhpParsing</a>()</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#parse">parse</a>(string input)</p><p class="description">Parses YAML into a PHP array.
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#dump">dump</a>(array array, integer inline)</p><p class="description">Dumps a PHP array to a YAML string.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/yaml/yaml.php#L27 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 27</a>

<h3 id="enablePhpParsing()">enablePhpParsing</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>enablePhpParsing</span> ()

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/yaml/yaml.php#L51 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 51</a>

<h3 id="parse()">parse</h3>
<span class='k'>static </span> <span class='nx'>array</span> <span class='nf'>parse</span> (string input)

<div class="details">
<p>Parses YAML into a PHP array.</p><p>The parse method, when supplied with a YAML stream (string or file),
will do its best to convert YAML in a file into a PHP array.</p><p>Usage:
<code>
$array = Yaml::parse('config.yml');
print_r($array);
</code></p><dl>
<dt>Parameters:</dt>
<dd>input - Path to a YAML file or a string containing YAML</dd>
<dt>Returns:</dt>
<dd>The YAML converted to a PHP array</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/yaml/exception/parseexception.html">ParseException</a> - If the YAML is not valid</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/yaml/yaml.php#L103 class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 103</a>

<h3 id="dump()">dump</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>dump</span> (array array, integer inline)

<div class="details">
<p>Dumps a PHP array to a YAML string.</p><p>The dump method, when supplied with an array, will do its best
to convert the array into friendly YAML.</p><dl>
<dt>Parameters:</dt>
<dd>array - PHP array</dd>
<dd>inline - The level where you switch to inline YAML</dd>
<dt>Returns:</dt>
<dd>A YAML string representing the original PHP array</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

