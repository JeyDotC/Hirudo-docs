

- - -

**Default namespace\PseudoEnum**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Enum.php#L37" target='_blank'>framework\hirudo\Hirudo\Lang\Enum.php at line 37</a>

#Class PseudoEnum#

**PseudoEnum**




- - -

<p><strong>public abstract  class</strong> <span>PseudoEnum</span></p>

<div class="comment" id="overview_description"><p><p>A base class for simple Enum representation. It gives some utility methods
commonly associated to the enums in other languages.</p></p><p><p>To make an enum class just extend this class and add the enum constants, like this:</p><p><code>
class MyEnum extends PseudoEnum {
const AN_ENUM_VALUE = 0;
const OTHER_ENUM_VALUE = 1;
const AND_OTHER_ENUM_VALUE = 2;
}
</code></p></p></div>



<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#valuebelongs">valueBelongs</a>(string|number value)</p><p class="description">Says if the given value belongs to the set of values  of this enum.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#namebelongs">nameBelongs</a>(string|number value, mixed name)</p><p class="description">Says if there is a constant with the given name for this enum.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#valuetostring">valueToString</a>(string|number value)</p><p class="description">Returns the constant name corresponding to the given value.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string|number</span></td>
<td class="description"><p class="name"><a href="#stringtovalue">stringToValue</a>(string string)</p><p class="description">Returns a value by the corresponding name.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#values">values</a>()</p><p class="description">Gets an array with all the constants of the enum.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Enum.php#L45" target='_blank'>framework\hirudo\Hirudo\Lang\Enum.php at line 45</a>

<h3 id="valueBelongs()">valueBelongs</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>valueBelongs</span> (string|number value)

<div class="details">
<p>Says if the given value belongs to the set of values  of this enum.</p><dl>
<dt>Parameters:</dt>
<dd>value - The value which we want to know if exists for this enum.</dd>
<dt>Returns:</dt>
<dd>True if the value exists for this enum, false otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Enum.php#L58" target='_blank'>framework\hirudo\Hirudo\Lang\Enum.php at line 58</a>

<h3 id="nameBelongs()">nameBelongs</h3>
<span class='k'>static </span> <span class='nx'>boolean</span> <span class='nf'>nameBelongs</span> (string|number value, mixed name)

<div class="details">
<p>Says if there is a constant with the given name for this enum.</p><dl>
<dt>Parameters:</dt>
<dd>value - The name which we want to know if exists for this enum.</dd>
<dt>Returns:</dt>
<dd>True if the name exists for this enum, false otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Enum.php#L71" target='_blank'>framework\hirudo\Hirudo\Lang\Enum.php at line 71</a>

<h3 id="valueToString()">valueToString</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>valueToString</span> (string|number value)

<div class="details">
<p>Returns the constant name corresponding to the given value.</p><dl>
<dt>Parameters:</dt>
<dd>value - The value which we want to know name in the enum list.</dd>
<dt>Returns:</dt>
<dd>The name corresponding to the given value.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Enum.php#L84" target='_blank'>framework\hirudo\Hirudo\Lang\Enum.php at line 84</a>

<h3 id="stringToValue()">stringToValue</h3>
<span class='k'>static </span> <span class='nx'>string|number</span> <span class='nf'>stringToValue</span> (string string)

<div class="details">
<p>Returns a value by the corresponding name.</p><dl>
<dt>Parameters:</dt>
<dd>string - The name of the constant.</dd>
<dt>Returns:</dt>
<dd>The value corresponding to the constant with the given name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Enum.php#L96" target='_blank'>framework\hirudo\Hirudo\Lang\Enum.php at line 96</a>

<h3 id="values()">values</h3>
<span class='k'>static </span> <span class='nx'>array</span> <span class='nf'>values</span> ()

<div class="details">
<p>Gets an array with all the constants of the enum.</p><dl>
<dt>Returns:</dt>
<dd>An asociative array which keys are the name and values are the values of all this class's constants.</dd>
</dl>

</div>

- - -
