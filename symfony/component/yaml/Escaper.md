- - -

**Symfony\Component\Yaml\Escaper**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/Yaml/Escaper.php.md#line19" class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 19</a>

# Class Escaper #

<pre class="tree">** Escaper **\n</pre>

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
<td class="type">static  Boolean</td>
<td class="description"><p class="name"><a href="#requiresDoubleQuoting()">requiresDoubleQuoting</a>(string value)</p><p class="description">Determines if a PHP value would require double quoting in YAML.</p></td>
</tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#escapeWithDoubleQuotes()">escapeWithDoubleQuotes</a>(string value)</p><p class="description">Escapes and surrounds a PHP value with double quotes.</p></td>
</tr>
<tr>
<td class="type">static  Boolean</td>
<td class="description"><p class="name"><a href="#requiresSingleQuoting()">requiresSingleQuoting</a>(string value)</p><p class="description">Determines if a PHP value would require single quoting in YAML.</p></td>
</tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#escapeWithSingleQuotes()">escapeWithSingleQuotes</a>(string value)</p><p class="description">Escapes and surrounds a PHP value with single quotes.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/Yaml/Escaper.php.md#line32" class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 32</a>

<h3 id="requiresDoubleQuoting()">requiresDoubleQuoting</h3>
```php
public static  Boolean **requiresDoubleQuoting**(string value)```
<div class="details">
<p>Determines if a PHP value would require double quoting in YAML.</p><dl>
<dt>Parameters:</dt>
<dd>value - A PHP value</dd>
<dt>Returns:</dt>
<dd>True if the value would require double quotes.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/Yaml/Escaper.php.md#line44" class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 44</a>

<h3 id="escapeWithDoubleQuotes()">escapeWithDoubleQuotes</h3>
```php
public static  string **escapeWithDoubleQuotes**(string value)```
<div class="details">
<p>Escapes and surrounds a PHP value with double quotes.</p><dl>
<dt>Parameters:</dt>
<dd>value - A PHP value</dd>
<dt>Returns:</dt>
<dd>The quoted, escaped string</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/Yaml/Escaper.php.md#line56" class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 56</a>

<h3 id="requiresSingleQuoting()">requiresSingleQuoting</h3>
```php
public static  Boolean **requiresSingleQuoting**(string value)```
<div class="details">
<p>Determines if a PHP value would require single quoting in YAML.</p><dl>
<dt>Parameters:</dt>
<dd>value - A PHP value</dd>
<dt>Returns:</dt>
<dd>True if the value would require single quotes.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/Yaml/Escaper.php.md#line68" class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Escaper.php at line 68</a>

<h3 id="escapeWithSingleQuotes()">escapeWithSingleQuotes</h3>
```php
public static  string **escapeWithSingleQuotes**(string value)```
<div class="details">
<p>Escapes and surrounds a PHP value with single quotes.</p><dl>
<dt>Parameters:</dt>
<dd>value - A PHP value</dd>
<dt>Returns:</dt>
<dd>The quoted, escaped string</dd>
</dl>
</div>

- - -

