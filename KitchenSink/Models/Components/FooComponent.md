

- - -

**KitchenSink\Models\Components\FooComponent**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Models/Components/FooComponent.php#L19" target='_blank'>src\KitchenSink\Models\Components\FooComponent.php at line 19</a>

#Class FooComponent#

**FooComponent**




- - -

<p><strong>public  class</strong> <span>FooComponent</span></p>

<div class="comment" id="overview_description"><p>A component that stores entities in session, normally you should use
a component that stores entities to a database.</p><p>Hirudo doesn't provide a way of persistence by itself, instead, you can use
one or more of the extensions provided by HirudOPlus. One of those is the
doctrine binding to Hirudo. Another will be the Restful client.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<Foo></span></td>
<td class="description"><p class="name"><a href="#getall">getAll</a>()</p><p class="description">Gets all stored foos.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Models/Entities/Foo.md>Foo</a></span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string id)</p><p class="description">Gets a Foo object by id.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#save">save</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Models/Entities/Foo.md">Foo</a> foo)</p><p class="description">Stores a Foo into session.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#remove">remove</a>(string id)</p><p class="description">Removes a Foo by id.</p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Models/Components/FooComponent.php#L26" target='_blank'>src\KitchenSink\Models\Components\FooComponent.php at line 26</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Models/Components/FooComponent.php#L40" target='_blank'>src\KitchenSink\Models\Components\FooComponent.php at line 40</a>

<h3 id="getAll()">getAll</h3>
<span class='k'></span> <span class='nx'>array<Foo></span> <span class='nf'>getAll</span> ()

<div class="details">
<p>Gets all stored foos.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Models/Components/FooComponent.php#L50" target='_blank'>src\KitchenSink\Models\Components\FooComponent.php at line 50</a>

<h3 id="get()">get</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Models/Entities/Foo.md>Foo</a></span> <span class='nf'>get</span> (string id)

<div class="details">
<p>Gets a Foo object by id.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Models/Components/FooComponent.php#L60" target='_blank'>src\KitchenSink\Models\Components\FooComponent.php at line 60</a>

<h3 id="save()">save</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>save</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Models/Entities/Foo.md">Foo</a> foo)

<div class="details">
<p>Stores a Foo into session.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Models/Components/FooComponent.php#L79" target='_blank'>src\KitchenSink\Models\Components\FooComponent.php at line 79</a>

<h3 id="remove()">remove</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>remove</span> (string id)

<div class="details">
<p>Removes a Foo by id.</p>
</div>

- - -

