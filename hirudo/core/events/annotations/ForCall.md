
- - -

**Hirudo\Core\Events\Annotations\ForCall**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 30#L30 class="location">framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 30</a>

#Class ForCall#

**ForCall**




- - -

<p class="signature">public  class **ForCall**</p>

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


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#app"> $app</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#module"> $module</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#task"> $task</a>
                                </p><p class="description"></p></td>
</tr>
</table>

