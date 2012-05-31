- - -

**Smarty\_smarty_code**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 99</div>
#Class _smarty_code#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html">_smarty_parsetree</a>
    ***_smarty_code**


- - -

<p class="signature">public  class **_smarty_code**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html">_smarty_parsetree</a>

</p>

<div class="comment" id="overview_description"><p>Code fragment inside a tag.</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
<dt>Ignore.</dt>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html#data">data</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html#parser">parser</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(object parser, string data)</p><p class="description">Create parse tree buffer for code fragment</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#to_smarty_php">to_smarty_php</a>()</p><p class="description">Return buffer content in parentheses</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html#to_smarty_php()">to_smarty_php</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 108</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(object parser, string data)```
<div class="details">
<p>Create parse tree buffer for code fragment</p><dl>
<dt>Parameters:</dt>
<dd>parser - parser object</dd>
<dd>data - content</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 119</div>
<h3 id="to_smarty_php()">to_smarty_php</h3>
```php
public  string **to_smarty_php**()```
<div class="details">
<p>Return buffer content in parentheses</p><dl>
<dt>Returns:</dt>
<dd>content</dd>
</dl>
</div>

- - -

