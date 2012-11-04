

- - -

**Hirudo\Core\Exceptions\ApplicationNotFoundException**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Exceptions/ApplicationNotFoundException.php#L29" target='_blank'>framework\hirudo\Hirudo\Core\Exceptions\ApplicationNotFoundException.php at line 29</a>

#Class ApplicationNotFoundException#

\Exception &gt; <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Exceptions/HirudoException.md">HirudoException</a>
 &gt; **ApplicationNotFoundException**




- - -

<p><strong>public  class</strong> <span>ApplicationNotFoundException</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Exceptions/HirudoException.md">HirudoException</a>

</p>

<div class="comment" id="overview_description"><p>Thrown when there is an attempt to call a non existent application</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string app, string path)</p><p class="description">Creates an ApplicationNotFoundException.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Exceptions\HirudoException</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Exceptions/HirudoException.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Exceptions/HirudoException.md#getapp">getApp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Exceptions/HirudoException.md#getmodule">getModule</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Exceptions/HirudoException.md#gettask">getTask</a></td></tr></table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Exceptions/ApplicationNotFoundException.php#L37" target='_blank'>framework\hirudo\Hirudo\Core\Exceptions\ApplicationNotFoundException.php at line 37</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string app, string path)

<div class="details">
<p>Creates an ApplicationNotFoundException.</p><dl>
<dt>Parameters:</dt>
<dd>app - The application name.</dd>
<dd>path - The directory in which the application should be.</dd>
</dl>

</div>

- - -

