- - -

#Functions#

- - -

<table id="summary_function" class="title">
<tr><th colspan="2" class="title">Function Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#parseScalar">parseScalar</a>(scalar scalar, string delimiters, array stringDelimiters, integer &$i, Boolean evaluate)</p><p class="description">Parses a scalar to a YAML string.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#unescapeCharacter">unescapeCharacter</a>(string value)</p><p class="description">Unescapes a character that was found in a double-quoted string</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#unescapeDoubleQuotedString">unescapeDoubleQuotedString</a>(string value)</p><p class="description">Unescapes a double quoted string.</p></td>
</tr>
</table>

<h2 id="detail_function">Function Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Inline.php#L106" >framework\libs\symfony-components\Symfony\Component\Yaml\Inline.php at line 106</a>

<h3 id="parseScalar()">parseScalar</h3>
<span class='k'>static </span> <span class='nx'>string</span> parseScalar (scalar scalar, string delimiters, array stringDelimiters, integer &$i, Boolean evaluate)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Unescaper.php#L51" >framework\libs\symfony-components\Symfony\Component\Yaml\Unescaper.php at line 51</a>

<h3 id="unescapeCharacter()">unescapeCharacter</h3>
<span class='k'></span> <span class='nx'>string</span> unescapeCharacter (string value)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Unescaper.php#L33" >framework\libs\symfony-components\Symfony\Component\Yaml\Unescaper.php at line 33</a>

<h3 id="unescapeDoubleQuotedString()">unescapeDoubleQuotedString</h3>
<span class='k'></span> <span class='nx'>string</span> unescapeDoubleQuotedString (string value)

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

