- - -

# Functions #

- - -

<table id="summary_function" class="title">
<tr><th colspan="2" class="title">Function Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addPass()">addPass</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, string type)</p><p class="description">Adds a pass.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getAfterRemovingPasses()">getAfterRemovingPasses</a>()</p><p class="description">Gets all passes for the AfterRemoving pass.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getBeforeOptimizationPasses()">getBeforeOptimizationPasses</a>()</p><p class="description">Gets all passes for the BeforeOptimization pass.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getBeforeRemovingPasses()">getBeforeRemovingPasses</a>()</p><p class="description">Gets all passes for the BeforeRemoving pass.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getMergePass()">getMergePass</a>()</p><p class="description">Gets all passes for the Merge pass.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getOptimizationPasses()">getOptimizationPasses</a>()</p><p class="description">Gets all passes for the Optimization pass.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getPasses()">getPasses</a>()</p><p class="description">Returns all passes in order to be processed.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getRemovingPasses()">getRemovingPasses</a>()</p><p class="description">Gets all passes for the Removing pass.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setAfterRemovingPasses()">setAfterRemovingPasses</a>(array passes)</p><p class="description">Sets the AfterRemoving passes.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setBeforeOptimizationPasses()">setBeforeOptimizationPasses</a>(array passes)</p><p class="description">Sets the BeforeOptimization passes.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setBeforeRemovingPasses()">setBeforeRemovingPasses</a>(array passes)</p><p class="description">Sets the BeforeRemoving passes.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setMergePass()">setMergePass</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass)</p><p class="description">Sets the Merge Pass.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setOptimizationPasses()">setOptimizationPasses</a>(array passes)</p><p class="description">Sets the Optimization passes.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setRemovingPasses()">setRemovingPasses</a>(array passes)</p><p class="description">Sets the Removing passes.</p></td>
</tr>
</table>

<h2 id="detail_function">Function Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line76" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 76</a>

<h3 id="addPass()">addPass</h3>
```php
public  void **addPass**(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, string type)```
<div class="details">
<p>Adds a pass.</p>
<dl>
<dt>Parameters:</dt>
<dd>pass - A Compiler pass</dd>
<dd>type - The pass type</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - when a pass type doesn't exist</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line94" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 94</a>

<h3 id="getAfterRemovingPasses()">getAfterRemovingPasses</h3>
```php
public  array **getAfterRemovingPasses**()```
<div class="details">
<p>Gets all passes for the AfterRemoving pass.</p>
<dl>
<dt>Returns:</dt>
<dd>An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line106" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 106</a>

<h3 id="getBeforeOptimizationPasses()">getBeforeOptimizationPasses</h3>
```php
public  array **getBeforeOptimizationPasses**()```
<div class="details">
<p>Gets all passes for the BeforeOptimization pass.</p>
<dl>
<dt>Returns:</dt>
<dd>An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line118" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 118</a>

<h3 id="getBeforeRemovingPasses()">getBeforeRemovingPasses</h3>
```php
public  array **getBeforeRemovingPasses**()```
<div class="details">
<p>Gets all passes for the BeforeRemoving pass.</p>
<dl>
<dt>Returns:</dt>
<dd>An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line154" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 154</a>

<h3 id="getMergePass()">getMergePass</h3>
```php
public  array **getMergePass**()```
<div class="details">
<p>Gets all passes for the Merge pass.</p>
<dl>
<dt>Returns:</dt>
<dd>An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line130" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 130</a>

<h3 id="getOptimizationPasses()">getOptimizationPasses</h3>
```php
public  array **getOptimizationPasses**()```
<div class="details">
<p>Gets all passes for the Optimization pass.</p>
<dl>
<dt>Returns:</dt>
<dd>An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line55" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 55</a>

<h3 id="getPasses()">getPasses</h3>
```php
public  array **getPasses**()```
<div class="details">
<p>Returns all passes in order to be processed.</p>
<dl>
<dt>Returns:</dt>
<dd>An array of all passes to process</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line142" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 142</a>

<h3 id="getRemovingPasses()">getRemovingPasses</h3>
```php
public  array **getRemovingPasses**()```
<div class="details">
<p>Gets all passes for the Removing pass.</p>
<dl>
<dt>Returns:</dt>
<dd>An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line178" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 178</a>

<h3 id="setAfterRemovingPasses()">setAfterRemovingPasses</h3>
```php
public  void **setAfterRemovingPasses**(array passes)```
<div class="details">
<p>Sets the AfterRemoving passes.</p>
<dl>
<dt>Parameters:</dt>
<dd>passes - An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line190" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 190</a>

<h3 id="setBeforeOptimizationPasses()">setBeforeOptimizationPasses</h3>
```php
public  void **setBeforeOptimizationPasses**(array passes)```
<div class="details">
<p>Sets the BeforeOptimization passes.</p>
<dl>
<dt>Parameters:</dt>
<dd>passes - An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line202" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 202</a>

<h3 id="setBeforeRemovingPasses()">setBeforeRemovingPasses</h3>
```php
public  void **setBeforeRemovingPasses**(array passes)```
<div class="details">
<p>Sets the BeforeRemoving passes.</p>
<dl>
<dt>Parameters:</dt>
<dd>passes - An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line166" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 166</a>

<h3 id="setMergePass()">setMergePass</h3>
```php
public  void **setMergePass**(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass)```
<div class="details">
<p>Sets the Merge Pass.</p>
<dl>
<dt>Parameters:</dt>
<dd>pass - The merge pass</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line214" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 214</a>

<h3 id="setOptimizationPasses()">setOptimizationPasses</h3>
```php
public  void **setOptimizationPasses**(array passes)```
<div class="details">
<p>Sets the Optimization passes.</p>
<dl>
<dt>Parameters:</dt>
<dd>passes - An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/PassConfig.php.md#line226" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\PassConfig.php at line 226</a>

<h3 id="setRemovingPasses()">setRemovingPasses</h3>
```php
public  void **setRemovingPasses**(array passes)```
<div class="details">
<p>Sets the Removing passes.</p>
<dl>
<dt>Parameters:</dt>
<dd>passes - An array of passes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

