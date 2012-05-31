
- - -

**Hirudo\Serialization\EntitySerializerBase**
<div class="location">framework\hirudo\Hirudo\Serialization\EntitySerializerBase.php at line 29</div>
#Class EntitySerializerBase#

**EntitySerializerBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/impl/json/entityserializerjson.html">Hirudo\Serialization\Impl\Json\EntitySerializerJSON</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **EntitySerializerBase**</p>

<div class="comment" id="overview_description"><p>A base class for entity serialization.</p></div>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new entity serializer.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#serialize">serialize</a>(mixed entity)</p><p class="description">Serializes an entity into a string.</p></td>
</tr>
<tr>
<td class="type"> protected abstract  string</td>
<td class="description"><p class="name"><a href="#doserialize">doSerialize</a>(array array)</p><p class="description">This is the abstract method to be implemented by any serializer, it receives
an ssociative array representing the entity making it easier to create the
string representation.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Serialization\EntitySerializerBase.php at line 36</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**()
```
<div class="details">
<p>Creates a new entity serializer.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Serialization\EntitySerializerBase.php at line 46</div>
<h3 id="serialize()">serialize</h3>

public  string **serialize** (mixed entity)<div class="details">
<p>Serializes an entity into a string.</p><dl>
<dt>Parameters:</dt>
<dd>entity - The entity to be serialized.</dd>
<dt>Returns:</dt>
<dd>The string representing the entity.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Serialization\EntitySerializerBase.php at line 60</div>
<h3 id="doSerialize()">doSerialize</h3>

protected abstract  string **doSerialize** (array array)<div class="details">
<p>This is the abstract method to be implemented by any serializer, it receives
an ssociative array representing the entity making it easier to create the
string representation.</p><dl>
<dt>Parameters:</dt>
<dd>array - The associative array that represents the entity.</dd>
<dt>Returns:</dt>
<dd>The string that represents the entity.</dd>
</dl>
</div>

- - -

