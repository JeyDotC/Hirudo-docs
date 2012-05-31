- - -

**Hirudo\Serialization\Impl\Json\EntityDeserializerJSON**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Serialization/Impl/Json/EntityDeserializerJSON.php.md#line32" class="location">framework\hirudo\Hirudo\Serialization\Impl\Json\EntityDeserializerJSON.php at line 32</a>

# Class EntityDeserializerJSON #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entitydeserializerbase.html">EntityDeserializerBase</a>\n    *** EntityDeserializerJSON **\n</pre>

- - -

<p class="signature">public  class **EntityDeserializerJSON**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entitydeserializerbase.html">EntityDeserializerBase</a>

</p>

<div class="comment" id="overview_description"><p>JSON Implementation of the EntityDeserializerBase. Converts a JSON string
into an entity of a given class.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#convertStringToArray()">convertStringToArray</a>(string string)</p><p class="description">This is the abstract method to be implemented by any de-serializer, it receives
an string to be converted into an associative array which will make easier
the conversion into an entity.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Serialization\EntityDeserializerBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entitydeserializerbase.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entitydeserializerbase.html#convertStringToArray()">convertStringToArray</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entitydeserializerbase.html#deserialize()">deserialize</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Serialization/Impl/Json/EntityDeserializerJSON.php.md#line34" class="location">framework\hirudo\Hirudo\Serialization\Impl\Json\EntityDeserializerJSON.php at line 34</a>

<h3 id="convertStringToArray()">convertStringToArray</h3>
```php
protected  array **convertStringToArray**(string string)```
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

