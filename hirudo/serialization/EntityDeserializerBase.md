- - -

**Hirudo\Serialization\EntityDeserializerBase**
<div class="location">framework\hirudo\Hirudo\Serialization\EntityDeserializerBase.php at line 29</div>
#Class EntityDeserializerBase#

**EntityDeserializerBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/impl/json/entitydeserializerjson.html">Hirudo\Serialization\Impl\Json\EntityDeserializerJSON</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **EntityDeserializerBase**</p>

<div class="comment" id="overview_description"><p>Base class for entity de-serializers.</p></div>

- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new entity de-serializer.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#deserialize">deserialize</a>(string class, string string)</p><p class="description">Converts the given string into an entity of the given class.</p></td>
</tr>
<tr>
<td class="type">protected abstract  array</td>
<td class="description"><p class="name"><a href="#convertStringToArray">convertStringToArray</a>(string string)</p><p class="description">This is the abstract method to be implemented by any de-serializer, it receives
an string to be converted into an associative array which will make easier
the conversion into an entity.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Serialization\EntityDeserializerBase.php at line 36</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
<p>Creates a new entity de-serializer.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Serialization\EntityDeserializerBase.php at line 48</div>
<h3 id="deserialize()">deserialize</h3>
```php
public  mixed **deserialize**(string class, string string)```
<div class="details">
<p>Converts the given string into an entity of the given class.</p><dl>
<dt>Parameters:</dt>
<dd>class - The class in which the string will be converted.</dd>
<dd>string - The string that will be converted into the given class.</dd>
<dt>Returns:</dt>
<dd>An instance of the given class.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Serialization\EntityDeserializerBase.php at line 67</div>
<h3 id="convertStringToArray()">convertStringToArray</h3>
```php
protected abstract  array **convertStringToArray**(string string)```
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

