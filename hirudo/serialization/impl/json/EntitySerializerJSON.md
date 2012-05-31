
- - -

**Hirudo\Serialization\Impl\Json\EntitySerializerJSON**
<div class="location">framework\hirudo\Hirudo\Serialization\Impl\Json\EntitySerializerJSON.php at line 32</div>
#Class EntitySerializerJSON#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entityserializerbase.html">EntitySerializerBase</a>
    ***EntitySerializerJSON**


- - -

<p class="signature">public  class **EntitySerializerJSON**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entityserializerbase.html">EntitySerializerBase</a>

</p>

<div class="comment" id="overview_description"><p>JSON implementation of EntitySerializerBase. Converts the given object
into a JSON string.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> protected  string</td>
<td class="description"><p class="name"><a href="#doserialize">doSerialize</a>(array array)</p><p class="description">This is the abstract method to be implemented by any serializer, it receives
an ssociative array representing the entity making it easier to create the
string representation.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Serialization\EntitySerializerBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entityserializerbase.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entityserializerbase.html#doSerialize()">doSerialize</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entityserializerbase.html#serialize()">serialize</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Serialization\Impl\Json\EntitySerializerJSON.php at line 34</div>
<h3 id="doSerialize()">doSerialize</h3>

protected  string **doSerialize** (array array)<div class="details">
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

