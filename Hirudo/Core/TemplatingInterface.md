

- - -

**Hirudo\Core\TemplatingInterface**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/TemplatingInterface.php#L32" target='_blank'>framework\Hirudo\Core\TemplatingInterface.php at line 32</a>

#Interface TemplatingInterface#

**TemplatingInterface**




- - -

<p><strong>public  interface</strong> <span>TemplatingInterface</span></p>

<div class="comment" id="overview_description"><p><p>An interface for any templating system such as Smarty, Twig, PATemplate, etc.</p></p><p><p>Implementors must be capable of loading and rendering the template resource
based on the view name.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#assign">assign</a>(string name, mixed value)</p><p class="description">Adds a variable to the view so it can be accessed from the template.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#display">display</a>(string moduleDir, string view)</p><p class="description">Renders the view and retuns it as a string.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#pick">pick</a>(array views)</p><p class="description">Renders the first found view.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getfileextension">getFileExtension</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addextensionspath">addExtensionsPath</a>(string path)</p><p class="description">Tells to the Templating system the location of an extensions folder, allowing
it to load and use its extensions.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/TemplatingInterface.php#L41" target='_blank'>framework\Hirudo\Core\TemplatingInterface.php at line 41</a>

<h3 id="assign()">assign</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>assign</span> (string name, mixed value)

<div class="details">
<p><p>Adds a variable to the view so it can be accessed from the template.</p></p><dl>
<dt>Parameters:</dt>
<dd>name - The name that the variable will adopt.</dd>
<dd>value - The value of the variable.</dd>
<dt>Returns:</dt>
<dd>The assigned value</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/TemplatingInterface.php#L51" target='_blank'>framework\Hirudo\Core\TemplatingInterface.php at line 51</a>

<h3 id="display()">display</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>display</span> (string moduleDir, string view)

<div class="details">
<p>Renders the view and retuns it as a string.</p><dl>
<dt>Parameters:</dt>
<dd>moduleDir - The absolute path to the module.</dd>
<dd>view - The name of the view to be rendered.</dd>
<dt>Returns:</dt>
<dd>The output of the view as a string.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/TemplatingInterface.php#L60" target='_blank'>framework\Hirudo\Core\TemplatingInterface.php at line 60</a>

<h3 id="pick()">pick</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>pick</span> (array views)

<div class="details">
<p>Renders the first found view.</p><dl>
<dt>Parameters:</dt>
<dd>views - A list of view file names.</dd>
<dt>Returns:</dt>
<dd>The output of the view as a string.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/TemplatingInterface.php#L65" target='_blank'>framework\Hirudo\Core\TemplatingInterface.php at line 65</a>

<h3 id="getFileExtension()">getFileExtension</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getFileExtension</span> ()

<div class="details">
<p></p><dl>
<dt>Returns:</dt>
<dd>The file extension supported by this template engine.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/TemplatingInterface.php#L74" target='_blank'>framework\Hirudo\Core\TemplatingInterface.php at line 74</a>

<h3 id="addExtensionsPath()">addExtensionsPath</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addExtensionsPath</span> (string path)

<div class="details">
<p>Tells to the Templating system the location of an extensions folder, allowing
it to load and use its extensions.</p>
</div>

- - -

