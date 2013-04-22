

- - -

**KitchenSink\Modules\CrudModule\CrudModule**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/CrudModule/CrudModule.php#L14" target='_blank'>src\KitchenSink\Modules\CrudModule\CrudModule.php at line 14</a>

#Class CrudModule#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>
 &gt; **CrudModule**




- - -

<p><strong>public  class</strong> <span>CrudModule</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>

</p>

<div class="comment" id="overview_description"><p>This module represents a tipical Create, Read, Update, Delete use case with the
Foo entity as the main subject.</p></div>



<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#context">context</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#currentuser">currentUser</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#headers">headers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#page">page</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#request">request</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#route">route</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#session">session</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#index">index</a>()</p><p class="description">Lists all entities.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#view">view</a>(string id)</p><p class="description">This method shows a details view for a foo with the given id.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#create">create</a>()</p><p class="description">Displays view to create a new Foo.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#edit">edit</a>(type id)</p><p class="description">Displays the foo editing page.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#remove">remove</a>(type id)</p><p class="description">Removes a Foo</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#save">save</a>(ViewModels\FooViewModel foo)</p><p class="description">Saves a new foo.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#update">update</a>(ViewModels\FooViewModel foo)</p><p class="description"></p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#addmessage">addMessage</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assignmany">assignMany</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#component">component</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#createmodulefromclassname">createModuleFromClassName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getappname">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getmoduledir">getModuleDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getname">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#gettask">getTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#onmoduleready">onModuleReady</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#redirect">redirect</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#setdefaulttask">setDefaultTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/CrudModule/CrudModule.php#L19" target='_blank'>src\KitchenSink\Modules\CrudModule\CrudModule.php at line 19</a>

<h3 id="index()">index</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>index</span> ()

<div class="details">
<p>Lists all entities.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/CrudModule/CrudModule.php#L56" target='_blank'>src\KitchenSink\Modules\CrudModule\CrudModule.php at line 56</a>

<h3 id="view()">view</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>view</span> (string id)

<div class="details">
<p>This method shows a details view for a foo with the given id.</p><p>Wait a second, where is that '$id' parameter coming from? well, Hirudo
resolves the parameters which has no type hinting from GET, thus, if there
is a value in the GET parameters which name matches 'id', then the $id param
is set to that value, other wise, the default value is used, and if there is no
default value, null is used.</p><p>Anyway, you can also programatically get the values from the GET this way:</p><p>$myGetValue = $this->request->get("id");</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/CrudModule/CrudModule.php#L68" target='_blank'>src\KitchenSink\Modules\CrudModule\CrudModule.php at line 68</a>

<h3 id="create()">create</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>create</span> ()

<div class="details">
<p>Displays view to create a new Foo.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/CrudModule/CrudModule.php#L95" target='_blank'>src\KitchenSink\Modules\CrudModule\CrudModule.php at line 95</a>

<h3 id="edit()">edit</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>edit</span> (type id)

<div class="details">
<p>Displays the foo editing page.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/CrudModule/CrudModule.php#L109" target='_blank'>src\KitchenSink\Modules\CrudModule\CrudModule.php at line 109</a>

<h3 id="remove()">remove</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>remove</span> (type id)

<div class="details">
<p>Removes a Foo</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/CrudModule/CrudModule.php#L136" target='_blank'>src\KitchenSink\Modules\CrudModule\CrudModule.php at line 136</a>

<h3 id="save()">save</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>save</span> (ViewModels\FooViewModel foo)

<div class="details">
<p>Saves a new foo.</p><p>Note the presence of a type hinted $foo param. For these cases, the parameter
is resolved from post by obtaining an array which name coincides with the
param name. The properties are set using the keys of such array.</p><p>Also note the presence of the HttpPost annotation. That annotation indicates
that this method only accepts POST requests. Any atempt to access this method
via GET, will cause an exception.</p><dl>
<dt>HttpPost.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/CrudModule/CrudModule.php#L149" target='_blank'>src\KitchenSink\Modules\CrudModule\CrudModule.php at line 149</a>

<h3 id="update()">update</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>update</span> (ViewModels\FooViewModel foo)

<div class="details">
<p></p><dl>
<dt>HttpPost.</dt>
</dl>

</div>

- - -

