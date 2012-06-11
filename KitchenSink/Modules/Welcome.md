

- - -

**KitchenSink\Modules\Welcome**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/Welcome/Welcome.php#L14" target='_blank'>src\KitchenSink\Modules\Welcome\Welcome.php at line 14</a>

#Class Welcome#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>
 &gt; **Welcome**




- - -

<p><strong>public  class</strong> <span>Welcome</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>

</p>

<div class="comment" id="overview_description"><p>A welcome Module, this module simply shows how to render a view
and how to add notifications which shall be represented by the template.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#context">context</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#currentuser">currentUser</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#headers">headers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#request">request</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#route">route</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#index">index</a>()</p><p class="description">Simply renders a view, is come kind of "Hello world".</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#notifications">notifications</a>()</p><p class="description">This method illustrates how to add notifications to the view.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#boompage">boomPage</a>()</p><p class="description">This is a task to test how Hirudo manages exceptions.
</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#addmessage">addMessage</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assignmany">assignMany</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#component">component</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getappname">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getmoduledir">getModuleDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getname">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getrendered">getRendered</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#gettask">getTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#onmoduleready">onModuleReady</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#renderget">renderGet</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#setappname">setAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#setdefaulttask">setDefaultTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/Welcome/Welcome.php#L19" target='_blank'>src\KitchenSink\Modules\Welcome\Welcome.php at line 19</a>

<h3 id="index()">index</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>index</span> ()

<div class="details">
<p>Simply renders a view, is come kind of "Hello world".</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/Welcome/Welcome.php#L35" target='_blank'>src\KitchenSink\Modules\Welcome\Welcome.php at line 35</a>

<h3 id="notifications()">notifications</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>notifications</span> ()

<div class="details">
<p>This method illustrates how to add notifications to the view.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/Welcome/Welcome.php#L67" target='_blank'>src\KitchenSink\Modules\Welcome\Welcome.php at line 67</a>

<h3 id="boomPage()">boomPage</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>boomPage</span> ()

<div class="details">
<p>This is a task to test how Hirudo manages exceptions.</p><p>The exceptions are managed by the module given in the ext/config/Config.yml
file in the onError value.</p><dl>
<dt>Throws:</dt>
<dd>\Exception</dd>
</dl>

</div>

- - -

