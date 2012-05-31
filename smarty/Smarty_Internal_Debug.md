- - -

**Smarty\Smarty_Internal_Debug**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 18</div>
#Class Smarty_Internal_Debug#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>
    ***Smarty_Internal_Debug**


- - -

<p class="signature">public  class **Smarty_Internal_Debug**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Debug Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Debug</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#template_data">$template_data</a></p><p class="description">template data</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#config_vars">config_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#parent">parent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#template_class">template_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#tpl_vars">tpl_vars</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#start_compile">start_compile</a>(object template)</p><p class="description">Start logging of compile time</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#end_compile">end_compile</a>(object template)</p><p class="description">End logging of compile time</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#start_render">start_render</a>(object template)</p><p class="description">Start logging of render time</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#end_render">end_render</a>(object template)</p><p class="description">End logging of compile time</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#start_cache">start_cache</a>(object template)</p><p class="description">Start logging of cache time</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#end_cache">end_cache</a>(object template)</p><p class="description">End logging of cache time</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#display_debug">display_debug</a>(Smarty_Internal_Template|Smarty obj)</p><p class="description">Opens a window for the Smarty Debugging Consol and display the data</p></td>
</tr>
<tr>
<td class="type">static  StdClass</td>
<td class="description"><p class="name"><a href="#get_debug_vars">get_debug_vars</a>(Smarty_Internal_Template|Smarty_Data obj)</p><p class="description">Recursively gets variables from all template/data scopes</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#append()">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#appendByRef()">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assign()">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignByRef()">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignGlobal()">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAllAssign()">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAssign()">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearConfig()">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#configLoad()">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVariable()">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVars()">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getStreamVariable()">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getTemplateVars()">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getVariable()">getVariable</a></td></tr></table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 25</div>
<h3 id="template_data">template_data</h3>

```php
public static  array$template_data = array()
```
<div class="details">
<p>template data</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 32</div>
<h3 id="start_compile()">start_compile</h3>

```php
public static  void **start_compile**(object template)
```
<div class="details">
<p>Start logging of compile time</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 43</div>
<h3 id="end_compile()">end_compile</h3>

```php
public static  void **end_compile**(object template)
```
<div class="details">
<p>End logging of compile time</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 54</div>
<h3 id="start_render()">start_render</h3>

```php
public static  void **start_render**(object template)
```
<div class="details">
<p>Start logging of render time</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 65</div>
<h3 id="end_render()">end_render</h3>

```php
public static  void **end_render**(object template)
```
<div class="details">
<p>End logging of compile time</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 76</div>
<h3 id="start_cache()">start_cache</h3>

```php
public static  void **start_cache**(object template)
```
<div class="details">
<p>Start logging of cache time</p><dl>
<dt>Parameters:</dt>
<dd>template - cached template</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 87</div>
<h3 id="end_cache()">end_cache</h3>

```php
public static  void **end_cache**(object template)
```
<div class="details">
<p>End logging of cache time</p><dl>
<dt>Parameters:</dt>
<dd>template - cached template</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 98</div>
<h3 id="display_debug()">display_debug</h3>

```php
public static  void **display_debug**(Smarty_Internal_Template|Smarty obj)
```
<div class="details">
<p>Opens a window for the Smarty Debugging Consol and display the data</p><dl>
<dt>Parameters:</dt>
<dd>obj - object to debug</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 144</div>
<h3 id="get_debug_vars()">get_debug_vars</h3>

```php
public static  StdClass **get_debug_vars**(Smarty_Internal_Template|Smarty_Data obj)
```
<div class="details">
<p>Recursively gets variables from all template/data scopes</p><dl>
<dt>Parameters:</dt>
<dd>obj - object to debug</dd>
</dl>
</div>

- - -

