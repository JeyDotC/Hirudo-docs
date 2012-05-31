
- - -

**Hirudo\Lang\DirectoryHelper**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Lang\Loader.php at line 193#L193 class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 193</a>

#Class DirectoryHelper#

**DirectoryHelper**




- - -

<p class="signature">public  class **DirectoryHelper**</p>

<div class="comment" id="overview_description"><p>A class for directory listing.</p></div>



- - -

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
<td class="description"><p class="name"><a href="#listfiles">listFiles</a>(int depth)</p><p class="description">Lists all files, ignoring the directories, for the actual DirectoryIterator
at the specified depth.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Lang\Loader.php at line 202#L202 class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 202</a>

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

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Lang\Loader.php at line 221#L221 class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 221</a>

<h3 id="listFiles()">listFiles</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>listFiles</span> (int depth)

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

