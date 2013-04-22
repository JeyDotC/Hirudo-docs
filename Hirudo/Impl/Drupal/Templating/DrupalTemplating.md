

- - -

**Hirudo\Impl\Drupal\Templating\DrupalTemplating**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/Drupal/Templating/DrupalTemplating.php#L34" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\DrupalTemplating.php at line 34</a>

#Class DrupalTemplating#

**DrupalTemplating**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/TemplatingInterface.md">Hirudo\Core\TemplatingInterface</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>DrupalTemplating</span></p>

<div class="comment" id="overview_description"><p>A delegate based templating system.</p></div>

<dl>
<dt>Hirudo\Core\Annotations\Export(id="templating",:</dt>
<dd>factory="instance")</dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new instance of delegate templating.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#assign">assign</a>(string name, mixed value)</p><p class="description">Adds a variable to the view so it can be accessed from the delegate template.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#display">display</a>(string view)</p><p class="description">Renders the view and retuns it as a string.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>delegateTemplating</span></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addextensionspath">addExtensionsPath</a>(string path)</p><p class="description">Adds a path to delegate extensions so these can be used in the templates.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#pick">pick</a>(mixed views)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getfileextension">getFileExtension</a>()</p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/Drupal/Templating/DrupalTemplating.php#L45" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\DrupalTemplating.php at line 45</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a new instance of delegate templating.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/Drupal/Templating/DrupalTemplating.php#L56" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\DrupalTemplating.php at line 56</a>

<h3 id="assign()">assign</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>assign</span> (string name, mixed value)

<div class="details">
<p><p>Adds a variable to the view so it can be accessed from the delegate template.</p></p><dl>
<dt>Parameters:</dt>
<dd>name - The name that the variable will adopt.</dd>
<dd>value - The value of the variable.</dd>
<dt>Returns:</dt>
<dd>The assigned value</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/Drupal/Templating/DrupalTemplating.php#L68" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\DrupalTemplating.php at line 68</a>

<h3 id="display()">display</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>display</span> (string view)

<div class="details">
<p>Renders the view and retuns it as a string.</p><dl>
<dt>Parameters:</dt>
<dd>view - The name of the view to be rendered.</dd>
<dt>Returns:</dt>
<dd>The output of the view as a string.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/Drupal/Templating/DrupalTemplating.php#L82" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\DrupalTemplating.php at line 82</a>

<h3 id="instance()">instance</h3>
<span class='k'>static </span> <span class='nx'>delegateTemplating</span> <span class='nf'>instance</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/Drupal/Templating/DrupalTemplating.php#L95" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\DrupalTemplating.php at line 95</a>

<h3 id="addExtensionsPath()">addExtensionsPath</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addExtensionsPath</span> (string path)

<div class="details">
<p>Adds a path to delegate extensions so these can be used in the templates.</p><dl>
<dt>Parameters:</dt>
<dd>path - The absolute path to the delegate extensions.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/Drupal/Templating/DrupalTemplating.php#L99" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\DrupalTemplating.php at line 99</a>

<h3 id="pick()">pick</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>pick</span> (mixed views)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Impl/Drupal/Templating/DrupalTemplating.php#L109" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\DrupalTemplating.php at line 109</a>

<h3 id="getFileExtension()">getFileExtension</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getFileExtension</span> ()

<div class="details">

</div>

- - -

