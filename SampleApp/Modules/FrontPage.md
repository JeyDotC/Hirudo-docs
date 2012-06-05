

- - -

**SampleApp\Modules\FrontPage**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/SampleApp/Modules/FrontPage/FrontPage.php#L13" target='_blank'>src\SampleApp\Modules\FrontPage\FrontPage.php at line 13</a>

#Class FrontPage#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>
 &gt; **FrontPage**




- - -

<p><strong>public  class</strong> <span>FrontPage</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>

</p>

<div class="comment" id="overview_description"><p>This is a sample module.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#context">context</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#currentUser">currentUser</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#headers">headers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#request">request</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#route">route</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#index">index</a>(string name)</p><p class="description">This is the index task, this one is called by default.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#response">response</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/SampleApp/Models/Entities/ComplexObject.md">ComplexObject</a> myComplexObject)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#seesomesessionvars">seeSomeSessionVars</a>()</p><p class="description">This is how you can get access to the session.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#boompage">boomPage</a>()</p><p class="description">This is a task to test how Hirudo manages exceptions.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#addMessage">addMessage</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assignMany">assignMany</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#component">component</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getAppName">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getModuleDir">getModuleDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getName">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getRendered">getRendered</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getTask">getTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#onModuleReady">onModuleReady</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#renderGet">renderGet</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#setAppName">setAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#setDefaultTask">setDefaultTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/SampleApp/Modules/FrontPage/FrontPage.php#L24" target='_blank'>src\SampleApp\Modules\FrontPage\FrontPage.php at line 24</a>

<h3 id="index()">index</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>index</span> (string name)

<div class="details">
<p>This is the index task, this one is called by default.</p><dl>
<dt>Parameters:</dt>
<dd>name - Variables without type hinting are resolved from GET, using the same name of the parameter, thus, the $name parameter in this function is taken from the 'name' value from get. If there is no such value, the default value is put in it's place, if the parameter has no default value the parameter will have value <code>null</code></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/SampleApp/Modules/FrontPage/FrontPage.php#L60" target='_blank'>src\SampleApp\Modules\FrontPage\FrontPage.php at line 60</a>

<h3 id="response()">response</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>response</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/SampleApp/Models/Entities/ComplexObject.md">ComplexObject</a> myComplexObject)

<div class="details">
<p></p><dl>
<dt>Parameters:</dt>
<dd>myComplexObject - <p>Parameters with type hinting are taken from post. The object parameters are built with the post data, to do so just name the fields with the array notation: paramName[attributeName] or use the smarty function {bind to="paramName.attributeName"} See the index.tpl file to look examples of both cases.</p> <p><strong>Important:</strong> In order to have the inner objects correctly mapped is necesary to type the private attributes with the phpDoc notation:</p> <code> /** @var Fully\Qualified\ClassName / private $myInnerObject </code></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/SampleApp/Modules/FrontPage/FrontPage.php#L79" target='_blank'>src\SampleApp\Modules\FrontPage\FrontPage.php at line 79</a>

<h3 id="seeSomeSessionVars()">seeSomeSessionVars</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>seeSomeSessionVars</span> ()

<div class="details">
<p>This is how you can get access to the session.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/SampleApp/Modules/FrontPage/FrontPage.php#L105" target='_blank'>src\SampleApp\Modules\FrontPage\FrontPage.php at line 105</a>

<h3 id="boomPage()">boomPage</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>boomPage</span> ()

<div class="details">
<p>This is a task to test how Hirudo manages exceptions.</p><dl>
<dt>Throws:</dt>
<dd>\Exception</dd>
</dl>

</div>

- - -

