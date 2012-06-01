

- - -

**Hirudo\Core\Exceptions\ApplicationNotFoundException**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Exceptions/ApplicationNotFoundException.php#L29" >framework\hirudo\Hirudo\Core\Exceptions\ApplicationNotFoundException.php at line 29</a>

#Class ApplicationNotFoundException#

\Exception
* <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.md">HirudoException</a>
        * **ApplicationNotFoundException**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>ApplicationNotFoundException</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.md">HirudoException</a>

</p>

<div class="comment" id="overview_description"><p>Thrown when there is an attempt to call a non existent application</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string app, string path)</p><p class="description">Creates an ApplicationNotFoundException.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Exceptions\HirudoException</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.md">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.md">getApp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.md">getModule</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.md">getTask</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Exceptions/ApplicationNotFoundException.php#L37" >framework\hirudo\Hirudo\Core\Exceptions\ApplicationNotFoundException.php at line 37</a>

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

