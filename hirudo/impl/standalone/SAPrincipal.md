- - -

**Hirudo\Impl\StandAlone\SAPrincipal**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SAPrincipal.php.md#line32" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SAPrincipal.php at line 32</a>

# Class SAPrincipal #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html">Principal</a>\n    *** SAPrincipal **\n</pre>

- - -

<p class="signature">public  class **SAPrincipal**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html">Principal</a>

</p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Hirudo\Core\Annotations\Export(id="principal",:</dt>
<dd>factory="instance")</dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>()</p><p class="description">Creates a ne Principal object.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  <a href="../../../hirudo/impl/standalone/saprincipal.html">SAPrincipal</a></td>
<td class="description"><p class="name"><a href="#instance()">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#isAnonimous()">isAnonimous</a>()</p><p class="description">Determines if this user is logged in.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setSession()">setSession</a>(Session session)</p><p class="description"></p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\Principal</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#getCredential()">getCredential</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#getData()">getData</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#getName()">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#getPermissions()">getPermissions</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#isAnonimous()">isAnonimous</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#setCredential()">setCredential</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#setName()">setName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/principal.html#setPermissions()">setPermissions</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SAPrincipal.php.md#line60" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SAPrincipal.php at line 60</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
<p>Creates a ne Principal object.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SAPrincipal.php.md#line52" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SAPrincipal.php at line 52</a>

<h3 id="instance()">instance</h3>
```php
public static  <a href="../../../hirudo/impl/standalone/saprincipal.html">SAPrincipal</a> **instance**()```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SAPrincipal.php.md#line64" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SAPrincipal.php at line 64</a>

<h3 id="isAnonimous()">isAnonimous</h3>
```php
public  boolean **isAnonimous**()```
<div class="details">
<p>Determines if this user is logged in.</p><dl>
<dt>Returns:</dt>
<dd>True if this user is logged in, false otherwise.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/StandAlone/SAPrincipal.php.md#line74" class="location">framework\hirudo\Hirudo\Impl\StandAlone\SAPrincipal.php at line 74</a>

<h3 id="setSession()">setSession</h3>
```php
public  void **setSession**(Session session)```
<div class="details">
<p></p><dl>
<dt>Hirudo\Core\Annotations\Import(id="session").</dt>
</dl>
</div>

- - -

