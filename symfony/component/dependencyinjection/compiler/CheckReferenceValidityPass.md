

- - -

**Symfony\Component\DependencyInjection\Compiler\CheckReferenceValidityPass**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/CheckReferenceValidityPass.php#L31" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckReferenceValidityPass.php at line 31</a>

#Class CheckReferenceValidityPass#

**CheckReferenceValidityPass**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>CheckReferenceValidityPass</span></p>

<div class="comment" id="overview_description"><p>Checks the validity of references</p><p>The following checks are performed by this pass:</p>
<ul>
<li>target definitions are not abstract</li>
<li>target definitions are of equal or wider scope</li>
</ul>
<p>- target definitions are in the same scope hierarchy</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/ContainerBuilder.md">ContainerBuilder</a> container)</p><p class="description">Processes the ContainerBuilder to validate References.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/CheckReferenceValidityPass.php#L45" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckReferenceValidityPass.php at line 45</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/ContainerBuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>Processes the ContainerBuilder to validate References.</p>
</div>

- - -

