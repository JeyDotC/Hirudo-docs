- - -

**Smarty\_smarty_tag**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php.md#line47" class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 47</a>

# Class _smarty_tag #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html">_smarty_parsetree</a>\n    *** _smarty_tag **\n</pre>

- - -

<p class="signature">public  class **_smarty_tag**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html">_smarty_parsetree</a>

</p>

<div class="comment" id="overview_description"><p>A complete smarty tag.</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
<dt>Ignore.</dt>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> int</td>
<td class="description"><p class="name"><a href="#saved_block_nesting">$saved_block_nesting</a></p><p class="description">Saved block nesting level</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html#data">data</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html#parser">parser</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(object parser, string data)</p><p class="description">Create parse tree buffer for Smarty tag</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#to_smarty_php()">to_smarty_php</a>()</p><p class="description">Return buffer content</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#assign_to_var()">assign_to_var</a>()</p><p class="description">Return complied code that loads the evaluated outout of buffer content into a temporary variable</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html#to_smarty_php()">to_smarty_php</a></td></tr></table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php.md#line53" class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 53</a>

<h3 id="saved_block_nesting">saved_block_nesting</h3>
```php
public  int **$saved_block_nesting**```
<div class="details">
<p>Saved block nesting level</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php.md#line61" class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 61</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(object parser, string data)```
<div class="details">
<p>Create parse tree buffer for Smarty tag</p><dl>
<dt>Parameters:</dt>
<dd>parser - parser object</dd>
<dd>data - content</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php.md#line73" class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 73</a>

<h3 id="to_smarty_php()">to_smarty_php</h3>
```php
public  string **to_smarty_php**()```
<div class="details">
<p>Return buffer content</p><dl>
<dt>Returns:</dt>
<dd>content</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php.md#line83" class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 83</a>

<h3 id="assign_to_var()">assign_to_var</h3>
```php
public  string **assign_to_var**()```
<div class="details">
<p>Return complied code that loads the evaluated outout of buffer content into a temporary variable</p><dl>
<dt>Returns:</dt>
<dd>template code</dd>
</dl>
</div>

- - -

