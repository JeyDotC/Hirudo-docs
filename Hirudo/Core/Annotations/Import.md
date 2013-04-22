

- - -

**Hirudo\Core\Annotations\Import**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Annotations/Import.php#L35" target='_blank'>framework\Hirudo\Core\Annotations\Import.php at line 35</a>

#Class Import#

**Import**




- - -

<p><strong>public final  class</strong> <span>Import</span></p>

<div class="comment" id="overview_description"><p>This annotation marks a method or property as a dependency requester, a point in which
to inject a dependency.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Annotation.</dt>
<dt>Target({"METHOD",:</dt>
<dd>"PROPERTY"})</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string The fully qualified name of the class to be imported.</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Annotations/Import.md#classname"> $className</a>
                                </p><p class="description">A dependency class name. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Annotations/Import.md#id"> $id</a>
                                </p><p class="description">The id of the dependency to be injected.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Annotations/Import.md#tag"> $tag</a>
                                </p><p class="description">A dependency tag. </p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Annotations/Import.php#L73" target='_blank'>framework\Hirudo\Core\Annotations\Import.php at line 73</a>

<h3 id="className">className</h3>
<span class='k'></span> <span class='nx'>string The fully qualified name of the class to be imported.</span><span class='no'> $className</span><span class='o'> = null</span>

<div class="details">
<p>A dependency class name. This is useful if the dependency class is instantiable
and direct instantiation is acceptable. To import interfaces, abstract
classes or classes with some kind of special instatiation issue
(like factory methods), use Import::$id instead and export the dependency
class with the @Export annotation.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Annotations/Import.php#L53" target='_blank'>framework\Hirudo\Core\Annotations\Import.php at line 53</a>

<h3 id="id">id</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $id</span><span class='o'> = null</span>

<div class="details">
<p>The id of the dependency to be injected.</p><p>If this attribute is null, the dependency injector shall determine the class
of the requested object and create a new instance to inject it. The way the class is
determined is like below:</p><p>If this annotation is applied to a method, the method's type hinting will be used
to determine the class of the dependency.</p><p>If this nanotation is applied to a property, the className property of this annotation
must be set to the fully qualified class name, this is a way to avoid the efford
of determining the class name based on the doc blocks.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Annotations/Import.php#L61" target='_blank'>framework\Hirudo\Core\Annotations\Import.php at line 61</a>

<h3 id="tag">tag</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $tag</span><span class='o'> = null</span>

<div class="details">
<p>A dependency tag. This is used to load dependencies through a tag instead
of an id, allowing to have a collection of dependencies related by tag.</p>
</div>

- - -

