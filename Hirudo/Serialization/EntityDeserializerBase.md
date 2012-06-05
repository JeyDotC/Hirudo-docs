

- - -

**Hirudo\Serialization\EntityDeserializerBase**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/EntityDeserializerBase.php#L29" target='_blank'>framework\hirudo\Hirudo\Serialization\EntityDeserializerBase.php at line 29</a>

#Class EntityDeserializerBase#

**EntityDeserializerBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/Impl/Json/EntityDeserializerJSON.md">Hirudo\Serialization\Impl\Json\EntityDeserializerJSON</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>EntityDeserializerBase</span></p>

<div class="comment" id="overview_description"><p>Base class for entity de-serializers.</p></div>



- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new entity de-serializer.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#deserialize">deserialize</a>(string class, string string)</p><p class="description">Converts the given string into an entity of the given class.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#convertstringtoarray">convertStringToArray</a>(string string)</p><p class="description">This is the abstract method to be implemented by any de-serializer, it receives
an string to be converted into an associative array which will make easier
the conversion into an entity.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/EntityDeserializerBase.php#L36" target='_blank'>framework\hirudo\Hirudo\Serialization\EntityDeserializerBase.php at line 36</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a new entity de-serializer.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/EntityDeserializerBase.php#L48" target='_blank'>framework\hirudo\Hirudo\Serialization\EntityDeserializerBase.php at line 48</a>

<h3 id="deserialize()">deserialize</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>deserialize</span> (string class, string string)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/EntityDeserializerBase.php#L67" target='_blank'>framework\hirudo\Hirudo\Serialization\EntityDeserializerBase.php at line 67</a>

<h3 id="convertStringToArray()">convertStringToArray</h3>
<span class='k'>protected abstract </span> <span class='nx'>array</span> <span class='nf'>convertStringToArray</span> (string string)

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

