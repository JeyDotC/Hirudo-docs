
- - -

**Hirudo\Serialization\MimeSerializationFactory**
<div class="location">framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 34</div>
#Class MimeSerializationFactory#

**MimeSerializationFactory**


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
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#getmime">getMime</a>(mixed mimeType)</p></td>
</tr>
<tr>
<td class="type">  <a href="../../hirudo/serialization/entityserializerbase.html">EntitySerializerBase</a></td>
<td class="description"><p class="name"><a href="#getserializer">getSerializer</a>(string mimeType)</p><p class="description">Gets a Serializer based on the given mime type.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../hirudo/serialization/entitydeserializerbase.html">EntityDeserializerBase</a></td>
<td class="description"><p class="name"><a href="#getdeserializer">getDeserializer</a>(string mimeType)</p><p class="description">Gets a de-Serializer based on the given mime type.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 39</div>
<h3 id="getMime()">getMime</h3>

public  void **getMime** (mixed mimeType)<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 51</div>
<h3 id="getSerializer()">getSerializer</h3>

public  <a href="../../hirudo/serialization/entityserializerbase.html">EntitySerializerBase</a> **getSerializer** (string mimeType)<div class="details">
<p>Gets a Serializer based on the given mime type.</p><dl>
<dt>Parameters:</dt>
<dd>mimeType - A string with the mime type.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 69</div>
<h3 id="getDeserializer()">getDeserializer</h3>

public  <a href="../../hirudo/serialization/entitydeserializerbase.html">EntityDeserializerBase</a> **getDeserializer** (string mimeType)<div class="details">
<p>Gets a de-Serializer based on the given mime type.</p></div>

- - -

