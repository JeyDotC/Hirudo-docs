

- - -

**Hirudo\Core\Context\SessionStates**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L29" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 29</a>

#Class SessionStates#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Lang/PseudoEnum.md">PseudoEnum</a>
 &gt; **SessionStates**




- - -

<p><strong>public final  class</strong> <span>SessionStates</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Lang/PseudoEnum.md">PseudoEnum</a>

</p>

<div class="comment" id="overview_description"><p>An enum representing the different sessions states.</p></div>



<hr />



<table id="summary_field">
<tr><th colspan="2">Constant Summary</th></tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>str</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/SessionStates.md#active">ACTIVE</a>
                                </p><p class="description">Session is active.</p></td>
</tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>str</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/SessionStates.md#destroyed">DESTROYED</a>
                                </p><p class="description">The session and all of it's data have been destroyed.</p></td>
</tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>str</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/SessionStates.md#error">ERROR</a>
                                </p><p class="description">Something went wrong with the session.</p></td>
</tr>
<tr>
<td>
                                    <span class='k'>final static </span> <span class='nx'>str</span>
                                  </td>
<td class="description"><p class="name" ><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/SessionStates.md#expired">EXPIRED</a>
                                </p><p class="description">Session timeout have been exeeded, normally the session have been
already closed in this case.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Lang\PseudoEnum</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Lang/PseudoEnum.md#namebelongs">nameBelongs</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Lang/PseudoEnum.md#stringtovalue">stringToValue</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Lang/PseudoEnum.md#valuebelongs">valueBelongs</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Lang/PseudoEnum.md#valuetostring">valueToString</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Lang/PseudoEnum.md#values">values</a></td></tr></table>

##Constant Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L34" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 34</a>

<h3 id="ACTIVE">ACTIVE</h3>
<span class='k'>final static </span> <span class='nx'>str</span><span class='no'>ACTIVE</span><span class='o'> = 'active'</span>

<div class="details">
<p>Session is active.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L43" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 43</a>

<h3 id="DESTROYED">DESTROYED</h3>
<span class='k'>final static </span> <span class='nx'>str</span><span class='no'>DESTROYED</span><span class='o'> = 'destroyed'</span>

<div class="details">
<p>The session and all of it's data have been destroyed.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L47" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 47</a>

<h3 id="ERROR">ERROR</h3>
<span class='k'>final static </span> <span class='nx'>str</span><span class='no'>ERROR</span><span class='o'> = 'error'</span>

<div class="details">
<p>Something went wrong with the session.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Session.php#L39" target='_blank'>framework\Hirudo\Core\Context\Session.php at line 39</a>

<h3 id="EXPIRED">EXPIRED</h3>
<span class='k'>final static </span> <span class='nx'>str</span><span class='no'>EXPIRED</span><span class='o'> = 'expired'</span>

<div class="details">
<p>Session timeout have been exeeded, normally the session have been
already closed in this case.</p>
</div>

- - -

