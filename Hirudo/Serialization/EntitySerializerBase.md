

- - -

**Hirudo\Serialization\EntitySerializerBase**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/EntitySerializerBase.php#L29" target='_blank'>framework\hirudo\Hirudo\Serialization\EntitySerializerBase.php at line 29</a>

#Class EntitySerializerBase#

**EntitySerializerBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Serialization/Impl/Json/EntitySerializerJSON.md">Hirudo\Serialization\Impl\Json\EntitySerializerJSON</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>EntitySerializerBase</span></p>

<div class="comment" id="overview_description"><p>A base class for entity serialization.</p></div>



<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new entity serializer.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#serialize">serialize</a>(mixed entity)</p><p class="description">Serializes an entity into a string.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#doserialize">doSerialize</a>(array array)</p><p class="description">This is the abstract method to be implemented by any serializer, it receives
an ssociative array representing the entity making it easier to create the
string representation.</p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/EntitySerializerBase.php#L36" target='_blank'>framework\hirudo\Hirudo\Serialization\EntitySerializerBase.php at line 36</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a new entity serializer.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/EntitySerializerBase.php#L46" target='_blank'>framework\hirudo\Hirudo\Serialization\EntitySerializerBase.php at line 46</a>

<h3 id="serialize()">serialize</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>serialize</span> (mixed entity)

<div class="details">
<p>Serializes an entity into a string.</p><dl>
<dt>Parameters:</dt>
<dd>entity - The entity to be serialized.</dd>
<dt>Returns:</dt>
<dd>The string representing the entity.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/EntitySerializerBase.php#L60" target='_blank'>framework\hirudo\Hirudo\Serialization\EntitySerializerBase.php at line 60</a>

<h3 id="doSerialize()">doSerialize</h3>
<span class='k'>protected abstract </span> <span class='nx'>string</span> <span class='nf'>doSerialize</span> (array array)

<div class="details">
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

