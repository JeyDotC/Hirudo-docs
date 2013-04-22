

- - -

**KitchenSink\Modules\ApiModule\ApiModule**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/src/KitchenSink/Modules/ApiModule/ApiModule.php#L17" target='_blank'>src\KitchenSink\Modules\ApiModule\ApiModule.php at line 17</a>

#Class ApiModule#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>
 &gt; **ApiModule**




- - -

<p><strong>public  class</strong> <span>ApiModule</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>

</p>

<div class="comment" id="overview_description"><p>This module illustrates an api
that mimics the CrudModule behavior but having
a REST-like interface.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#context">context</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#currentuser">currentUser</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#headers">headers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#page">page</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#request">request</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#route">route</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#session">session</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<Foo></span></td>
<td class="description"><p class="name"><a href="#index">index</a>()</p><p class="description">This method returns the list of Foo objects stored in session.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Models/Entities/Foo.md>Foo</a></span></td>
<td class="description"><p class="name"><a href="#view">view</a>(mixed id)</p><p class="description">Returns the Foo object with the given id.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#create">create</a>(\KitchenSink\Models\Entities\Foo foo)</p><p class="description">Saves a new Foo in session.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#update">update</a>(\KitchenSink\Models\Entities\Foo foo)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#remove">remove</a>(int id)</p><p class="description"></p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#addmessage">addMessage</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assignmany">assignMany</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#component">component</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#createmodulefromclassname">createModuleFromClassName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getappname">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getmoduledir">getModuleDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getname">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#gettask">getTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#onmoduleready">onModuleReady</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#redirect">redirect</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#setdefaulttask">setDefaultTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/src/KitchenSink/Modules/ApiModule/ApiModule.php#L42" target='_blank'>src\KitchenSink\Modules\ApiModule\ApiModule.php at line 42</a>

<h3 id="index()">index</h3>
<span class='k'></span> <span class='nx'>array<Foo></span> <span class='nf'>index</span> ()

<div class="details">
<p>This method returns the list of Foo objects stored in session.</p><p>In order to make this method REST-like we need to mark it as
such with the Api annotation. The HttpMethod allows to say what HTTP verbs
are accepted by it.</p><p>Note that we are not specifying the format we are going to return the
data. The format for serialization is determined from the Accept: header
parameter, so if you send an HttpRequest with 'Accept: aplication/json' the
data returned for this method will be serialized to JSON.</p><p>We aren't even serializing the returned data, that process is done
automatically by the framework, which after choosing a format for serialization
atempts to serialize the values returned by this method.</p><dl>
<dt>See Also:</dt>
<dd><a href="../../../hirudo/core/annotations/httpmethod.html">HttpMethod</a></dd>
<dt>Api.</dt>
<dt>HttpMethod("GET").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/src/KitchenSink/Modules/ApiModule/ApiModule.php#L59" target='_blank'>src\KitchenSink\Modules\ApiModule\ApiModule.php at line 59</a>

<h3 id="view()">view</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/KitchenSink/Models/Entities/Foo.md>Foo</a></span> <span class='nf'>view</span> (mixed id)

<div class="details">
<p>Returns the Foo object with the given id.</p><p>This is much like the previous one, but we are receiving a value which is
resolved from GET</p><dl>
<dt>See Also:</dt>
<dd><a href="../../../hirudo/core/annotations/httpmethod.html">HttpMethod</a></dd>
<dt>Api.</dt>
<dt>HttpMethod("GET").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/src/KitchenSink/Modules/ApiModule/ApiModule.php#L88" target='_blank'>src\KitchenSink\Modules\ApiModule\ApiModule.php at line 88</a>

<h3 id="create()">create</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>create</span> (\KitchenSink\Models\Entities\Foo foo)

<div class="details">
<p>Saves a new Foo in session.</p><p>This method is different from the other two above. First of all, it just
accepts POST requests, and secondly, it has a type hinted parameter which
is resolved directly from the request payload which will be in some format,
like JSON or XML.</p><p>The way the request payload's format is determined is similar to the way
the response's format is gessed, in this case, Hirudo uses the Content-Type:
header variable. So, if we send a request with Content-Type: application/json
Hirudo will expect the request payload to be JSON and will attepmt to deserialize
it with that asumption.</p><p>Here is something important to keep in mind, for now, hirudo accepts one only
type-hinted parameter for API methods, not like the normal ones that accepts
any number of those.</p><dl>
<dt>See Also:</dt>
<dd><a href="../../../hirudo/core/annotations/httpmethod.html">HttpMethod</a></dd>
<dt>Api.</dt>
<dt>HttpMethod("POST").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/src/KitchenSink/Modules/ApiModule/ApiModule.php#L99" target='_blank'>src\KitchenSink\Modules\ApiModule\ApiModule.php at line 99</a>

<h3 id="update()">update</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>update</span> (\KitchenSink\Models\Entities\Foo foo)

<div class="details">
<p></p><dl>
<dt>Api.</dt>
<dt>HttpMethod("PUT").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/src/KitchenSink/Modules/ApiModule/ApiModule.php#L110" target='_blank'>src\KitchenSink\Modules\ApiModule\ApiModule.php at line 110</a>

<h3 id="remove()">remove</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>remove</span> (int id)

<div class="details">
<p></p><dl>
<dt>Api.</dt>
<dt>HttpMethod("DELETE").</dt>
</dl>

</div>

- - -

