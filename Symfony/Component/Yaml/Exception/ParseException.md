

- - -

**Symfony\Component\Yaml\Exception\ParseException**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Exception/ParseException.php#L21" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 21</a>

#Class ParseException#

\RuntimeException
* **ParseException**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Exception/ExceptionInterface.md">Symfony\Component\DependencyInjection\Exception\ExceptionInterface</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>ParseException</span>
<strong>extends</strong> \RuntimeException

</p>

<div class="comment" id="overview_description"><p>Exception class thrown when an error occurs during parsing.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string message, integer parsedLine, integer snippet, string parsedFile, Exception previous)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getsnippet">getSnippet</a>()</p><p class="description">Gets the snippet of code near the error.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setsnippet">setSnippet</a>(string snippet)</p><p class="description">Sets the snippet of code near the error.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getparsedfile">getParsedFile</a>()</p><p class="description">Gets the filename where the error occurred.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setparsedfile">setParsedFile</a>(string parsedFile)</p><p class="description">Sets the filename where the error occurred.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#getparsedline">getParsedLine</a>()</p><p class="description">Gets the line where the error occurred.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setparsedline">setParsedLine</a>(integer parsedLine)</p><p class="description">Sets the line where the error occurred.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Exception/ParseException.php#L37" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 37</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string message, integer parsedLine, integer snippet, string parsedFile, Exception previous)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>message - The error message</dd>
<dd>parsedLine - The line where the error occurred</dd>
<dd>snippet - The snippet of code near the problem</dd>
<dd>parsedFile - The file name where the error occurred</dd>
<dd>previous - The previous exception</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Exception/ParseException.php#L54" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 54</a>

<h3 id="getSnippet()">getSnippet</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getSnippet</span> ()

<div class="details">
<p>Gets the snippet of code near the error.</p><dl>
<dt>Returns:</dt>
<dd>The snippet of code</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Exception/ParseException.php#L64" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 64</a>

<h3 id="setSnippet()">setSnippet</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setSnippet</span> (string snippet)

<div class="details">
<p>Sets the snippet of code near the error.</p><dl>
<dt>Parameters:</dt>
<dd>snippet - The code snippet</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Exception/ParseException.php#L78" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 78</a>

<h3 id="getParsedFile()">getParsedFile</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getParsedFile</span> ()

<div class="details">
<p>Gets the filename where the error occurred.</p><p>This method returns null if a string is parsed.</p><dl>
<dt>Returns:</dt>
<dd>The filename</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Exception/ParseException.php#L88" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 88</a>

<h3 id="setParsedFile()">setParsedFile</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setParsedFile</span> (string parsedFile)

<div class="details">
<p>Sets the filename where the error occurred.</p><dl>
<dt>Parameters:</dt>
<dd>parsedFile - The filename</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Exception/ParseException.php#L100" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 100</a>

<h3 id="getParsedLine()">getParsedLine</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>getParsedLine</span> ()

<div class="details">
<p>Gets the line where the error occurred.</p><dl>
<dt>Returns:</dt>
<dd>The file line</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/Yaml/Exception/ParseException.php#L110" target='_blank'>framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 110</a>

<h3 id="setParsedLine()">setParsedLine</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setParsedLine</span> (integer parsedLine)

<div class="details">
<p>Sets the line where the error occurred.</p><dl>
<dt>Parameters:</dt>
<dd>parsedLine - The file line</dd>
</dl>

</div>

- - -

