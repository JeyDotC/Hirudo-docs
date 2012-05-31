- - -

**SwissBilling\Modules\TransactionTest**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Modules/TransactionTest/TransactionTest.php.md#line15" class="location">src\SwissBilling\Modules\TransactionTest\TransactionTest.php at line 15</a>

# Class TransactionTest #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html">Module</a>\n    *** TransactionTest **\n</pre>

- - -

<p class="signature">public  class **TransactionTest**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html">Module</a>

</p>

<div class="comment" id="overview_description"><p>Description of SwissBillingTest</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#context">context</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#currentUser">currentUser</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#headers">headers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#request">request</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#route">route</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#onModuleReady()">onModuleReady</a>()</p><p class="description">This function is called before a task execution, is
useful for taking actions prior the execution of any task such as
initializing objects common to all tasks.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#index()">index</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#test()">test</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#error()">error</a>(mixed timestamp)</p><p class="description">object(SwissBilling\Models\Entities\TransactionResult)[62]
private 'transaction_id' => int 0
private 'url' => null
private 'merchantmsg' => string 'To be defined later' (length=19)
private 'debtormsg' => string 'To be defined later' (length=19)
private 'invoicing_costs' => float 5
private 'partial_payment' => int 0
private 'partial_payment_fees' => float 0
private 'partial_payment_rate' => float 0
private 'partial_payment_table' => null
private 'sb_member_id' => null
private 'status' => string 'Test approved' (length=13)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#success()">success</a>(mixed trans, mixed timestamp)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#cancel()">cancel</a>()</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#addMessage()">addMessage</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#assign()">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#assignMany()">assignMany</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#component()">component</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#display()">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#getAppName()">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#getModuleDir()">getModuleDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#getName()">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#getRendered()">getRendered</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#getTask()">getTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#onModuleReady()">onModuleReady</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#renderGet()">renderGet</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#setAppName()">setAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/module.html#setDefaultTask()">setDefaultTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Modules/TransactionTest/TransactionTest.php.md#line29" class="location">src\SwissBilling\Modules\TransactionTest\TransactionTest.php at line 29</a>

<h3 id="onModuleReady()">onModuleReady</h3>
```php
protected  void **onModuleReady**()```
<div class="details">
<p>This function is called before a task execution, is
useful for taking actions prior the execution of any task such as
initializing objects common to all tasks.</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Modules/TransactionTest/TransactionTest.php.md#line34" class="location">src\SwissBilling\Modules\TransactionTest\TransactionTest.php at line 34</a>

<h3 id="index()">index</h3>
```php
public  void **index**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Modules/TransactionTest/TransactionTest.php.md#line39" class="location">src\SwissBilling\Modules\TransactionTest\TransactionTest.php at line 39</a>

<h3 id="test()">test</h3>
```php
public  void **test**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Modules/TransactionTest/TransactionTest.php.md#line65" class="location">src\SwissBilling\Modules\TransactionTest\TransactionTest.php at line 65</a>

<h3 id="error()">error</h3>
```php
public  void **error**(mixed timestamp)```
<div class="details">
<p>object(SwissBilling\Models\Entities\TransactionResult)[62]
private 'transaction_id' => int 0
private 'url' => null
private 'merchantmsg' => string 'To be defined later' (length=19)
private 'debtormsg' => string 'To be defined later' (length=19)
private 'invoicing_costs' => float 5
private 'partial_payment' => int 0
private 'partial_payment_fees' => float 0
private 'partial_payment_rate' => float 0
private 'partial_payment_table' => null
private 'sb_member_id' => null
private 'status' => string 'Test approved' (length=13)</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Modules/TransactionTest/TransactionTest.php.md#line72" class="location">src\SwissBilling\Modules\TransactionTest\TransactionTest.php at line 72</a>

<h3 id="success()">success</h3>
```php
public  void **success**(mixed trans, mixed timestamp)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Modules/TransactionTest/TransactionTest.php.md#line79" class="location">src\SwissBilling\Modules\TransactionTest\TransactionTest.php at line 79</a>

<h3 id="cancel()">cancel</h3>
```php
public  void **cancel**()```
<div class="details">
</div>

- - -

