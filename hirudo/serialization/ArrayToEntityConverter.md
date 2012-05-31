- - -

**Hirudo\Serialization\ArrayToEntityConverter**
<div class="location">framework\hirudo\Hirudo\Serialization\ArrayToEntityConverter.php at line 29</div>
#Class ArrayToEntityConverter#

**ArrayToEntityConverter**


- - -

<p class="signature">public  class **ArrayToEntityConverter**</p>

<div class="comment" id="overview_description"><p>Transforms an array into an object of a given class.</p></div>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#convert">convert</a>(array array, mixed objectOrClassName)</p><p class="description">Converts an array into the given object. </p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Serialization\ArrayToEntityConverter.php at line 44</div>
<h3 id="convert()">convert</h3>
```php
public  mixed **convert**(array array, mixed objectOrClassName)```
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

