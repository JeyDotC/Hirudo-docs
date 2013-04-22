

- - -

**Hirudo\Core\Events\Dispatcher\ListenerHolder**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L10" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 10</a>

#Class ListenerHolder#

**ListenerHolder**




- - -

<p><strong>public  class</strong> <span>ListenerHolder</span></p>



<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed listener, mixed eventName, mixed constraints, bool isDeferred, str virtualId, str overrides)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#create">create</a>(mixed listener, mixed eventName, mixed constraints, str overrides)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#createvirtual">createVirtual</a>(mixed listener, mixed eventName, mixed constraints, mixed virtualId, str overrides)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#createdeferred">createDeferred</a>(mixed listener, mixed eventName, mixed constraints, str overrides)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#createvirtualdeferred">createVirtualDeferred</a>(mixed listener, mixed eventName, mixed constraints, mixed virtualId, str overrides)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getoverrides">getOverrides</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#run">run</a>(Event event)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getlistener">getListener</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#geteventname">getEventName</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getconstraints">getConstraints</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getisdeferred">getIsDeferred</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getisvirtual">getIsVirtual</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getvirtualid">getVirtualId</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setlistener">setListener</a>(mixed listener)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getoverriddenid">getOverriddenId</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getpriority">getPriority</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setpriority">setPriority</a>(mixed priority)</p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L39" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 39</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (mixed listener, mixed eventName, mixed constraints, bool isDeferred, str virtualId, str overrides)

<div class="details">

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L23" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 23</a>

<h3 id="create()">create</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>create</span> (mixed listener, mixed eventName, mixed constraints, str overrides)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L27" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 27</a>

<h3 id="createVirtual()">createVirtual</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>createVirtual</span> (mixed listener, mixed eventName, mixed constraints, mixed virtualId, str overrides)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L31" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 31</a>

<h3 id="createDeferred()">createDeferred</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>createDeferred</span> (mixed listener, mixed eventName, mixed constraints, str overrides)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L35" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 35</a>

<h3 id="createVirtualDeferred()">createVirtualDeferred</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>createVirtualDeferred</span> (mixed listener, mixed eventName, mixed constraints, mixed virtualId, str overrides)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L51" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 51</a>

<h3 id="getOverrides()">getOverrides</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getOverrides</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L55" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 55</a>

<h3 id="run()">run</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>run</span> (Event event)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L62" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 62</a>

<h3 id="getListener()">getListener</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getListener</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L66" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 66</a>

<h3 id="getEventName()">getEventName</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getEventName</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L70" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 70</a>

<h3 id="getConstraints()">getConstraints</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getConstraints</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L74" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 74</a>

<h3 id="getIsDeferred()">getIsDeferred</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getIsDeferred</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L78" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 78</a>

<h3 id="getIsVirtual()">getIsVirtual</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getIsVirtual</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L82" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 82</a>

<h3 id="getVirtualId()">getVirtualId</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getVirtualId</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L86" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 86</a>

<h3 id="setListener()">setListener</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setListener</span> (mixed listener)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L90" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 90</a>

<h3 id="getOverriddenId()">getOverriddenId</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getOverriddenId</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L125" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 125</a>

<h3 id="getPriority()">getPriority</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getPriority</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Events/Dispatcher/ListenerHolder.php#L129" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\ListenerHolder.php at line 129</a>

<h3 id="setPriority()">setPriority</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setPriority</span> (mixed priority)

<div class="details">

</div>

- - -

