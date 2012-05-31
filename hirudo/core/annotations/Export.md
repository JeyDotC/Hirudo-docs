- - -

**Hirudo\Core\Annotations\Export**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Annotations/Export.php.md#line34" class="location">framework\hirudo\Hirudo\Core\Annotations\Export.php at line 34</a>

# Class Export #

<pre class="tree">** Export **\n</pre>

- - -

<p class="signature">public final  class **Export**</p>

<div class="comment" id="overview_description"><p>Signals a class, method or property as a service exporter.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Annotation.</dt>
<dt>Target({"CLASS",:</dt>
<dd>"METHOD", "PROPERTY"})</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#factory">$factory</a></p><p class="description">An optional factory method which is in charge of returning
an instance of the service.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#id">$id</a></p><p class="description">The id of the service to be exported.</p></td>
</tr>
</table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Annotations/Export.php.md#line49" class="location">framework\hirudo\Hirudo\Core\Annotations\Export.php at line 49</a>

<h3 id="factory">factory</h3>
```php
public  string **$factory** = &quot;&quot;```
<div class="details">
<p>An optional factory method which is in charge of returning
an instance of the service.</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Annotations/Export.php.md#line41" class="location">framework\hirudo\Hirudo\Core\Annotations\Export.php at line 41</a>

<h3 id="id">id</h3>
```php
public  string **$id** = &quot;&quot;```
<div class="details">
<p>The id of the service to be exported.</p></div>

- - -

