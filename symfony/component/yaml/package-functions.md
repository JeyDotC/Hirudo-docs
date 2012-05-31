- - -

#Functions#

- - -

<table id="summary_function" class="title">
<tr><th colspan="2" class="title">Function Summary</th></tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#parseScalar">parseScalar</a>(scalar scalar, string delimiters, array stringDelimiters, integer &$i, Boolean evaluate)</p><p class="description">Parses a scalar to a YAML string.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#unescapeCharacter">unescapeCharacter</a>(string value)</p><p class="description">Unescapes a character that was found in a double-quoted string</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#unescapeDoubleQuotedString">unescapeDoubleQuotedString</a>(string value)</p><p class="description">Unescapes a double quoted string.</p></td>
</tr>
</table>

<h2 id="detail_function">Function Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Inline.php at line 106</div>
<h3 id="parseScalar()">parseScalar</h3>
```php
public static  string **parseScalar**(scalar scalar, string delimiters, array stringDelimiters, integer &$i, Boolean evaluate)```
<div class="details">
<p>Parses a scalar to a YAML string.</p>
<dl>
<dt>Returns:</dt>
<dd>A YAML string</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/yaml/exception/parseexception.html">ParseException</a> - When malformed inline YAML string is parsed</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Unescaper.php at line 51</div>
<h3 id="unescapeCharacter()">unescapeCharacter</h3>
```php
public  string **unescapeCharacter**(string value)```
<div class="details">
<p>Unescapes a character that was found in a double-quoted string</p>
<dl>
<dt>Parameters:</dt>
<dd>value - An escaped character</dd>
<dt>Returns:</dt>
<dd>The unescaped character</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Unescaper.php at line 33</div>
<h3 id="unescapeDoubleQuotedString()">unescapeDoubleQuotedString</h3>
```php
public  string **unescapeDoubleQuotedString**(string value)```
<div class="details">
<p>Unescapes a double quoted string.</p>
<dl>
<dt>Parameters:</dt>
<dd>value - A double quoted string.</dd>
<dt>Returns:</dt>
<dd>The unescaped string.</dd>
</dl>
</div>

- - -

