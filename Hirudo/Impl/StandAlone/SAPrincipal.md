

- - -

**Hirudo\Impl\StandAlone\SAPrincipal**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAPrincipal.php#L32" target='_blank'>framework\Hirudo\Impl\StandAlone\SAPrincipal.php at line 32</a>

#Class SAPrincipal#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md">Principal</a>
 &gt; **SAPrincipal**




- - -

<p><strong>public  class</strong> <span>SAPrincipal</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md">Principal</a>

</p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Hirudo\Core\Annotations\Export(id="principal",:</dt>
<dd>factory="instance")</dd>
</dl>


<hr />

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
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/StandAlone/SAPrincipal.md>SAPrincipal</a></span></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isanonimous">isAnonimous</a>()</p><p class="description">Determines if this user is logged in.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setsession">setSession</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Session.md">Session</a> session)</p><p class="description"></p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\Principal</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#getcredential">getCredential</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#getdata">getData</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#getname">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#getpermissions">getPermissions</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#isanonimous">isAnonimous</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#setcredential">setCredential</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#setname">setName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Principal.md#setpermissions">setPermissions</a></td></tr></table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAPrincipal.php#L60" target='_blank'>framework\Hirudo\Impl\StandAlone\SAPrincipal.php at line 60</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a ne Principal object.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAPrincipal.php#L52" target='_blank'>framework\Hirudo\Impl\StandAlone\SAPrincipal.php at line 52</a>

<h3 id="instance()">instance</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/StandAlone/SAPrincipal.md>SAPrincipal</a></span> <span class='nf'>instance</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAPrincipal.php#L64" target='_blank'>framework\Hirudo\Impl\StandAlone\SAPrincipal.php at line 64</a>

<h3 id="isAnonimous()">isAnonimous</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isAnonimous</span> ()

<div class="details">
<p>Determines if this user is logged in.</p><dl>
<dt>Returns:</dt>
<dd>True if this user is logged in, false otherwise.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAPrincipal.php#L74" target='_blank'>framework\Hirudo\Impl\StandAlone\SAPrincipal.php at line 74</a>

<h3 id="setSession()">setSession</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setSession</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Session.md">Session</a> session)

<div class="details">
<p></p><dl>
<dt>Hirudo\Core\Annotations\Import(id="session").</dt>
</dl>

</div>

- - -

