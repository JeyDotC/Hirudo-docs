

- - -

**Hirudo\Lang\DirectoryHelper**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Lang/Loader.php#L253" target='_blank'>framework\Hirudo\Lang\Loader.php at line 253</a>

#Class DirectoryHelper#

**DirectoryHelper**




- - -

<p><strong>public  class</strong> <span>DirectoryHelper</span></p>

<div class="comment" id="overview_description"><p>A class for directory listing.</p></div>



<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(RecursiveDirectoryIterator dir)</p><p class="description">Creates a directory helper.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#listfiles">listFiles</a>(int depth, str filterByExtension, bool trimExtension, bool base)</p><p class="description">Lists all files, ignoring the directories, for the actual DirectoryIterator
at the specified depth.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#listdirectories">listDirectories</a>(int depth)</p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Lang/Loader.php#L262" target='_blank'>framework\Hirudo\Lang\Loader.php at line 262</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (RecursiveDirectoryIterator dir)

<div class="details">
<p>Creates a directory helper.</p><dl>
<dt>Parameters:</dt>
<dd>dir - The root folder from which this directory helper will work.</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Lang/Loader.php#L281" target='_blank'>framework\Hirudo\Lang\Loader.php at line 281</a>

<h3 id="listFiles()">listFiles</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>listFiles</span> (int depth, str filterByExtension, bool trimExtension, bool base)

<div class="details">
<p>Lists all files, ignoring the directories, for the actual DirectoryIterator
at the specified depth.</p><dl>
<dt>Parameters:</dt>
<dd>depth - The depth for which this iterator will find the files.</dd>
<dt>Returns:</dt>
<dd>The list of absolute paths to the found files.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Lang/Loader.php#L289" target='_blank'>framework\Hirudo\Lang\Loader.php at line 289</a>

<h3 id="listDirectories()">listDirectories</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>listDirectories</span> (int depth)

<div class="details">

</div>

- - -

