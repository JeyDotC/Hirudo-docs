

- - -

**Hirudo\Core\Events\Annotations\ForCall**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/Annotations/ForCall.php#L30" target='_blank'>framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 30</a>

#Class ForCall#

**ForCall**




- - -

<p><strong>public  class</strong> <span>ForCall</span></p>

<div class="comment" id="overview_description"><p><p>Signals a Task event listener to only listen the event
when the current call matches the given characteristics.</p></p><p>Example:</p><p><code>
ForCall(app="MyApp", module="Amodule", task="aTask")
</code></p><p><p>Indicates that the event listener will only listen the event when the call
is for the 'MyApp' application on the 'Amodule' module in the 'aTask' task.</p></p><p><p>Omitting any of those characteristics indicates that the event will be
listened for any value of it. For example, omitting the app and module values
will cause the event to be listened for any application and module but only on
the 'aTask' task.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Annotation.</dt>
<dt>Target("CLASS").</dt>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Annotations/ForCall.md#app"> $app</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Annotations/ForCall.md#module"> $module</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Annotations/ForCall.md#task"> $task</a>
                                </p><p class="description"></p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/Annotations/ForCall.php#L36" target='_blank'>framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 36</a>

<h3 id="app">app</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $app</span><span class='o'> = &quot;&quot;</span>

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/Annotations/ForCall.php#L42" target='_blank'>framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 42</a>

<h3 id="module">module</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $module</span><span class='o'> = &quot;&quot;</span>

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Events/Annotations/ForCall.php#L48" target='_blank'>framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 48</a>

<h3 id="task">task</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $task</span><span class='o'> = &quot;&quot;</span>

<div class="details">
<p></p>
</div>

- - -

