- - -

**Hirudo\Core\Context\Principal**
<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 53</div>
#Class Principal#

**Principal**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/joomla/joomlaprincipal.html">Hirudo\Impl\Joomla\JoomlaPrincipal</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/standalone/saprincipal.html">Hirudo\Impl\StandAlone\SAPrincipal</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Principal**</p>

<div class="comment" id="overview_description"><p>This class represents the current user.</p><p>TODO: setter methods look unnecessary</p></div>

- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a ne Principal object.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">abstract  boolean</td>
<td class="description"><p class="name"><a href="#isAnonimous">isAnonimous</a>()</p><p class="description">Determines if this user is logged in.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getName">getName</a>()</p><p class="description">Gets the current user name. </p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setName">setName</a>(string name)</p><p class="description">Sets the current user name.</p></td>
</tr>
<tr>
<td class="type"> type</td>
<td class="description"><p class="name"><a href="#getCredential">getCredential</a>()</p><p class="description">Usually the user password, this may be null depending of the security
system implementation.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setCredential">setCredential</a>(string credential)</p><p class="description">Sets the current user's credential.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getPermissions">getPermissions</a>()</p><p class="description">Gets the array of roles associated to this user.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setPermissions">setPermissions</a>(array permissions)</p><p class="description">Sets the array of roles associated to this user.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../hirudo/core/context/userextradata.html">UserExtraData</a></td>
<td class="description"><p class="name"><a href="#getData">getData</a>()</p><p class="description"></p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 63</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**()
```
<div class="details">
<p>Creates a ne Principal object.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 72</div>
<h3 id="isAnonimous()">isAnonimous</h3>

```php
public abstract  boolean **isAnonimous**()
```
<div class="details">
<p>Determines if this user is logged in.</p><dl>
<dt>Returns:</dt>
<dd>True if this user is logged in, false otherwise.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 79</div>
<h3 id="getName()">getName</h3>

```php
public  string **getName**()
```
<div class="details">
<p>Gets the current user name. The name with which the user logs in.</p><dl>
<dt>Returns:</dt>
<dd>the current user name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 88</div>
<h3 id="setName()">setName</h3>

```php
public  void **setName**(string name)
```
<div class="details">
<p>Sets the current user name.</p><dl>
<dt>Parameters:</dt>
<dd>name - The new user name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 98</div>
<h3 id="getCredential()">getCredential</h3>

```php
public  type **getCredential**()
```
<div class="details">
<p>Usually the user password, this may be null depending of the security
system implementation.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 107</div>
<h3 id="setCredential()">setCredential</h3>

```php
public  void **setCredential**(string credential)
```
<div class="details">
<p>Sets the current user's credential.</p><dl>
<dt>Parameters:</dt>
<dd>credential - The new credential.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 116</div>
<h3 id="getPermissions()">getPermissions</h3>

```php
public  array **getPermissions**()
```
<div class="details">
<p>Gets the array of roles associated to this user.</p><dl>
<dt>Returns:</dt>
<dd>The list of roles associated to this user.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 125</div>
<h3 id="setPermissions()">setPermissions</h3>

```php
public  void **setPermissions**(array permissions)
```
<div class="details">
<p>Sets the array of roles associated to this user.</p><dl>
<dt>Parameters:</dt>
<dd>permissions - A new list of roles associated to this user.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Principal.php at line 133</div>
<h3 id="getData()">getData</h3>

```php
public  <a href="../../../hirudo/core/context/userextradata.html">UserExtraData</a> **getData**()
```
<div class="details">
<p></p></div>

- - -

