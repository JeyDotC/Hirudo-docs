
- - -

**Smarty\Smarty_Internal_Templatelexer**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 13</div>
#Class Smarty_Internal_Templatelexer#

**Smarty_Internal_Templatelexer**


- - -

<p class="signature">public  class **Smarty_Internal_Templatelexer**</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Templatelexer</p></div>


- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#counter">$counter</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#data">$data</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#line">$line</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#node">$node</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#smarty_token_names">$smarty_token_names</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#state">$state</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#taglineno">$taglineno</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#token">$token</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#value">$value</a></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed data, mixed compiler)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yylex">yylex</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yypushstate">yypushstate</a>(mixed state)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yypopstate">yypopstate</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yybegin">yybegin</a>(mixed state)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yylex1">yylex1</a>()</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 16</div>
<h3 id="counter">counter</h3>

public  mixed $counter
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 15</div>
<h3 id="data">data</h3>

public  mixed $data = null
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 20</div>
<h3 id="line">line</h3>

public  mixed $line
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 19</div>
<h3 id="node">node</h3>

public  mixed $node
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 24</div>
<h3 id="smarty_token_names">smarty_token_names</h3>

public  mixed $smarty_token_names = array(...)
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 22</div>
<h3 id="state">state</h3>

public  mixed $state = 1
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 21</div>
<h3 id="taglineno">taglineno</h3>

public  mixed $taglineno
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 17</div>
<h3 id="token">token</h3>

public  mixed $token
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 18</div>
<h3 id="value">value</h3>

public  mixed $value
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 27</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(mixed data, mixed compiler)
```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 47</div>
<h3 id="yylex()">yylex</h3>

public  void **yylex** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 52</div>
<h3 id="yypushstate()">yypushstate</h3>

public  void **yypushstate** (mixed state)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 58</div>
<h3 id="yypopstate()">yypopstate</h3>

public  void **yypopstate** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 63</div>
<h3 id="yybegin()">yybegin</h3>

public  void **yybegin** (mixed state)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 70</div>
<h3 id="yylex1()">yylex1</h3>

public  void **yylex1** ()<div class="details">
</div>

- - -

