- - -

**SwissBilling\Models\Entities\Debtor**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line10" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 10</a>

# Class Debtor #

<pre class="tree">** Debtor **\n</pre>

- - -

<p class="signature">public  class **Debtor**</p>

<div class="comment" id="overview_description"><p>Description of Debtor</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getCompany_name()">getCompany_name</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setCompany_name()">setCompany_name</a>(mixed company_name)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getTitle()">getTitle</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setTitle()">setTitle</a>(mixed title)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getFirstname()">getFirstname</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setFirstname()">setFirstname</a>(mixed firstname)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getLastname()">getLastname</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setLastname()">setLastname</a>(mixed lastname)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getBirthdate()">getBirthdate</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setBirthdate()">setBirthdate</a>(mixed birthdate)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getAdr1()">getAdr1</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setAdr1()">setAdr1</a>(mixed adr1)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getAdr2()">getAdr2</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setAdr2()">setAdr2</a>(mixed adr2)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getCity()">getCity</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setCity()">setCity</a>(mixed city)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getZip()">getZip</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setZip()">setZip</a>(mixed zip)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getCountry()">getCountry</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setCountry()">setCountry</a>(mixed country)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getEmail()">getEmail</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setEmail()">setEmail</a>(mixed email)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getPhone()">getPhone</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setPhone()">setPhone</a>(mixed phone)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getLanguage()">getLanguage</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setLanguage()">setLanguage</a>(mixed language)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getUser_ID()">getUser_ID</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setUser_ID()">setUser_ID</a>(mixed user_ID)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getIs_SBMember()">getIs_SBMember</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setIs_SBMember()">setIs_SBMember</a>(mixed is_SBMember)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getSBMember_ID()">getSBMember_ID</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setSBMember_ID()">setSBMember_ID</a>(mixed SBMember_ID)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_company_name()">getDeliv_company_name</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_company_name()">setDeliv_company_name</a>(mixed deliv_company_name)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_title()">getDeliv_title</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_title()">setDeliv_title</a>(mixed deliv_title)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_firstname()">getDeliv_firstname</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_firstname()">setDeliv_firstname</a>(mixed deliv_firstname)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_lastname()">getDeliv_lastname</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_lastname()">setDeliv_lastname</a>(mixed deliv_lastname)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_adr1()">getDeliv_adr1</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_adr1()">setDeliv_adr1</a>(mixed deliv_adr1)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_adr2()">getDeliv_adr2</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_adr2()">setDeliv_adr2</a>(mixed deliv_adr2)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_city()">getDeliv_city</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_city()">setDeliv_city</a>(mixed deliv_city)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_zip()">getDeliv_zip</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_zip()">setDeliv_zip</a>(mixed deliv_zip)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getDeliv_country()">getDeliv_country</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setDeliv_country()">setDeliv_country</a>(mixed deliv_country)</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line38" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 38</a>

<h3 id="getCompany_name()">getCompany_name</h3>
```php
public  void **getCompany_name**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line42" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 42</a>

<h3 id="setCompany_name()">setCompany_name</h3>
```php
public  void **setCompany_name**(mixed company_name)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line46" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 46</a>

<h3 id="getTitle()">getTitle</h3>
```php
public  void **getTitle**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line50" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 50</a>

<h3 id="setTitle()">setTitle</h3>
```php
public  void **setTitle**(mixed title)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line54" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 54</a>

<h3 id="getFirstname()">getFirstname</h3>
```php
public  void **getFirstname**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line58" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 58</a>

<h3 id="setFirstname()">setFirstname</h3>
```php
public  void **setFirstname**(mixed firstname)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line62" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 62</a>

<h3 id="getLastname()">getLastname</h3>
```php
public  void **getLastname**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line66" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 66</a>

<h3 id="setLastname()">setLastname</h3>
```php
public  void **setLastname**(mixed lastname)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line70" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 70</a>

<h3 id="getBirthdate()">getBirthdate</h3>
```php
public  void **getBirthdate**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line74" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 74</a>

<h3 id="setBirthdate()">setBirthdate</h3>
```php
public  void **setBirthdate**(mixed birthdate)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line78" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 78</a>

<h3 id="getAdr1()">getAdr1</h3>
```php
public  void **getAdr1**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line82" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 82</a>

<h3 id="setAdr1()">setAdr1</h3>
```php
public  void **setAdr1**(mixed adr1)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line86" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 86</a>

<h3 id="getAdr2()">getAdr2</h3>
```php
public  void **getAdr2**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line90" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 90</a>

<h3 id="setAdr2()">setAdr2</h3>
```php
public  void **setAdr2**(mixed adr2)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line94" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 94</a>

<h3 id="getCity()">getCity</h3>
```php
public  void **getCity**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line98" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 98</a>

<h3 id="setCity()">setCity</h3>
```php
public  void **setCity**(mixed city)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line102" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 102</a>

<h3 id="getZip()">getZip</h3>
```php
public  void **getZip**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line106" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 106</a>

<h3 id="setZip()">setZip</h3>
```php
public  void **setZip**(mixed zip)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line110" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 110</a>

<h3 id="getCountry()">getCountry</h3>
```php
public  void **getCountry**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line114" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 114</a>

<h3 id="setCountry()">setCountry</h3>
```php
public  void **setCountry**(mixed country)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line118" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 118</a>

<h3 id="getEmail()">getEmail</h3>
```php
public  void **getEmail**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line122" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 122</a>

<h3 id="setEmail()">setEmail</h3>
```php
public  void **setEmail**(mixed email)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line126" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 126</a>

<h3 id="getPhone()">getPhone</h3>
```php
public  void **getPhone**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line130" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 130</a>

<h3 id="setPhone()">setPhone</h3>
```php
public  void **setPhone**(mixed phone)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line134" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 134</a>

<h3 id="getLanguage()">getLanguage</h3>
```php
public  void **getLanguage**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line138" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 138</a>

<h3 id="setLanguage()">setLanguage</h3>
```php
public  void **setLanguage**(mixed language)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line142" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 142</a>

<h3 id="getUser_ID()">getUser_ID</h3>
```php
public  void **getUser_ID**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line146" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 146</a>

<h3 id="setUser_ID()">setUser_ID</h3>
```php
public  void **setUser_ID**(mixed user_ID)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line150" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 150</a>

<h3 id="getIs_SBMember()">getIs_SBMember</h3>
```php
public  void **getIs_SBMember**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line154" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 154</a>

<h3 id="setIs_SBMember()">setIs_SBMember</h3>
```php
public  void **setIs_SBMember**(mixed is_SBMember)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line158" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 158</a>

<h3 id="getSBMember_ID()">getSBMember_ID</h3>
```php
public  void **getSBMember_ID**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line162" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 162</a>

<h3 id="setSBMember_ID()">setSBMember_ID</h3>
```php
public  void **setSBMember_ID**(mixed SBMember_ID)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line166" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 166</a>

<h3 id="getDeliv_company_name()">getDeliv_company_name</h3>
```php
public  void **getDeliv_company_name**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line170" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 170</a>

<h3 id="setDeliv_company_name()">setDeliv_company_name</h3>
```php
public  void **setDeliv_company_name**(mixed deliv_company_name)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line174" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 174</a>

<h3 id="getDeliv_title()">getDeliv_title</h3>
```php
public  void **getDeliv_title**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line178" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 178</a>

<h3 id="setDeliv_title()">setDeliv_title</h3>
```php
public  void **setDeliv_title**(mixed deliv_title)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line182" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 182</a>

<h3 id="getDeliv_firstname()">getDeliv_firstname</h3>
```php
public  void **getDeliv_firstname**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line186" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 186</a>

<h3 id="setDeliv_firstname()">setDeliv_firstname</h3>
```php
public  void **setDeliv_firstname**(mixed deliv_firstname)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line190" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 190</a>

<h3 id="getDeliv_lastname()">getDeliv_lastname</h3>
```php
public  void **getDeliv_lastname**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line194" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 194</a>

<h3 id="setDeliv_lastname()">setDeliv_lastname</h3>
```php
public  void **setDeliv_lastname**(mixed deliv_lastname)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line198" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 198</a>

<h3 id="getDeliv_adr1()">getDeliv_adr1</h3>
```php
public  void **getDeliv_adr1**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line202" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 202</a>

<h3 id="setDeliv_adr1()">setDeliv_adr1</h3>
```php
public  void **setDeliv_adr1**(mixed deliv_adr1)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line206" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 206</a>

<h3 id="getDeliv_adr2()">getDeliv_adr2</h3>
```php
public  void **getDeliv_adr2**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line210" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 210</a>

<h3 id="setDeliv_adr2()">setDeliv_adr2</h3>
```php
public  void **setDeliv_adr2**(mixed deliv_adr2)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line214" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 214</a>

<h3 id="getDeliv_city()">getDeliv_city</h3>
```php
public  void **getDeliv_city**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line218" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 218</a>

<h3 id="setDeliv_city()">setDeliv_city</h3>
```php
public  void **setDeliv_city**(mixed deliv_city)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line222" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 222</a>

<h3 id="getDeliv_zip()">getDeliv_zip</h3>
```php
public  void **getDeliv_zip**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line226" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 226</a>

<h3 id="setDeliv_zip()">setDeliv_zip</h3>
```php
public  void **setDeliv_zip**(mixed deliv_zip)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line230" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 230</a>

<h3 id="getDeliv_country()">getDeliv_country</h3>
```php
public  void **getDeliv_country**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/src/SwissBilling/Models/Entities/Debtor.php.md#line234" class="location">src\SwissBilling\Models\Entities\Debtor.php at line 234</a>

<h3 id="setDeliv_country()">setDeliv_country</h3>
```php
public  void **setDeliv_country**(mixed deliv_country)```
<div class="details">
</div>

- - -

