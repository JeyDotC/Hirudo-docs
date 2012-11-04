

- - -

**Hirudo\Core\Events\Annotations\Listen**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/Annotations/Listen.php#L32" target='_blank'>framework\hirudo\Hirudo\Core\Events\Annotations\Listen.php at line 32</a>

#Class Listen#

**Listen**




- - -

<p><strong>public  class</strong> <span>Listen</span></p>

<div class="comment" id="overview_description"><p>Marks a method as an event listener.</p><p>Usage:</p><p><code>
Listen(to="eventName")
</code></p><p>The listener can optionally be restricted to a call or set of calls by using the
<code>constraints</code> parameter.</p><p>Example:</p><p><code>
Listen(to="eventName", constraints={"App::Module::Task", "AnotherApp::AnotherModule::otherTask", ...})
</code></p><p>Is possible to use regular expressions, just avoid using the slash (/) delimiters.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Annotation.</dt>
<dt>Target("METHOD").</dt>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<string></span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Annotations/Listen.md#constraints"> $constraints</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Annotations/Listen.md#priority"> $priority</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Annotations/Listen.md#to"> $to</a>
                                </p><p class="description"></p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/Annotations/Listen.php#L44" target='_blank'>framework\hirudo\Hirudo\Core\Events\Annotations\Listen.php at line 44</a>

<h3 id="constraints">constraints</h3>
<span class='k'></span> <span class='nx'>array<string></span><span class='no'> $constraints</span><span class='o'> = array()</span>

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/Annotations/Listen.php#L50" target='_blank'>framework\hirudo\Hirudo\Core\Events\Annotations\Listen.php at line 50</a>

<h3 id="priority">priority</h3>
<span class='k'></span> <span class='nx'>int</span><span class='no'> $priority</span><span class='o'> = 0</span>

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/Annotations/Listen.php#L38" target='_blank'>framework\hirudo\Hirudo\Core\Events\Annotations\Listen.php at line 38</a>

<h3 id="to">to</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $to</span><div class="details">
<p></p>
</div>

- - -

