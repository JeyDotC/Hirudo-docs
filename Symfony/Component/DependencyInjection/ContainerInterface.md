

- - -

**Symfony\Component\DependencyInjection\ContainerInterface**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L22" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 22</a>

#Interface ContainerInterface#

**ContainerInterface**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/TaggedContainerInterface.md">TaggedContainerInterface</a> </dd>
</dl>



- - -

<p><strong>public  interface</strong> <span>ContainerInterface</span></p>

<div class="comment" id="overview_description"><p>ContainerInterface is the interface implemented by service container classes.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string id, int invalidBehavior)</p><p class="description">Gets a service.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#has">has</a>(string id)</p><p class="description">Returns true if the given service is defined.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getparameter">getParameter</a>(string name)</p><p class="description">Gets a parameter.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#hasparameter">hasParameter</a>(string name)</p><p class="description">Checks if a parameter exists.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setparameter">setParameter</a>(string name, mixed value)</p><p class="description">Sets a parameter.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#enterscope">enterScope</a>(string name)</p><p class="description">Enters the given scope</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#leavescope">leaveScope</a>(string name)</p><p class="description">Leaves the current scope, and re-enters the parent scope</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addscope">addScope</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/ScopeInterface.md">ScopeInterface</a> scope)</p><p class="description">Adds a scope to the container</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#hasscope">hasScope</a>(string name)</p><p class="description">Whether this container has the given scope</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#isscopeactive">isScopeActive</a>(string name)</p><p class="description">Determines whether the given scope is currently active.
</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L40" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 40</a>

<h3 id="get()">get</h3>
<span class='k'></span> <span class='nx'>object</span> <span class='nf'>get</span> (string id, int invalidBehavior)

<div class="details">
<p>Gets a service.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>invalidBehavior - The behavior when the service does not exist</dd>
<dt>Returns:</dt>
<dd>The associated service</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the service is not defined</dd>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/reference.html">Reference</a></dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L51" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 51</a>

<h3 id="has()">has</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>has</span> (string id)

<div class="details">
<p>Returns true if the given service is defined.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dt>Returns:</dt>
<dd>true if the service is defined, false otherwise</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L64" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 64</a>

<h3 id="getParameter()">getParameter</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getParameter</span> (string name)

<div class="details">
<p>Gets a parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>The parameter value</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the parameter is not defined</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L75" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 75</a>

<h3 id="hasParameter()">hasParameter</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>hasParameter</span> (string name)

<div class="details">
<p>Checks if a parameter exists.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>The presence of parameter in container</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L85" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 85</a>

<h3 id="setParameter()">setParameter</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setParameter</span> (string name, mixed value)

<div class="details">
<p>Sets a parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dd>value - The parameter value</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L95" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 95</a>

<h3 id="enterScope()">enterScope</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>enterScope</span> (string name)

<div class="details">
<p>Enters the given scope</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L105" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 105</a>

<h3 id="leaveScope()">leaveScope</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>leaveScope</span> (string name)

<div class="details">
<p>Leaves the current scope, and re-enters the parent scope</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L115" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 115</a>

<h3 id="addScope()">addScope</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addScope</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/ScopeInterface.md">ScopeInterface</a> scope)

<div class="details">
<p>Adds a scope to the container</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L125" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 125</a>

<h3 id="hasScope()">hasScope</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>hasScope</span> (string name)

<div class="details">
<p>Whether this container has the given scope</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/ContainerInterface.php#L137" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerInterface.php at line 137</a>

<h3 id="isScopeActive()">isScopeActive</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>isScopeActive</span> (string name)

<div class="details">
<p>Determines whether the given scope is currently active.</p><p>It does however not check if the scope actually exists.</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -

