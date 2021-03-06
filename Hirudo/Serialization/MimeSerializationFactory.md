

- - -

**Hirudo\Serialization\MimeSerializationFactory**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Serialization/MimeSerializationFactory.php#L32" target='_blank'>framework\Hirudo\Serialization\MimeSerializationFactory.php at line 32</a>

#Class MimeSerializationFactory#

**MimeSerializationFactory**




- - -

<p><strong>public  class</strong> <span>MimeSerializationFactory</span></p>

<div class="comment" id="overview_description"><p>A default SerializationFactory implementation. This one creates
the serializer and the de-serializer based on a mime type.</p><p>If the mime given to request the serializer or de-serializer has a slash ('/'),
the text before it will be ignored, so if $mimeType is "application/json", only the
"json" part of the string will be taken into account.</p></div>



<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getmime">getMime</a>(mixed mimeType)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntitySerializerBase.md>EntitySerializerBase</a></span></td>
<td class="description"><p class="name"><a href="#getserializer">getSerializer</a>(string mimeType)</p><p class="description">Gets a Serializer based on the given mime type.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntityDeserializerBase.md>EntityDeserializerBase</a></span></td>
<td class="description"><p class="name"><a href="#getdeserializer">getDeserializer</a>(string mimeType)</p><p class="description">Gets a de-Serializer based on the given mime type.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Serialization/MimeSerializationFactory.php#L37" target='_blank'>framework\Hirudo\Serialization\MimeSerializationFactory.php at line 37</a>

<h3 id="getMime()">getMime</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getMime</span> (mixed mimeType)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Serialization/MimeSerializationFactory.php#L49" target='_blank'>framework\Hirudo\Serialization\MimeSerializationFactory.php at line 49</a>

<h3 id="getSerializer()">getSerializer</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntitySerializerBase.md>EntitySerializerBase</a></span> <span class='nf'>getSerializer</span> (string mimeType)

<div class="details">
<p>Gets a Serializer based on the given mime type.</p><dl>
<dt>Parameters:</dt>
<dd>mimeType - A string with the mime type.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Serialization/MimeSerializationFactory.php#L66" target='_blank'>framework\Hirudo\Serialization\MimeSerializationFactory.php at line 66</a>

<h3 id="getDeserializer()">getDeserializer</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntityDeserializerBase.md>EntityDeserializerBase</a></span> <span class='nf'>getDeserializer</span> (string mimeType)

<div class="details">
<p>Gets a de-Serializer based on the given mime type.</p>
</div>

- - -

