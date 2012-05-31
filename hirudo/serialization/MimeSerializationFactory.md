- - -

**Hirudo\Serialization\MimeSerializationFactory**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Serialization/MimeSerializationFactory.php.md#line34" class="location">framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 34</a>

# Class MimeSerializationFactory #

<pre class="tree">** MimeSerializationFactory **\n</pre>

- - -

<p class="signature">public  class **MimeSerializationFactory**</p>

<div class="comment" id="overview_description"><p>A default SerializationFactory implementation. This one creates
the serializer and the de-serializer based on a mime type.</p><p>If the mime given to request the serializer or de-serializer has a slash ('/'),
the text before it will be ignored, so if $mimeType is "application/json", only the
"json" part of the string will be taken into account.</p></div>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getMime()">getMime</a>(mixed mimeType)</p></td>
</tr>
<tr>
<td class="type"> <a href="../../hirudo/serialization/entityserializerbase.html">EntitySerializerBase</a></td>
<td class="description"><p class="name"><a href="#getSerializer()">getSerializer</a>(string mimeType)</p><p class="description">Gets a Serializer based on the given mime type.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../hirudo/serialization/entitydeserializerbase.html">EntityDeserializerBase</a></td>
<td class="description"><p class="name"><a href="#getDeserializer()">getDeserializer</a>(string mimeType)</p><p class="description">Gets a de-Serializer based on the given mime type.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Serialization/MimeSerializationFactory.php.md#line39" class="location">framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 39</a>

<h3 id="getMime()">getMime</h3>
```php
public  void **getMime**(mixed mimeType)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Serialization/MimeSerializationFactory.php.md#line51" class="location">framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 51</a>

<h3 id="getSerializer()">getSerializer</h3>
```php
public  <a href="../../hirudo/serialization/entityserializerbase.html">EntitySerializerBase</a> **getSerializer**(string mimeType)```
<div class="details">
<p>Gets a Serializer based on the given mime type.</p><dl>
<dt>Parameters:</dt>
<dd>mimeType - A string with the mime type.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Serialization/MimeSerializationFactory.php.md#line69" class="location">framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 69</a>

<h3 id="getDeserializer()">getDeserializer</h3>
```php
public  <a href="../../hirudo/serialization/entitydeserializerbase.html">EntityDeserializerBase</a> **getDeserializer**(string mimeType)```
<div class="details">
<p>Gets a de-Serializer based on the given mime type.</p></div>

- - -

