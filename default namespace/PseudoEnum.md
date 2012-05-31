- - -

**Default namespace\PseudoEnum**
<div class="location">framework\hirudo\Hirudo\Lang\Enum.php at line 37</div>
#Class PseudoEnum#

**PseudoEnum**


- - -

<p class="signature">public abstract  class **PseudoEnum**</p>

<div class="comment" id="overview_description"><p><p>A base class for simple Enum representation. It gives some utility methods
commonly associated to the enums in other languages.</p></p><p><p>To make an enum class just extend this class and add the enum constants, like this:</p><p><code>
class MyEnum extends PseudoEnum {
const AN_ENUM_VALUE = 0;
const OTHER_ENUM_VALUE = 1;
const AND_OTHER_ENUM_VALUE = 2;
}
</code></p></p></div>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  boolean</td>
<td class="description"><p class="name"><a href="#valueBelongs">valueBelongs</a>(string|number value)</p><p class="description">Says if the given value belongs to the set of values  of this enum.</p></td>
</tr>
<tr>
<td class="type">static  boolean</td>
<td class="description"><p class="name"><a href="#nameBelongs">nameBelongs</a>(string|number value, mixed name)</p><p class="description">Says if there is a constant with the given name for this enum.</p></td>
</tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#valueToString">valueToString</a>(string|number value)</p><p class="description">Returns the constant name corresponding to the given value.</p></td>
</tr>
<tr>
<td class="type">static  string|number</td>
<td class="description"><p class="name"><a href="#stringToValue">stringToValue</a>(string string)</p><p class="description">Returns a value by the corresponding name.</p></td>
</tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#values">values</a>()</p><p class="description">Gets an array with all the constants of the enum.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Lang\Enum.php at line 45</div>
<h3 id="valueBelongs()">valueBelongs</h3>

```php
public static  boolean **valueBelongs**(string|number value)
```
<div class="details">
<p>Says if the given value belongs to the set of values  of this enum.</p><dl>
<dt>Parameters:</dt>
<dd>value - The value which we want to know if exists for this enum.</dd>
<dt>Returns:</dt>
<dd>True if the value exists for this enum, false otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Enum.php at line 58</div>
<h3 id="nameBelongs()">nameBelongs</h3>

```php
public static  boolean **nameBelongs**(string|number value, mixed name)
```
<div class="details">
<p>Says if there is a constant with the given name for this enum.</p><dl>
<dt>Parameters:</dt>
<dd>value - The name which we want to know if exists for this enum.</dd>
<dt>Returns:</dt>
<dd>True if the name exists for this enum, false otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Enum.php at line 71</div>
<h3 id="valueToString()">valueToString</h3>

```php
public static  string **valueToString**(string|number value)
```
<div class="details">
<p>Returns the constant name corresponding to the given value.</p><dl>
<dt>Parameters:</dt>
<dd>value - The value which we want to know name in the enum list.</dd>
<dt>Returns:</dt>
<dd>The name corresponding to the given value.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Enum.php at line 84</div>
<h3 id="stringToValue()">stringToValue</h3>

```php
public static  string|number **stringToValue**(string string)
```
<div class="details">
<p>Returns a value by the corresponding name.</p><dl>
<dt>Parameters:</dt>
<dd>string - The name of the constant.</dd>
<dt>Returns:</dt>
<dd>The value corresponding to the constant with the given name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Enum.php at line 96</div>
<h3 id="values()">values</h3>

```php
public static  array **values**()
```
<div class="details">
<p>Gets an array with all the constants of the enum.</p><dl>
<dt>Returns:</dt>
<dd>An asociative array which keys are the name and values are the values of all this class's constants.</dd>
</dl>
</div>

- - -

