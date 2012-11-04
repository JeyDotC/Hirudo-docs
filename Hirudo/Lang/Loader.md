

- - -

**Hirudo\Lang\Loader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Loader.php#L46" target='_blank'>framework\hirudo\Hirudo\Lang\Loader.php at line 46</a>

#Class Loader#

**Loader**




- - -

<p><strong>public final  class</strong> <span>Loader</span></p>

<div class="comment" id="overview_description"><p><p>A PHP file loader. It's like an enhanced require_once. The improvements
consist on:</p></p>
<ul>
<li>Having a sigle style for path strings using the '::' notation for directrory separators</li>
<li>The use of the '*' notation to load all files in a path.</li>
</ul>
<p></p></div>

<dl>
<dt>See Also:</dt>
<dd>Loader::using()</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#arraytopaths">arrayToPaths</a>(array array, string extension)</p><p class="description">Traduces a list of strings with the Loader::using() format to the
resulting paths.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#topaths">toPaths</a>(array array, string extension, mixed string)</p><p class="description">Traduces string with the Loader::using() format to the
resulting paths.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#tosinglepath">toSinglePath</a>(mixed string, mixed extension)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#isdir">isDir</a>(mixed dir)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#isfile">isFile</a>(mixed file, mixed extension)</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Loader.php#L78" target='_blank'>framework\hirudo\Hirudo\Lang\Loader.php at line 78</a>

<h3 id="arrayToPaths()">arrayToPaths</h3>
<span class='k'>static </span> <span class='nx'>array</span> <span class='nf'>arrayToPaths</span> (array array, string extension)

<div class="details">
<p>Traduces a list of strings with the <code>Loader::using()</code> format to the
resulting paths.</p><dl>
<dt>Parameters:</dt>
<dd>array - An array of strings representing the paths.</dd>
<dd>extension - An extension to be applied to the paths.</dd>
<dt>Returns:</dt>
<dd>An array of absolute paths.</dd>
<dt>See Also:</dt>
<dd>For more details.</dd>
<dd>For more details.</dd>
<dt>Throws:</dt>
<dd><a href="../../hirudo/lang/invalidpathexception.html">InvalidPathException</a> - If $string is not a string, is null or is empty.</dd>
<dd>LogicException - If $extension is not a string.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Loader.php#L101" target='_blank'>framework\hirudo\Hirudo\Lang\Loader.php at line 101</a>

<h3 id="toPaths()">toPaths</h3>
<span class='k'>static </span> <span class='nx'>array</span> <span class='nf'>toPaths</span> (array array, string extension, mixed string)

<div class="details">
<p>Traduces string with the <code>Loader::using()</code> format to the
resulting paths.</p><dl>
<dt>Parameters:</dt>
<dd>array - A string representing the paths.</dd>
<dd>extension - An extension to be applied to the paths.</dd>
<dt>Returns:</dt>
<dd>An array of absolute paths.</dd>
<dt>See Also:</dt>
<dd>For more details.</dd>
<dt>Throws:</dt>
<dd><a href="../../hirudo/lang/invalidpathexception.html">InvalidPathException</a> - If $string is not a string, is null or is empty.</dd>
<dd>LogicException - If $extension is not a string.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Loader.php#L149" target='_blank'>framework\hirudo\Hirudo\Lang\Loader.php at line 149</a>

<h3 id="toSinglePath()">toSinglePath</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>toSinglePath</span> (mixed string, mixed extension)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Loader.php#L175" target='_blank'>framework\hirudo\Hirudo\Lang\Loader.php at line 175</a>

<h3 id="isDir()">isDir</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>isDir</span> (mixed dir)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Lang/Loader.php#L180" target='_blank'>framework\hirudo\Hirudo\Lang\Loader.php at line 180</a>

<h3 id="isFile()">isFile</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>isFile</span> (mixed file, mixed extension)

<div class="details">

</div>

- - -

