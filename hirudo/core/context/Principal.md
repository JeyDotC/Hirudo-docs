

- - -

**Hirudo\Core\Context\Principal**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L53" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 53</a>

#Class Principal#

**Principal**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/joomla/JoomlaPrincipal.md">Hirudo\Impl\Joomla\JoomlaPrincipal</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/standalone/SAPrincipal.md">Hirudo\Impl\StandAlone\SAPrincipal</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>Principal</span></p>

<div class="comment" id="overview_description"><p>This class represents the current user.</p><p>TODO: setter methods look unnecessary</p></div>



- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a ne Principal object.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isanonimous">isAnonimous</a>()</p><p class="description">Determines if this user is logged in.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getname">getName</a>()</p><p class="description">Gets the current user name. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setname">setName</a>(string name)</p><p class="description">Sets the current user name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>type</span></td>
<td class="description"><p class="name"><a href="#getcredential">getCredential</a>()</p><p class="description">Usually the user password, this may be null depending of the security
system implementation.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setcredential">setCredential</a>(string credential)</p><p class="description">Sets the current user's credential.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getpermissions">getPermissions</a>()</p><p class="description">Gets the array of roles associated to this user.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setpermissions">setPermissions</a>(array permissions)</p><p class="description">Sets the array of roles associated to this user.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/UserExtraData>UserExtraData</a></span></td>
<td class="description"><p class="name"><a href="#getdata">getData</a>()</p><p class="description"></p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L63" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 63</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a ne Principal object.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L72" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 72</a>

<h3 id="isAnonimous()">isAnonimous</h3>
<span class='k'>abstract </span> <span class='nx'>boolean</span> <span class='nf'>isAnonimous</span> ()

<div class="details">
<p>Determines if this user is logged in.</p><dl>
<dt>Returns:</dt>
<dd>True if this user is logged in, false otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L79" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 79</a>

<h3 id="getName()">getName</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getName</span> ()

<div class="details">
<p>Gets the current user name. The name with which the user logs in.</p><dl>
<dt>Returns:</dt>
<dd>the current user name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L88" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 88</a>

<h3 id="setName()">setName</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setName</span> (string name)

<div class="details">
<p>Sets the current user name.</p><dl>
<dt>Parameters:</dt>
<dd>name - The new user name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L98" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 98</a>

<h3 id="getCredential()">getCredential</h3>
<span class='k'></span> <span class='nx'>type</span> <span class='nf'>getCredential</span> ()

<div class="details">
<p>Usually the user password, this may be null depending of the security
system implementation.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L107" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 107</a>

<h3 id="setCredential()">setCredential</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setCredential</span> (string credential)

<div class="details">
<p>Sets the current user's credential.</p><dl>
<dt>Parameters:</dt>
<dd>credential - The new credential.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L116" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 116</a>

<h3 id="getPermissions()">getPermissions</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getPermissions</span> ()

<div class="details">
<p>Gets the array of roles associated to this user.</p><dl>
<dt>Returns:</dt>
<dd>The list of roles associated to this user.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L125" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 125</a>

<h3 id="setPermissions()">setPermissions</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setPermissions</span> (array permissions)

<div class="details">
<p>Sets the array of roles associated to this user.</p><dl>
<dt>Parameters:</dt>
<dd>permissions - A new list of roles associated to this user.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/Principal.php#L133" target='_blank'>framework\hirudo\Hirudo\Core\Context\Principal.php at line 133</a>

<h3 id="getData()">getData</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/UserExtraData>UserExtraData</a></span> <span class='nf'>getData</span> ()

<div class="details">
<p></p>
</div>

- - -

