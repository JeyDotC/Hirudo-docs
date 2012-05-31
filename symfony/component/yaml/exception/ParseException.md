- - -

**Symfony\Component\Yaml\Exception\ParseException**
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 21</div>
#Class ParseException#

\RuntimeException
***ParseException**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/exception/exceptioninterface.html">Symfony\Component\DependencyInjection\Exception\ExceptionInterface</a> </dd>
</dl>

- - -

<p class="signature">public  class **ParseException**
extends \RuntimeException

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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string message, integer parsedLine, integer snippet, string parsedFile, Exception previous)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getSnippet">getSnippet</a>()</p><p class="description">Gets the snippet of code near the error.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setSnippet">setSnippet</a>(string snippet)</p><p class="description">Sets the snippet of code near the error.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getParsedFile">getParsedFile</a>()</p><p class="description">Gets the filename where the error occurred.
</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setParsedFile">setParsedFile</a>(string parsedFile)</p><p class="description">Sets the filename where the error occurred.</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#getParsedLine">getParsedLine</a>()</p><p class="description">Gets the line where the error occurred.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setParsedLine">setParsedLine</a>(integer parsedLine)</p><p class="description">Sets the line where the error occurred.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 37</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(string message, integer parsedLine, integer snippet, string parsedFile, Exception previous)```
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
<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 54</div>
<h3 id="getSnippet()">getSnippet</h3>
```php
public  string **getSnippet**()```
<div class="details">
<p>Gets the snippet of code near the error.</p><dl>
<dt>Returns:</dt>
<dd>The snippet of code</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 64</div>
<h3 id="setSnippet()">setSnippet</h3>
```php
public  void **setSnippet**(string snippet)```
<div class="details">
<p>Sets the snippet of code near the error.</p><dl>
<dt>Parameters:</dt>
<dd>snippet - The code snippet</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 78</div>
<h3 id="getParsedFile()">getParsedFile</h3>
```php
public  string **getParsedFile**()```
<div class="details">
<p>Gets the filename where the error occurred.</p><p>This method returns null if a string is parsed.</p><dl>
<dt>Returns:</dt>
<dd>The filename</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 88</div>
<h3 id="setParsedFile()">setParsedFile</h3>
```php
public  void **setParsedFile**(string parsedFile)```
<div class="details">
<p>Sets the filename where the error occurred.</p><dl>
<dt>Parameters:</dt>
<dd>parsedFile - The filename</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 100</div>
<h3 id="getParsedLine()">getParsedLine</h3>
```php
public  integer **getParsedLine**()```
<div class="details">
<p>Gets the line where the error occurred.</p><dl>
<dt>Returns:</dt>
<dd>The file line</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\Yaml\Exception\ParseException.php at line 110</div>
<h3 id="setParsedLine()">setParsedLine</h3>
```php
public  void **setParsedLine**(integer parsedLine)```
<div class="details">
<p>Sets the line where the error occurred.</p><dl>
<dt>Parameters:</dt>
<dd>parsedLine - The file line</dd>
</dl>
</div>

- - -

