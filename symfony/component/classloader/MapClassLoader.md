

- - -

**Symfony\Component\ClassLoader\MapClassLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/MapClassLoader.php#L19" >framework\libs\symfony-components\Symfony\Component\ClassLoader\MapClassLoader.php at line 19</a>

#Class MapClassLoader#

**MapClassLoader**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>MapClassLoader</span></p>

<div class="comment" id="overview_description"><p>A class loader that uses a mapping file to look up paths.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array map)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register">register</a>(Boolean prepend)</p><p class="description">Registers this instance as an autoloader.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadclass">loadClass</a>(string class)</p><p class="description">Loads the given class or interface.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string|null</span></td>
<td class="description"><p class="name"><a href="#findfile">findFile</a>(string class)</p><p class="description">Finds the path to the file where the class is defined.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/MapClassLoader.php#L28" >framework\libs\symfony-components\Symfony\Component\ClassLoader\MapClassLoader.php at line 28</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (array map)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>map - A map where keys are classes and values the absolute file path</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/MapClassLoader.php#L38" >framework\libs\symfony-components\Symfony\Component\ClassLoader\MapClassLoader.php at line 38</a>

<h3 id="register()">register</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register</span> (Boolean prepend)

<div class="details">
<p>Registers this instance as an autoloader.</p><dl>
<dt>Parameters:</dt>
<dd>prepend - Whether to prepend the autoloader or not</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/MapClassLoader.php#L48" >framework\libs\symfony-components\Symfony\Component\ClassLoader\MapClassLoader.php at line 48</a>

<h3 id="loadClass()">loadClass</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>loadClass</span> (string class)

<div class="details">
<p>Loads the given class or interface.</p><dl>
<dt>Parameters:</dt>
<dd>class - The name of the class</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/MapClassLoader.php#L66" >framework\libs\symfony-components\Symfony\Component\ClassLoader\MapClassLoader.php at line 66</a>

<h3 id="findFile()">findFile</h3>
<span class='k'></span> <span class='nx'>string|null</span> <span class='nf'>findFile</span> (string class)

<div class="details">
<p>Finds the path to the file where the class is defined.</p><dl>
<dt>Parameters:</dt>
<dd>class - The name of the class</dd>
<dt>Returns:</dt>
<dd>The path, if found</dd>
</dl>

</div>

- - -

