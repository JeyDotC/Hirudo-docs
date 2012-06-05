

- - -

**Hirudo\Core\Annotations\Export**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Annotations/Export.php#L34" target='_blank'>framework\hirudo\Hirudo\Core\Annotations\Export.php at line 34</a>

#Class Export#

**Export**




- - -

<p><strong>public final  class</strong> <span>Export</span></p>

<div class="comment" id="overview_description"><p>Signals a class, method or property as a service exporter.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Annotation.</dt>
<dt>Target({"CLASS",:</dt>
<dd>"METHOD", "PROPERTY"})</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="factory"> $factory</a>
                                </p><p class="description">An optional factory method which is in charge of returning
an instance of the service.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="id"> $id</a>
                                </p><p class="description">The id of the service to be exported.</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Annotations/Export.php#L49" target='_blank'>framework\hirudo\Hirudo\Core\Annotations\Export.php at line 49</a>

<h3 id="factory">factory</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $factory</span><span class='o'> = &quot;&quot;</span>

<div class="details">
<p>An optional factory method which is in charge of returning
an instance of the service.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Annotations/Export.php#L41" target='_blank'>framework\hirudo\Hirudo\Core\Annotations\Export.php at line 41</a>

<h3 id="id">id</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $id</span><span class='o'> = &quot;&quot;</span>

<div class="details">
<p>The id of the service to be exported.</p>
</div>

- - -

