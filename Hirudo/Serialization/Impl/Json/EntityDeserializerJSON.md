

- - -

**Hirudo\Serialization\Impl\Json\EntityDeserializerJSON**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Serialization/Impl/Json/EntityDeserializerJSON.php#L32" target='_blank'>framework\Hirudo\Serialization\Impl\Json\EntityDeserializerJSON.php at line 32</a>

#Class EntityDeserializerJSON#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntityDeserializerBase.md">EntityDeserializerBase</a>
 &gt; **EntityDeserializerJSON**




- - -

<p><strong>public  class</strong> <span>EntityDeserializerJSON</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntityDeserializerBase.md">EntityDeserializerBase</a>

</p>

<div class="comment" id="overview_description"><p>JSON Implementation of the EntityDeserializerBase. Converts a JSON string
into an entity of a given class.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#convertstringtoarray">convertStringToArray</a>(string string)</p><p class="description">This is the abstract method to be implemented by any de-serializer, it receives
an string to be converted into an associative array which will make easier
the conversion into an entity.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Serialization\EntityDeserializerBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntityDeserializerBase.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntityDeserializerBase.md#convertstringtoarray">convertStringToArray</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/EntityDeserializerBase.md#deserialize">deserialize</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Serialization/Impl/Json/EntityDeserializerJSON.php#L34" target='_blank'>framework\Hirudo\Serialization\Impl\Json\EntityDeserializerJSON.php at line 34</a>

<h3 id="convertStringToArray()">convertStringToArray</h3>
<span class='k'>protected </span> <span class='nx'>array</span> <span class='nf'>convertStringToArray</span> (string string)

<div class="details">
<p>This is the abstract method to be implemented by any de-serializer, it receives
an string to be converted into an associative array which will make easier
the conversion into an entity.</p><dl>
<dt>Parameters:</dt>
<dd>string - The associative array that represents the entity.</dd>
<dt>Returns:</dt>
<dd>An associative array that represents the entity.</dd>
</dl>

</div>

- - -

