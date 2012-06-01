

- - -

**Symfony\Component\DependencyInjection\Reference**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Reference.php#L21" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Reference.php at line 21</a>

#Class Reference#

**Reference**




- - -

<p><strong>public  class</strong> <span>Reference</span></p>

<div class="comment" id="overview_description"><p>Reference represents a service reference.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string id, int invalidBehavior, Boolean strict)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name"><a href="#getinvalidbehavior">getInvalidBehavior</a>()</p><p class="description">Returns the behavior to be used when the service does not exist.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#isstrict">isStrict</a>()</p><p class="description">Returns true when this Reference is strict</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Reference.php#L36" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Reference.php at line 36</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string id, int invalidBehavior, Boolean strict)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>invalidBehavior - The behavior when the service does not exist</dd>
<dd>strict - Sets how this reference is validated</dd>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/container.html">Container</a></dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Reference.php#L58" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Reference.php at line 58</a>

<h3 id="getInvalidBehavior()">getInvalidBehavior</h3>
<span class='k'></span> <span class='nx'>int</span> <span class='nf'>getInvalidBehavior</span> ()

<div class="details">
<p>Returns the behavior to be used when the service does not exist.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Reference.php#L68" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Reference.php at line 68</a>

<h3 id="isStrict()">isStrict</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>isStrict</span> ()

<div class="details">
<p>Returns true when this Reference is strict</p>
</div>

- - -

