
- - -

**Symfony\Component\Yaml\Yaml**
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 23</div>
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
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#enablephpparsing">$enablePhpParsing</a></p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#enablephpparsing">enablePhpParsing</a>()</p></td>
</tr>
<tr>
<td class="type"> static  array</td>
<td class="description"><p class="name"><a href="#parse">parse</a>(string input)</p><p class="description">Parses YAML into a PHP array.
</p></td>
</tr>
<tr>
<td class="type"> static  string</td>
<td class="description"><p class="name"><a href="#dump">dump</a>(array array, integer inline)</p><p class="description">Dumps a PHP array to a YAML string.
</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 25</div>
<h3 id="enablePhpParsing">enablePhpParsing</h3>

public static  mixed $enablePhpParsing = false
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 27</div>
<h3 id="enablePhpParsing()">enablePhpParsing</h3>

public static  void **enablePhpParsing** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 51</div>
<h3 id="parse()">parse</h3>

public static  array **parse** (string input)<div class="details">
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

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Yaml.php at line 103</div>
<h3 id="dump()">dump</h3>

public static  string **dump** (array array, integer inline)<div class="details">
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

