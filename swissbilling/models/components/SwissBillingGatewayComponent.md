- - -

**SwissBilling\Models\Components\SwissBillingGatewayComponent**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Components/SwissBillingGatewayComponent.php.md#line14" class="location">src\SwissBilling\Models\Components\SwissBillingGatewayComponent.php at line 14</a>

# Class SwissBillingGatewayComponent #

<pre class="tree">** SwissBillingGatewayComponent **\n</pre>

- - -

<p class="signature">public  class **SwissBillingGatewayComponent**</p>

<div class="comment" id="overview_description"><p>Description of SwissBillingGatewayComponent</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(mixed wsdl)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> <a href="../../../swissbilling/models/entities/transactionresult.html">TransactionResult</a></td>
<td class="description"><p class="name"><a href="#eshopTransactionRequest()">eshopTransactionRequest</a>(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, Entities\Transaction transaction, <a href="../../../swissbilling/models/entities/debtor.html">Debtor</a> debtor, array items)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> <a href="../../../swissbilling/models/entities/transactionresult.html">TransactionResult</a></td>
<td class="description"><p class="name"><a href="#eshopTransactionStatusRequest()">eshopTransactionStatusRequest</a>(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, string transaction_id, string order_timestamp)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#eshopTransactionAcknowledge()">eshopTransactionAcknowledge</a>(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, type order_id, string date)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#eshopTransactionCancel()">eshopTransactionCancel</a>(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, type order_id, string date)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> <a href="../../../swissbilling/models/entities/transactionresult.html">TransactionResult</a></td>
<td class="description"><p class="name"><a href="#eshopCreditNotification()">eshopCreditNotification</a>(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, type order_id, string date)</p><p class="description"></p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Components/SwissBillingGatewayComponent.php.md#line34" class="location">src\SwissBilling\Models\Components\SwissBillingGatewayComponent.php at line 34</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(mixed wsdl)```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Components/SwissBillingGatewayComponent.php.md#line48" class="location">src\SwissBilling\Models\Components\SwissBillingGatewayComponent.php at line 48</a>

<h3 id="eshopTransactionRequest()">eshopTransactionRequest</h3>
```php
public  <a href="../../../swissbilling/models/entities/transactionresult.html">TransactionResult</a> **eshopTransactionRequest**(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, Entities\Transaction transaction, <a href="../../../swissbilling/models/entities/debtor.html">Debtor</a> debtor, array items)```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Components/SwissBillingGatewayComponent.php.md#line77" class="location">src\SwissBilling\Models\Components\SwissBillingGatewayComponent.php at line 77</a>

<h3 id="eshopTransactionStatusRequest()">eshopTransactionStatusRequest</h3>
```php
public  <a href="../../../swissbilling/models/entities/transactionresult.html">TransactionResult</a> **eshopTransactionStatusRequest**(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, string transaction_id, string order_timestamp)```
<div class="details">
<p></p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd></dd>
<dd>order_timestamp - Timestamp in 'Y-m-d H:i:s' format</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Components/SwissBillingGatewayComponent.php.md#line92" class="location">src\SwissBilling\Models\Components\SwissBillingGatewayComponent.php at line 92</a>

<h3 id="eshopTransactionAcknowledge()">eshopTransactionAcknowledge</h3>
```php
public  void **eshopTransactionAcknowledge**(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, type order_id, string date)```
<div class="details">
<p></p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd></dd>
<dd>date - date in 'Y-m-d H:i:s' format</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Components/SwissBillingGatewayComponent.php.md#line102" class="location">src\SwissBilling\Models\Components\SwissBillingGatewayComponent.php at line 102</a>

<h3 id="eshopTransactionCancel()">eshopTransactionCancel</h3>
```php
public  void **eshopTransactionCancel**(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, type order_id, string date)```
<div class="details">
<p></p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd></dd>
<dd>date - date in 'Y-m-d H:i:s' format</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Components/SwissBillingGatewayComponent.php.md#line114" class="location">src\SwissBilling\Models\Components\SwissBillingGatewayComponent.php at line 114</a>

<h3 id="eshopCreditNotification()">eshopCreditNotification</h3>
```php
public  <a href="../../../swissbilling/models/entities/transactionresult.html">TransactionResult</a> **eshopCreditNotification**(<a href="../../../swissbilling/models/entities/merchant.html">Merchant</a> merchant, type order_id, string date)```
<div class="details">
<p></p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd></dd>
<dd>date - date in 'Y-m-d H:i:s' format</dd>
</dl>
</div>

- - -

