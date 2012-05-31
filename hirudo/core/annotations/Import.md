
- - -

**Hirudo\Core\Annotations\Import**
<div class="location">framework\hirudo\Hirudo\Core\Annotations\Import.php at line 35</div>
#Class Import#

**Import**


- - -

<p class="signature">public final  class **Import**</p>

<div class="comment" id="overview_description"><p>This annotation marks a method or property as a dependency requester, a point in which
to inject a dependency.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Annotation.</dt>
<dt>Target({"METHOD",:</dt>
<dd>"PROPERTY"})</dd>
</dl>

- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> string The fully qualified name of the class to be imported.</td>
<td class="description"><p class="name"><a href="#classname">$className</a></p><p class="description">A dependency class name. </p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#id">$id</a></p><p class="description">The id of the dependency to be injected.
</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\hirudo\Hirudo\Core\Annotations\Import.php at line 64</div>
<h3 id="className">className</h3>

public  string The fully qualified name of the class to be imported. $className = null
<div class="details">
<p>A dependency class name. This is useful if the dependency class is instantiable
and direct instantiation is acceptable. To import interfaces, abstract
classes or classes with some kind of special instatiation issue
(like factory methods), use Import::$id instead and export the dependency
class with the @Export annotation.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Annotations\Import.php at line 53</div>
<h3 id="id">id</h3>

public  string $id = null
<div class="details">
<p>The id of the dependency to be injected.</p><p>If this attribute is null, the dependency injector shall determine the class
of the requested object and create a new instance to inject it. The way the class is
determined is like below:</p><p>If this annotation is applied to a method, the method's type hinting will be used
to determine the class of the dependency.</p><p>If this nanotation is applied to a property, the className property of this annotation
must be set to the fully qualified class name, this is a way to avoid the efford
of determining the class name based on the doc blocks.</p></div>

- - -

