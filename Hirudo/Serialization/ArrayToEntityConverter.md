

- - -

**Hirudo\Serialization\ArrayToEntityConverter**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/ArrayToEntityConverter.php#L29" target='_blank'>framework\hirudo\Hirudo\Serialization\ArrayToEntityConverter.php at line 29</a>

#Class ArrayToEntityConverter#

**ArrayToEntityConverter**




- - -

<p><strong>public  class</strong> <span>ArrayToEntityConverter</span></p>

<div class="comment" id="overview_description"><p>Transforms an array into an object of a given class.</p></div>



<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#convert">convert</a>(array array, mixed objectOrClassName)</p><p class="description">Converts an array into the given object. </p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Serialization/ArrayToEntityConverter.php#L44" target='_blank'>framework\hirudo\Hirudo\Serialization\ArrayToEntityConverter.php at line 44</a>

<h3 id="convert()">convert</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>convert</span> (array array, mixed objectOrClassName)

<div class="details">
<p>Converts an array into the given object.</p><p>The collection must be an associative array which keys will correspond to
a property in the object.</p><dl>
<dt>Parameters:</dt>
<dd>array - The associative array to be converted into an object.</dd>
<dd>objectOrClassName - A classname in which the given array will be converted.</dd>
<dt>Returns:</dt>
<dd>An instance of the given class.</dd>
</dl>

</div>

- - -

