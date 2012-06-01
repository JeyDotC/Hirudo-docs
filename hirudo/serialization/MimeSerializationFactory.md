

- - -

**Hirudo\Serialization\MimeSerializationFactory**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/MimeSerializationFactory.php#L34" >framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 34</a>

#Class MimeSerializationFactory#

**MimeSerializationFactory**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>MimeSerializationFactory</span></p>

<div class="comment" id="overview_description"><p>A default SerializationFactory implementation. This one creates
the serializer and the de-serializer based on a mime type.</p><p>If the mime given to request the serializer or de-serializer has a slash ('/'),
the text before it will be ignored, so if $mimeType is "application/json", only the
"json" part of the string will be taken into account.</p></div>



- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getmime">getMime</a>(mixed mimeType)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/hirudo/serialization/entityserializerbase.html>EntitySerializerBase</a></span></td>
<td class="description"><p class="name"><a href="#getserializer">getSerializer</a>(string mimeType)</p><p class="description">Gets a Serializer based on the given mime type.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/hirudo/serialization/entitydeserializerbase.html>EntityDeserializerBase</a></span></td>
<td class="description"><p class="name"><a href="#getdeserializer">getDeserializer</a>(string mimeType)</p><p class="description">Gets a de-Serializer based on the given mime type.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/MimeSerializationFactory.php#L39" >framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 39</a>

<h3 id="getMime()">getMime</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getMime</span> (mixed mimeType)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/MimeSerializationFactory.php#L51" >framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 51</a>

<h3 id="getSerializer()">getSerializer</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/hirudo/serialization/entityserializerbase.html>EntitySerializerBase</a></span> <span class='nf'>getSerializer</span> (string mimeType)

<div class="details">
<p>Gets a Serializer based on the given mime type.</p><dl>
<dt>Parameters:</dt>
<dd>mimeType - A string with the mime type.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/MimeSerializationFactory.php#L69" >framework\hirudo\Hirudo\Serialization\MimeSerializationFactory.php at line 69</a>

<h3 id="getDeserializer()">getDeserializer</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/hirudo/serialization/entitydeserializerbase.html>EntityDeserializerBase</a></span> <span class='nf'>getDeserializer</span> (string mimeType)

<div class="details">
<p>Gets a de-Serializer based on the given mime type.</p>
</div>

- - -

