

- - -

**Hirudo\Core\Events\Dispatcher\CachedHirudoDispatcher**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Events/Dispatcher/CachedHirudoDispatcher.php#L12" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\CachedHirudoDispatcher.php at line 12</a>

#Class CachedHirudoDispatcher#

EventDispatcher &gt; <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md">HirudoDispatcher</a>
 &gt; **CachedHirudoDispatcher**




- - -

<p><strong>public  class</strong> <span>CachedHirudoDispatcher</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md">HirudoDispatcher</a>

</p>

<div class="comment" id="overview_description"><p>Description of CachedHirudoDispatcher</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Constant Summary</th></tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>str</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/CachedHirudoDispatcher.md#cache_salt">CACHE_SALT</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md">HirudoDispatcher</a> delegate, Cache cache)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadobjectlisteners">loadObjectListeners</a>(ReflectionClass reflectedObject, mixed object)</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Events\Dispatcher\HirudoDispatcher</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md#addlistener">addListener</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md#dodispatch">doDispatch</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md#loadobjectlisteners">loadObjectListeners</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md#removelistener">removeListener</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md#subscribeobject">subscribeObject</a></td></tr></table>

##Constant Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Events/Dispatcher/CachedHirudoDispatcher.php#L14" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\CachedHirudoDispatcher.php at line 14</a>

<h3 id="CACHE_SALT">CACHE_SALT</h3>
<span class='k'>final static </span> <span class='nx'>str</span><span class='no'>CACHE_SALT</span><span class='o'> = &quot;@[Hirudo.Dispatcher]&quot;</span>

<div class="details">

</div>

- - -

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Events/Dispatcher/CachedHirudoDispatcher.php#L29" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\CachedHirudoDispatcher.php at line 29</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/Dispatcher/HirudoDispatcher.md">HirudoDispatcher</a> delegate, Cache cache)

<div class="details">

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Events/Dispatcher/CachedHirudoDispatcher.php#L34" target='_blank'>framework\Hirudo\Core\Events\Dispatcher\CachedHirudoDispatcher.php at line 34</a>

<h3 id="loadObjectListeners()">loadObjectListeners</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>loadObjectListeners</span> (ReflectionClass reflectedObject, mixed object)

<div class="details">

</div>

- - -

