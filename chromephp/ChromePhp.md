- - -

**ChromePhp\ChromePhp**
<div class="location">ChromePhp.php at line 25</div>
#Class ChromePhp#

**ChromePhp**


- - -

<p class="signature">public  class **ChromePhp**</p>

<div class="comment" id="overview_description"><p>Server Side Chrome PHP debugger class</p></div>

<dl>
<dt>Author:</dt>
<dd>Craig Campbell <iamcraigcampbell@gmail.com></dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_backtraces">$_backtraces</a></p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  bool</td>
<td class="description"><p class="name"><a href="#_error_triggered">$_error_triggered</a></p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected static  <a href="../chromephp/chromephp.html">ChromePhp</a></td>
<td class="description"><p class="name"><a href="#_instance">$_instance</a></p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_processed">$_processed</a></p><p class="description">Prevent recursion when working with objects referring to each other</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_settings">$_settings</a></p><p class="description"></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type">private  void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">constructor</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  <a href="../chromephp/chromephp.html">ChromePhp</a></td>
<td class="description"><p class="name"><a href="#getInstance">getInstance</a>()</p><p class="description">gets instance of this class</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#log">log</a>(string label, mixed value, string severity)</p><p class="description">logs a variable to the console</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#warn">warn</a>(string label, mixed value)</p><p class="description">logs a warning to the console</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#error">error</a>(string label, mixed value)</p><p class="description">logs an error to the console</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#group">group</a>(string value)</p><p class="description">sends a group log</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#info">info</a>(string value)</p><p class="description">sends an info log</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#groupCollapsed">groupCollapsed</a>(string value)</p><p class="description">sends a collapsed group log</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#groupEnd">groupEnd</a>(string value)</p><p class="description">ends a group log</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addSetting">addSetting</a>(string key, mixed value)</p><p class="description">adds a setting</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addSettings">addSettings</a>(array settings)</p><p class="description">add ability to set multiple settings in one call</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getSetting">getSetting</a>(string key)</p><p class="description">gets a setting</p></td>
</tr>
</table>

##Field Detail##
<div class="location">ChromePhp.php at line 37</div>
<h3 id="_backtraces">_backtraces</h3>
```php
protected  array **$_backtraces** = array()```
<div class="details">
<p></p></div>

- - -

<div class="location">ChromePhp.php at line 42</div>
<h3 id="_error_triggered">_error_triggered</h3>
```php
protected  bool **$_error_triggered** = false```
<div class="details">
<p></p></div>

- - -

<div class="location">ChromePhp.php at line 52</div>
<h3 id="_instance">_instance</h3>
```php
protected static  <a href="../chromephp/chromephp.html">ChromePhp</a> **$_instance**```
<div class="details">
<p></p></div>

- - -

<div class="location">ChromePhp.php at line 59</div>
<h3 id="_processed">_processed</h3>
```php
protected  array **$_processed** = array()```
<div class="details">
<p>Prevent recursion when working with objects referring to each other</p></div>

- - -

<div class="location">ChromePhp.php at line 47</div>
<h3 id="_settings">_settings</h3>
```php
protected  array **$_settings** = array(...)```
<div class="details">
<p></p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">ChromePhp.php at line 64</div>
<h3 id="__construct()">__construct</h3>
```php
private  void **__construct**()```
<div class="details">
<p>constructor</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">ChromePhp.php at line 75</div>
<h3 id="getInstance()">getInstance</h3>
```php
public static  <a href="../chromephp/chromephp.html">ChromePhp</a> **getInstance**()```
<div class="details">
<p>gets instance of this class</p></div>

- - -

<div class="location">ChromePhp.php at line 90</div>
<h3 id="log()">log</h3>
```php
public static  void **log**(string label, mixed value, string severity)```
<div class="details">
<p>logs a variable to the console</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd></dd>
<dd>severity - ChromePhp::LOG || ChromePhp::WARN || ChromePhp::ERROR</dd>
</dl>
</div>

- - -

<div class="location">ChromePhp.php at line 109</div>
<h3 id="warn()">warn</h3>
```php
public static  void **warn**(string label, mixed value)```
<div class="details">
<p>logs a warning to the console</p></div>

- - -

<div class="location">ChromePhp.php at line 120</div>
<h3 id="error()">error</h3>
```php
public static  void **error**(string label, mixed value)```
<div class="details">
<p>logs an error to the console</p></div>

- - -

<div class="location">ChromePhp.php at line 129</div>
<h3 id="group()">group</h3>
```php
public static  void **group**(string value)```
<div class="details">
<p>sends a group log</p></div>

- - -

<div class="location">ChromePhp.php at line 138</div>
<h3 id="info()">info</h3>
```php
public static  void **info**(string value)```
<div class="details">
<p>sends an info log</p></div>

- - -

<div class="location">ChromePhp.php at line 147</div>
<h3 id="groupCollapsed()">groupCollapsed</h3>
```php
public static  void **groupCollapsed**(string value)```
<div class="details">
<p>sends a collapsed group log</p></div>

- - -

<div class="location">ChromePhp.php at line 156</div>
<h3 id="groupEnd()">groupEnd</h3>
```php
public static  void **groupEnd**(string value)```
<div class="details">
<p>ends a group log</p></div>

- - -

<div class="location">ChromePhp.php at line 328</div>
<h3 id="addSetting()">addSetting</h3>
```php
public  void **addSetting**(string key, mixed value)```
<div class="details">
<p>adds a setting</p></div>

- - -

<div class="location">ChromePhp.php at line 338</div>
<h3 id="addSettings()">addSettings</h3>
```php
public  void **addSettings**(array settings)```
<div class="details">
<p>add ability to set multiple settings in one call</p></div>

- - -

<div class="location">ChromePhp.php at line 350</div>
<h3 id="getSetting()">getSetting</h3>
```php
public  mixed **getSetting**(string key)```
<div class="details">
<p>gets a setting</p></div>

- - -

