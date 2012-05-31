
- - -

**Smarty\_smarty_doublequoted**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 133</div>
#Class _smarty_doublequoted#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html">_smarty_parsetree</a>
    ***_smarty_doublequoted**


- - -

<p class="signature">public  class **_smarty_doublequoted**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html">_smarty_parsetree</a>

</p>

<div class="comment" id="overview_description"><p>Double quoted string inside a tag.</p></div>

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
<td class="description"><p class="name"><a href="#__construct">__construct</a>(object parser, <a href="../smarty/_smarty_parsetree.html">_smarty_parsetree</a> subtree)</p><p class="description">Create parse tree buffer for double quoted string subtrees</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#append_subtree">append_subtree</a>(<a href="../smarty/_smarty_parsetree.html">_smarty_parsetree</a> subtree)</p><p class="description">Append buffer to subtree</p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#to_smarty_php">to_smarty_php</a>()</p><p class="description">Merge subtree buffer content together</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.html#to_smarty_php()">to_smarty_php</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 141</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(object parser, <a href="../smarty/_smarty_parsetree.html">_smarty_parsetree</a> subtree)
```
<div class="details">
<p>Create parse tree buffer for double quoted string subtrees</p><dl>
<dt>Parameters:</dt>
<dd>parser - parser object</dd>
<dd>subtree - parsetree buffer</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 155</div>
<h3 id="append_subtree()">append_subtree</h3>

public  void **append_subtree** (<a href="../smarty/_smarty_parsetree.html">_smarty_parsetree</a> subtree)<div class="details">
<p>Append buffer to subtree</p><dl>
<dt>Parameters:</dt>
<dd>subtree - parsetree buffer</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 179</div>
<h3 id="to_smarty_php()">to_smarty_php</h3>

public  string **to_smarty_php** ()<div class="details">
<p>Merge subtree buffer content together</p><dl>
<dt>Returns:</dt>
<dd>compiled template code</dd>
</dl>
</div>

- - -

