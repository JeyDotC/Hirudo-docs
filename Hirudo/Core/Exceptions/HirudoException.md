

- - -

**Hirudo\Core\Exceptions\HirudoException**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Exceptions/HirudoException.php#L37" target='_blank'>framework\Hirudo\Core\Exceptions\HirudoException.php at line 37</a>

#Class HirudoException#

\Exception &gt; **HirudoException**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Exceptions/ApplicationNotFoundException.md">ApplicationNotFoundException</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Exceptions/ModuleNotFoundException.md">ModuleNotFoundException</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>HirudoException</span>
<strong>extends</strong> \Exception

</p>

<div class="comment" id="overview_description"><p><p>Base class for exceptions occurred on Hirudo. This class contains the
current ModuleCall.</p></p><p><p>All exceptions thrown by an application that doesn't inherit this class,
are wraped into an instance of this class as the 'previous' exception.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>See Also:</dt>
<dd>\Exception</dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModuleCall.md">ModuleCall</a> call, string message, \Exception previous)</p><p class="description">Creates a HirudoException.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getapp">getApp</a>()</p><p class="description">Gets the name of the application in which this exception were thrown.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getmodule">getModule</a>()</p><p class="description">Gets the name of the module in which this exception were thrown.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#gettask">getTask</a>()</p><p class="description">Gets the task of the application in which this exception were thrown.</p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Exceptions/HirudoException.php#L52" target='_blank'>framework\Hirudo\Core\Exceptions\HirudoException.php at line 52</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModuleCall.md">ModuleCall</a> call, string message, \Exception previous)

<div class="details">
<p>Creates a HirudoException.</p><dl>
<dt>Parameters:</dt>
<dd>call - The module call in which this exception were thrown.</dd>
<dd>message - A useful message.</dd>
<dd>previous - An inner exception.</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Exceptions/HirudoException.php#L70" target='_blank'>framework\Hirudo\Core\Exceptions\HirudoException.php at line 70</a>

<h3 id="getApp()">getApp</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getApp</span> ()

<div class="details">
<p>Gets the name of the application in which this exception were thrown.</p><dl>
<dt>Returns:</dt>
<dd>The application name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Exceptions/HirudoException.php#L79" target='_blank'>framework\Hirudo\Core\Exceptions\HirudoException.php at line 79</a>

<h3 id="getModule()">getModule</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getModule</span> ()

<div class="details">
<p>Gets the name of the module in which this exception were thrown.</p><dl>
<dt>Returns:</dt>
<dd>The module name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Exceptions/HirudoException.php#L87" target='_blank'>framework\Hirudo\Core\Exceptions\HirudoException.php at line 87</a>

<h3 id="getTask()">getTask</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getTask</span> ()

<div class="details">
<p>Gets the task of the application in which this exception were thrown.</p><dl>
<dt>Returns:</dt>
<dd>The task name.</dd>
</dl>

</div>

- - -

