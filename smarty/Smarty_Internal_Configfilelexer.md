- - -

**Smarty\Smarty_Internal_Configfilelexer**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line13" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 13</a>

# Class Smarty_Internal_Configfilelexer #

<pre class="tree">** Smarty_Internal_Configfilelexer **\n</pre>

- - -

<p class="signature">public  class **Smarty_Internal_Configfilelexer**</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Configfilelexer</p></div>

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
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(mixed data, mixed smarty)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#instance()">instance</a>(mixed new_instance)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#yylex()">yylex</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#yypushstate()">yypushstate</a>(mixed state)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#yypopstate()">yypopstate</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#yybegin()">yybegin</a>(mixed state)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#yylex1()">yylex1</a>()</p></td>
</tr>
</table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line17" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 17</a>

<h3 id="counter">counter</h3>
```php
public  mixed **$counter**```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line16" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 16</a>

<h3 id="data">data</h3>
```php
public  mixed **$data** = null```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line21" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 21</a>

<h3 id="line">line</h3>
```php
public  mixed **$line**```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line20" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 20</a>

<h3 id="node">node</h3>
```php
public  mixed **$node**```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line23" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 23</a>

<h3 id="smarty_token_names">smarty_token_names</h3>
```php
public  mixed **$smarty_token_names** = array(...)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line18" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 18</a>

<h3 id="token">token</h3>
```php
public  mixed **$token**```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line19" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 19</a>

<h3 id="value">value</h3>
```php
public  mixed **$value**```
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line26" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 26</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(mixed data, mixed smarty)```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line36" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 36</a>

<h3 id="instance()">instance</h3>
```php
public static  void **instance**(mixed new_instance)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line49" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 49</a>

<h3 id="yylex()">yylex</h3>
```php
public  void **yylex**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line54" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 54</a>

<h3 id="yypushstate()">yypushstate</h3>
```php
public  void **yypushstate**(mixed state)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line60" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 60</a>

<h3 id="yypopstate()">yypopstate</h3>
```php
public  void **yypopstate**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line65" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 65</a>

<h3 id="yybegin()">yybegin</h3>
```php
public  void **yybegin**(mixed state)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_configfilelexer.php.md#line73" class="location">framework\libs\smarty\sysplugins\smarty_internal_configfilelexer.php at line 73</a>

<h3 id="yylex1()">yylex1</h3>
```php
public  void **yylex1**()```
<div class="details">
</div>

- - -

