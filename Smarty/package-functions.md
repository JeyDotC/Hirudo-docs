- - -

#Functions#

- - -

<table id="summary_function" class="title">
<tr><th colspan="2" class="title">Function Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#_smarty_regex_replace_check">_smarty_regex_replace_check</a>(string search)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smartyautoload">smartyAutoload</a>(mixed class)</p><p class="description">Autoloader</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_block_textformat">smarty_block_textformat</a>(array params, string content, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template, boolean &$repeat, mixed repeat)</p><p class="description">Smarty {textformat}{/textformat} block pluginType:     block function
Name:     textformat
Purpose:  format text a certain way with preset styles
or custom wrap/indent settings
Params:


style         - string (email)
indent        - integer (0)
wrap          - integer (80)
wrap_char     - string ("\n")
indent_char   - string (" ")
wrap_boundary - boolean (true)

</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string|null</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_counter">smarty_function_counter</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {counter} function pluginType:     function
Name:     counter
Purpose:  print out a counter value</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string|null</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_cycle">smarty_function_cycle</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {cycle} function pluginType:     function
Name:     cycle
Date:     May 3, 2002
Purpose:  cycle through given values
Params:


name      - name of cycle (optional)
values    - comma separated list of values to cycle, or an array of values to cycle
(this can be left out for subsequent calls)
reset     - boolean - resets given var to true

- print     - boolean - print var or not. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_escape_special_chars">smarty_function_escape_special_chars</a>(string string)</p><p class="description">escape_special_chars common functionFunction: smarty_function_escape_special_chars
Purpose:  used by other smarty functions to escape
special chars except for already escaped ones</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string|null</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_fetch">smarty_function_fetch</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {fetch} pluginType:     function
Name:     fetch
Purpose:  fetch file, web or ftp data and display results</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_checkboxes">smarty_function_html_checkboxes</a>(array params, object template)</p><p class="description">Smarty {html_checkboxes} function pluginFile:       function.html_checkboxes.php
Type:       function
Name:       html_checkboxes
Date:       24.Feb.2003
Purpose:    Prints out a list of checkbox input types
Examples:

{html_checkboxes values=$ids output=$names}
{html_checkboxes values=$ids name='box' separator='' output=$names}
{html_checkboxes values=$ids checked=$checked separator='' output=$names}

Params:


name       (optional) - string default "checkbox"
values     (required) - array
options    (optional) - associative array
checked    (optional) - array default not set
separator  (optional) - ie  or &nbsp;
output     (optional) - the output next to each checkbox
assign     (optional) - assign the output as an array to this variable
escape     (optional) - escape the content (not value), defaults to true

</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_checkboxes_output">smarty_function_html_checkboxes_output</a>(mixed name, mixed value, mixed output, mixed selected, mixed extra, mixed separator, mixed labels, mixed label_ids, bool escape)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_image">smarty_function_html_image</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {html_image} function pluginType:     function
Name:     html_image
Date:     Feb 24, 2003
Purpose:  format HTML tags for the image
Examples: {html_image file="/images/masthead.gif"}
Output:   
Params:


file        - (required) - file (and path) of image
height      - (optional) - image height (default actual height)
width       - (optional) - image width (default actual width)
basedir     - (optional) - base directory for absolute paths, default is environment variable DOCUMENT_ROOT
path_prefix - prefix for path output (optional, default empty)

</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_options">smarty_function_html_options</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {html_options} function pluginType:     function
Name:     html_options
Purpose:  Prints the list of  tags generated from
the passed parameters
Params:


name       (optional) - string default "select"
values     (required) - if no options supplied) - array
options    (required) - if no values supplied) - associative array
selected   (optional) - string default not set
output     (required) - if not options supplied) - array
id         (optional) - string default not set
class      (optional) - string default not set

</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_options_optgroup">smarty_function_html_options_optgroup</a>(mixed key, mixed values, mixed selected, mixed id, mixed class, mixed idx)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_options_optoutput">smarty_function_html_options_optoutput</a>(mixed key, mixed value, mixed selected, mixed id, mixed class, mixed idx)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_radios">smarty_function_html_radios</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {html_radios} function pluginFile:       function.html_radios.php
Type:       function
Name:       html_radios
Date:       24.Feb.2003
Purpose:    Prints out a list of radio input types
Params:


name       (optional) - string default "radio"
values     (required) - array
options    (required) - associative array
checked    (optional) - array default not set
separator  (optional) - ie  or &nbsp;
output     (optional) - the output next to each radio button
assign     (optional) - assign the output as an array to this variable
escape     (optional) - escape the content (not value), defaults to true


Examples:

{html_radios values=$ids output=$names}
{html_radios values=$ids name='box' separator='' output=$names}
{html_radios values=$ids checked=$checked separator='' output=$names}
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_radios_output">smarty_function_html_radios_output</a>(mixed name, mixed value, mixed output, mixed selected, mixed extra, mixed separator, mixed labels, mixed label_ids, mixed escape)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_select_date">smarty_function_html_select_date</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {html_select_date} pluginType:     function
Name:     html_select_date
Purpose:  Prints the dropdowns for date selection.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_select_time">smarty_function_html_select_time</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {html_select_time} function pluginType:     function
Name:     html_select_time
Purpose:  Prints the dropdowns for time selection</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_table">smarty_function_html_table</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {html_table} function pluginType:     function
Name:     html_table
Date:     Feb 17, 2003
Purpose:  make an html table from an array of data
Params:


loop       - array to loop through
cols       - number of columns, comma separated list of column names
or array of column names
rows       - number of rows
table_attr - table attributes
th_attr    - table heading attributes (arrays are cycled)
tr_attr    - table row attributes (arrays are cycled)
td_attr    - table cell attributes (arrays are cycled)
trailpad   - value to pad trailing cells with
caption    - text for caption element
vdir       - vertical direction (default: "down", means top-to-bottom)
hdir       - horizontal direction (default: "right", means left-to-right)
inner      - inner loop (default "cols": print $loop line by line,
$loop will be printed column by column otherwise)


Examples:

{table loop=$data}
{table loop=$data cols=4 tr_attr='"bgcolor=red"'}
{table loop=$data cols="first,second,third" tr_attr=$colors}
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_html_table_cycle">smarty_function_html_table_cycle</a>(mixed name, mixed var, mixed no)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_mailto">smarty_function_mailto</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {mailto} function pluginType:     function
Name:     mailto
Date:     May 21, 2002
Purpose:  automate mailto address link creation, and optionally encode them.
Params:


address    - (required) - e-mail address
text       - (optional) - text to display, default is address
encode     - (optional) - can be one of:
* none : no encoding (default)
* javascript : encode with javascript
* javascript_charcode : encode with javascript charcode
* hex : encode with hexidecimal (no javascript)
cc         - (optional) - address(es) to carbon copy
bcc        - (optional) - address(es) to blind carbon copy
subject    - (optional) - e-mail subject
newsgroups - (optional) - newsgroup(s) to post to
followupto - (optional) - address(es) to follow up to
extra      - (optional) - extra tags for the href link


Examples:

{mailto address="me@domain.com"}
{mailto address="me@domain.com" encode="javascript"}
{mailto address="me@domain.com" encode="hex"}
{mailto address="me@domain.com" subject="Hello to you!"}
{mailto address="me@domain.com" cc="you@domain.com,they@domain.com"}
{mailto address="me@domain.com" extra='class="mailto"'}
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string|null</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_function_math">smarty_function_math</a>(array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Smarty {math} function pluginType:     function
Name:     math
Purpose:  handle math computations in template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_literal_compiler_param">smarty_literal_compiler_param</a>(array params, integer index, mixed default)</p><p class="description">evaluate compiler parameter</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_make_timestamp">smarty_make_timestamp</a>(DateTime|int|string string)</p><p class="description">Function: smarty_make_timestamp
Purpose:  used by other smarty functions to make a timestamp from a string.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_mb_from_unicode">smarty_mb_from_unicode</a>(integer|array unicode, string encoding)</p><p class="description">convert unicodes to the character of given encoding</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_mb_str_replace">smarty_mb_str_replace</a>(string search, string replace, string subject, int &$count, int count)</p><p class="description">Multibyte string replace</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_mb_to_unicode">smarty_mb_to_unicode</a>(string string, string encoding)</p><p class="description">convert characters to their decimal unicode equivalents</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_mb_wordwrap">smarty_mb_wordwrap</a>(string str, int width, string break, boolean cut)</p><p class="description">Wrap a string to a given number of characters</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifier_capitalize">smarty_modifier_capitalize</a>(string string, boolean uc_digits, boolean lc_rest)</p><p class="description">Smarty capitalize modifier pluginType:     modifier
Name:     capitalize
Purpose:  capitalize words in the string{$string|capitalize:true:true is the fastest option for MBString enabled systems }}</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifier_date_format">smarty_modifier_date_format</a>(string string, string format, string default_date, string formatter)</p><p class="description">Smarty date_format modifier pluginType:     modifier
Name:     date_format
Purpose:  format datestamps via strftime
Input:

string: input date string
format: strftime format for output

- default_date: default date if $string is empty</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifier_debug_print_var">smarty_modifier_debug_print_var</a>(array|object var, integer depth, integer length)</p><p class="description">Smarty debug_print_var modifier pluginType:     modifier
Name:     debug_print_var
Purpose:  formats variable contents for display in the console</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifier_escape">smarty_modifier_escape</a>(string string, string esc_type, string char_set, boolean double_encode)</p><p class="description">Smarty escape modifier pluginType:     modifier
Name:     escape
Purpose:  escape string for output</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifier_regex_replace">smarty_modifier_regex_replace</a>(string string, string|array search, string|array replace)</p><p class="description">Smarty regex_replace modifier pluginType:     modifier
Name:     regex_replace
Purpose:  regular expression search/replace</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifier_replace">smarty_modifier_replace</a>(string string, string search, string replace)</p><p class="description">Smarty replace modifier pluginType:     modifier
Name:     replace
Purpose:  simple search/replace</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifier_spacify">smarty_modifier_spacify</a>(string string, string spacify_char)</p><p class="description">Smarty spacify modifier pluginType:     modifier
Name:     spacify
Purpose:  add spaces between characters in a string</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifier_truncate">smarty_modifier_truncate</a>(string string, integer length, string etc, boolean break_words, boolean middle)</p><p class="description">Smarty truncate modifier pluginType:     modifier
Name:     truncate
Purpose:  Truncate a string to a certain length if necessary,
optionally splitting in the middle of a word, and
appending the $etc string or inserting $etc into the middle.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_cat">smarty_modifiercompiler_cat</a>(array params, mixed compiler)</p><p class="description">Smarty cat modifier pluginType:     modifier
Name:     cat
Date:     Feb 24, 2003
Purpose:  catenate a value to a variable
Input:    string to catenate
Example:  {$var|cat:"foo"}</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_count_characters">smarty_modifiercompiler_count_characters</a>(array params, mixed compiler)</p><p class="description">Smarty count_characters modifier pluginType:     modifier
Name:     count_characteres
Purpose:  count the number of characters in a text</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_count_paragraphs">smarty_modifiercompiler_count_paragraphs</a>(array params, mixed compiler)</p><p class="description">Smarty count_paragraphs modifier pluginType:     modifier
Name:     count_paragraphs
Purpose:  count the number of paragraphs in a text</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_count_sentences">smarty_modifiercompiler_count_sentences</a>(array params, mixed compiler)</p><p class="description">Smarty count_sentences modifier pluginType:     modifier
Name:     count_sentences
Purpose:  count the number of sentences in a text</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_count_words">smarty_modifiercompiler_count_words</a>(array params, mixed compiler)</p><p class="description">Smarty count_words modifier pluginType:     modifier
Name:     count_words
Purpose:  count the number of words in a text</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_default">smarty_modifiercompiler_default</a>(array params, mixed compiler)</p><p class="description">Smarty default modifier pluginType:     modifier
Name:     default
Purpose:  designate default value for empty variables</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_escape">smarty_modifiercompiler_escape</a>(array params, mixed compiler)</p><p class="description">Smarty escape modifier pluginType:     modifier
Name:     escape
Purpose:  escape string for output</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_from_charset">smarty_modifiercompiler_from_charset</a>(array params, mixed compiler)</p><p class="description">Smarty from_charset modifier pluginType:     modifier
Name:     from_charset
Purpose:  convert character encoding from $charset to internal encoding</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_indent">smarty_modifiercompiler_indent</a>(array params, mixed compiler)</p><p class="description">Smarty indent modifier pluginType:     modifier
Name:     indent
Purpose:  indent lines of text</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_lower">smarty_modifiercompiler_lower</a>(array params, mixed compiler)</p><p class="description">Smarty lower modifier pluginType:     modifier
Name:     lower
Purpose:  convert string to lowercase</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_noprint">smarty_modifiercompiler_noprint</a>(array params, mixed compiler)</p><p class="description">Smarty noprint modifier pluginType:     modifier
Name:     noprint
Purpose:  return an empty string</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_string_format">smarty_modifiercompiler_string_format</a>(array params, mixed compiler)</p><p class="description">Smarty string_format modifier pluginType:     modifier
Name:     string_format
Purpose:  format strings via sprintf</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_strip">smarty_modifiercompiler_strip</a>(array params, mixed compiler)</p><p class="description">Smarty strip modifier pluginType:     modifier
Name:     strip
Purpose:  Replace all repeated spaces, newlines, tabs
with a single space or supplied replacement string.
Example:  {$var|strip} {$var|strip:"&nbsp;"}
Date:     September 25th, 2002</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_strip_tags">smarty_modifiercompiler_strip_tags</a>(array params, mixed compiler)</p><p class="description">Smarty strip_tags modifier pluginType:     modifier
Name:     strip_tags
Purpose:  strip html tags from text</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_to_charset">smarty_modifiercompiler_to_charset</a>(array params, mixed compiler)</p><p class="description">Smarty to_charset modifier pluginType:     modifier
Name:     to_charset
Purpose:  convert character encoding from internal encoding to $charset</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_unescape">smarty_modifiercompiler_unescape</a>(array params, mixed compiler)</p><p class="description">Smarty unescape modifier pluginType:     modifier
Name:     unescape
Purpose:  unescape html entities</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_upper">smarty_modifiercompiler_upper</a>(array params, mixed compiler)</p><p class="description">Smarty upper modifier pluginType:     modifier
Name:     lower
Purpose:  convert string to uppercase</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_modifiercompiler_wordwrap">smarty_modifiercompiler_wordwrap</a>(array params, mixed compiler)</p><p class="description">Smarty wordwrap modifier pluginType:     modifier
Name:     wordwrap
Purpose:  wrap a string of text at a given length</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_outputfilter_trimwhitespace">smarty_outputfilter_trimwhitespace</a>(string source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> smarty)</p><p class="description">Smarty trimwhitespace outputfilter pluginTrim unnecessary whitespace from HTML markup.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_php_tag">smarty_php_tag</a>(array params, string content, object template, boolean &$repeat, mixed repeat)</p><p class="description">Smarty {php}{/php} block function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#smarty_variablefilter_htmlspecialchars">smarty_variablefilter_htmlspecialchars</a>(string source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> smarty)</p><p class="description">Smarty htmlspecialchars variablefilter plugin</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_13">yy_r1_13</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_14">yy_r1_14</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_15">yy_r1_15</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_16">yy_r1_16</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_17">yy_r1_17</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_18">yy_r1_18</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_19">yy_r1_19</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_20">yy_r1_20</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_21">yy_r1_21</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_22">yy_r1_22</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r1_23">yy_r1_23</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_10">yy_r2_10</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_11">yy_r2_11</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_12">yy_r2_12</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_13">yy_r2_13</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_14">yy_r2_14</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_15">yy_r2_15</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_16">yy_r2_16</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_17">yy_r2_17</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_18">yy_r2_18</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_19">yy_r2_19</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_20">yy_r2_20</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_22">yy_r2_22</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_24">yy_r2_24</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_26">yy_r2_26</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_27">yy_r2_27</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_28">yy_r2_28</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_29">yy_r2_29</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_30">yy_r2_30</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_31">yy_r2_31</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_32">yy_r2_32</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_33">yy_r2_33</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_34">yy_r2_34</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_35">yy_r2_35</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_36">yy_r2_36</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_37">yy_r2_37</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_38">yy_r2_38</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_39">yy_r2_39</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_40">yy_r2_40</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_41">yy_r2_41</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_42">yy_r2_42</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_43">yy_r2_43</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_47">yy_r2_47</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_48">yy_r2_48</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_49">yy_r2_49</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_5">yy_r2_5</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_50">yy_r2_50</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_51">yy_r2_51</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_52">yy_r2_52</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_53">yy_r2_53</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_54">yy_r2_54</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_55">yy_r2_55</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_57">yy_r2_57</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_59">yy_r2_59</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_6">yy_r2_6</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_60">yy_r2_60</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_61">yy_r2_61</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_62">yy_r2_62</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_63">yy_r2_63</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_64">yy_r2_64</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_65">yy_r2_65</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_66">yy_r2_66</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_67">yy_r2_67</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_68">yy_r2_68</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_69">yy_r2_69</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_7">yy_r2_7</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_70">yy_r2_70</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_71">yy_r2_71</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_72">yy_r2_72</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_73">yy_r2_73</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_74">yy_r2_74</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_75">yy_r2_75</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_76">yy_r2_76</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_8">yy_r2_8</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r2_9">yy_r2_9</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r3_4">yy_r3_4</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r3_5">yy_r3_5</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r3_6">yy_r3_6</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r3_7">yy_r3_7</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_10">yy_r4_10</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_11">yy_r4_11</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_12">yy_r4_12</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_13">yy_r4_13</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_17">yy_r4_17</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_4">yy_r4_4</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_5">yy_r4_5</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_6">yy_r4_6</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_7">yy_r4_7</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_8">yy_r4_8</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yy_r4_9">yy_r4_9</a>(mixed yy_subpatterns)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yylex2">yylex2</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yylex3">yylex3</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/package-functions.md#yylex4">yylex4</a>()</p></td>
</tr>
</table>

<h2 id="detail_function">Function Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.regex_replace.php#L41" target='_blank'>framework\libs\smarty\plugins\modifier.regex_replace.php at line 41</a>

<h3 id="_smarty_regex_replace_check()">_smarty_regex_replace_check</h3>
<span class='k'></span> <span class='nx'>string</span> _smarty_regex_replace_check (string search)

<div class="details">
<p></p>
<dl>
<dt>Parameters:</dt>
<dd>search - string(s) that should be replaced</dd>
<dt>Ignore.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/Smarty.class.php#L1100" target='_blank'>framework\libs\smarty\Smarty.class.php at line 1100</a>

<h3 id="smartyAutoload()">smartyAutoload</h3>
<span class='k'></span> <span class='nx'>void</span> smartyAutoload (mixed class)

<div class="details">
<p>Autoloader</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/block.textformat.php#L35" target='_blank'>framework\libs\smarty\plugins\block.textformat.php at line 35</a>

<h3 id="smarty_block_textformat()">smarty_block_textformat</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_block_textformat (array params, string content, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template, boolean &$repeat, mixed repeat)

<div class="details">
<p>Smarty {textformat}{/textformat} block plugin</p><p>Type:     block function<br>
Name:     textformat<br>
Purpose:  format text a certain way with preset styles
or custom wrap/indent settings<br>
Params:
<pre></p>
<ul>
<li>style         - string (email)</li>
<li>indent        - integer (0)</li>
<li>wrap          - integer (80)</li>
<li>wrap_char     - string ("\n")</li>
<li>indent_char   - string (" ")</li>
<li>wrap_boundary - boolean (true)</li>
</ul>
<p></pre></p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.textformat.php">{textformat} (Smarty online manual)</a></code></dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>content - contents of the block</dd>
<dd>template - template object</dd>
<dd>&$repeat - repeat flag</dd>
<dt>Returns:</dt>
<dd>content re-formatted</dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.counter.php#L22" target='_blank'>framework\libs\smarty\plugins\function.counter.php at line 22</a>

<h3 id="smarty_function_counter()">smarty_function_counter</h3>
<span class='k'></span> <span class='nx'>string|null</span> smarty_function_counter (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {counter} function plugin</p><p>Type:     function<br>
Name:     counter<br>
Purpose:  print out a counter value</p>
<dl>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.counter.php">{counter} (Smarty online manual)</a></code></dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.cycle.php#L46" target='_blank'>framework\libs\smarty\plugins\function.cycle.php at line 46</a>

<h3 id="smarty_function_cycle()">smarty_function_cycle</h3>
<span class='k'></span> <span class='nx'>string|null</span> smarty_function_cycle (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {cycle} function plugin</p><p>Type:     function<br>
Name:     cycle<br>
Date:     May 3, 2002<br>
Purpose:  cycle through given values<br>
Params:
<pre></p>
<ul>
<li>name      - name of cycle (optional)</li>
<li>values    - comma separated list of values to cycle, or an array of values to cycle
(this can be left out for subsequent calls)</li>
<li>reset     - boolean - resets given var to true</li>
<li>print     - boolean - print var or not. default is true</li>
<li>advance   - boolean - whether or not to advance the cycle</li>
<li>delimiter - the value delimiter, default is ","</li>
<li>assign    - boolean, assigns to template var instead of printed.</li>
</ul>
<p></pre>
Examples:<br>
<pre>
{cycle values="#eeeeee,#d0d0d0d"}
{cycle name=row values="one,two,three" reset=true}
{cycle name=row}
</pre></p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.cycle.php">{cycle} (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>credit to Mark Priatel <mpriatel@rogers.com></dd>
<dd>credit to Gerard <gerard@interfold.com></dd>
<dd>credit to Jason Sweat <jsweat_php@yahoo.com></dd>
<dt>Version:</dt>
<dd>1.3</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/shared.escape_special_chars.php#L40" target='_blank'>framework\libs\smarty\plugins\shared.escape_special_chars.php at line 40</a>

<h3 id="smarty_function_escape_special_chars()">smarty_function_escape_special_chars</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_escape_special_chars (string string)

<div class="details">
<p>escape_special_chars common function</p><p>Function: smarty_function_escape_special_chars<br>
Purpose:  used by other smarty functions to escape
special chars except for already escaped ones</p>
<dl>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>string - text that should by escaped</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.fetch.php#L23" target='_blank'>framework\libs\smarty\plugins\function.fetch.php at line 23</a>

<h3 id="smarty_function_fetch()">smarty_function_fetch</h3>
<span class='k'></span> <span class='nx'>string|null</span> smarty_function_fetch (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {fetch} plugin</p><p>Type:     function<br>
Name:     fetch<br>
Purpose:  fetch file, web or ftp data and display results</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.fetch.php">{fetch} (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
<dt>Returns:</dt>
<dd>if the assign parameter is passed, Smarty assigns the result to a template variable</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_checkboxes.php#L45" target='_blank'>framework\libs\smarty\plugins\function.html_checkboxes.php at line 45</a>

<h3 id="smarty_function_html_checkboxes()">smarty_function_html_checkboxes</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_html_checkboxes (array params, object template)

<div class="details">
<p>Smarty {html_checkboxes} function plugin</p><p>File:       function.html_checkboxes.php<br>
Type:       function<br>
Name:       html_checkboxes<br>
Date:       24.Feb.2003<br>
Purpose:    Prints out a list of checkbox input types<br>
Examples:
<pre>
{html_checkboxes values=$ids output=$names}
{html_checkboxes values=$ids name='box' separator='<br>' output=$names}
{html_checkboxes values=$ids checked=$checked separator='<br>' output=$names}
</pre>
Params:
<pre></p>
<ul>
<li>name       (optional) - string default "checkbox"</li>
<li>values     (required) - array</li>
<li>options    (optional) - associative array</li>
<li>checked    (optional) - array default not set</li>
<li>separator  (optional) - ie <br> or &nbsp;</li>
<li>output     (optional) - the output next to each checkbox</li>
<li>assign     (optional) - assign the output as an array to this variable</li>
<li>escape     (optional) - escape the content (not value), defaults to true</li>
</ul>
<p></pre></p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.html.checkboxes.php">{html_checkboxes} (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Christopher Kvarme <christopher.kvarme@flashjab.com></dd>
<dd>credits to Monte Ohrt <monte at ohrt dot com></dd>
<dt>Version:</dt>
<dd>1.0</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
<dt>Uses:</dt>
<dd>smarty_function_escape_special_chars()</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_checkboxes.php#L153" target='_blank'>framework\libs\smarty\plugins\function.html_checkboxes.php at line 153</a>

<h3 id="smarty_function_html_checkboxes_output()">smarty_function_html_checkboxes_output</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_function_html_checkboxes_output (mixed name, mixed value, mixed output, mixed selected, mixed extra, mixed separator, mixed labels, mixed label_ids, bool escape)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_image.php#L37" target='_blank'>framework\libs\smarty\plugins\function.html_image.php at line 37</a>

<h3 id="smarty_function_html_image()">smarty_function_html_image</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_html_image (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {html_image} function plugin</p><p>Type:     function<br>
Name:     html_image<br>
Date:     Feb 24, 2003<br>
Purpose:  format HTML tags for the image<br>
Examples: {html_image file="/images/masthead.gif"}<br>
Output:   <img src="/images/masthead.gif" width=400 height=23><br>
Params:
<pre></p>
<ul>
<li>file        - (required) - file (and path) of image</li>
<li>height      - (optional) - image height (default actual height)</li>
<li>width       - (optional) - image width (default actual width)</li>
<li>basedir     - (optional) - base directory for absolute paths, default is environment variable DOCUMENT_ROOT</li>
<li>path_prefix - prefix for path output (optional, default empty)</li>
</ul>
<p></pre></p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.html.image.php">{html_image} (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>credits to Duda <duda@big.hu></dd>
<dt>Version:</dt>
<dd>1.0</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
<dt>Uses:</dt>
<dd>smarty_function_escape_special_chars()</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_options.php#L36" target='_blank'>framework\libs\smarty\plugins\function.html_options.php at line 36</a>

<h3 id="smarty_function_html_options()">smarty_function_html_options</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_html_options (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {html_options} function plugin</p><p>Type:     function<br>
Name:     html_options<br>
Purpose:  Prints the list of <option> tags generated from
the passed parameters<br>
Params:
<pre></p>
<ul>
<li>name       (optional) - string default "select"</li>
<li>values     (required) - if no options supplied) - array</li>
<li>options    (required) - if no values supplied) - associative array</li>
<li>selected   (optional) - string default not set</li>
<li>output     (required) - if not options supplied) - array</li>
<li>id         (optional) - string default not set</li>
<li>class      (optional) - string default not set</li>
</ul>
<p></pre></p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.html.options.php">{html_image} (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>Ralf Strehle (minor optimization) <ralf dot strehle at yahoo dot de></dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
<dt>Uses:</dt>
<dd>smarty_function_escape_special_chars()</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_options.php#L164" target='_blank'>framework\libs\smarty\plugins\function.html_options.php at line 164</a>

<h3 id="smarty_function_html_options_optgroup()">smarty_function_html_options_optgroup</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_function_html_options_optgroup (mixed key, mixed values, mixed selected, mixed id, mixed class, mixed idx)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_options.php#L132" target='_blank'>framework\libs\smarty\plugins\function.html_options.php at line 132</a>

<h3 id="smarty_function_html_options_optoutput()">smarty_function_html_options_optoutput</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_function_html_options_optoutput (mixed key, mixed value, mixed selected, mixed id, mixed class, mixed idx)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_radios.php#L45" target='_blank'>framework\libs\smarty\plugins\function.html_radios.php at line 45</a>

<h3 id="smarty_function_html_radios()">smarty_function_html_radios</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_html_radios (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {html_radios} function plugin</p><p>File:       function.html_radios.php<br>
Type:       function<br>
Name:       html_radios<br>
Date:       24.Feb.2003<br>
Purpose:    Prints out a list of radio input types<br>
Params:
<pre></p>
<ul>
<li>name       (optional) - string default "radio"</li>
<li>values     (required) - array</li>
<li>options    (required) - associative array</li>
<li>checked    (optional) - array default not set</li>
<li>separator  (optional) - ie <br> or &nbsp;</li>
<li>output     (optional) - the output next to each radio button</li>
<li>assign     (optional) - assign the output as an array to this variable</li>
<li>escape     (optional) - escape the content (not value), defaults to true</li>
</ul>
<p></pre>
Examples:
<pre>
{html_radios values=$ids output=$names}
{html_radios values=$ids name='box' separator='<br>' output=$names}
{html_radios values=$ids checked=$checked separator='<br>' output=$names}
</pre></p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://smarty.php.net/manual/en/language.function.html.radios.php">{html_radios} (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Christopher Kvarme <christopher.kvarme@flashjab.com></dd>
<dd>credits to Monte Ohrt <monte at ohrt dot com></dd>
<dt>Version:</dt>
<dd>1.0</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
<dt>Uses:</dt>
<dd>smarty_function_escape_special_chars()</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_radios.php#L140" target='_blank'>framework\libs\smarty\plugins\function.html_radios.php at line 140</a>

<h3 id="smarty_function_html_radios_output()">smarty_function_html_radios_output</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_function_html_radios_output (mixed name, mixed value, mixed output, mixed selected, mixed extra, mixed separator, mixed labels, mixed label_ids, mixed escape)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_select_date.php#L54" target='_blank'>framework\libs\smarty\plugins\function.html_select_date.php at line 54</a>

<h3 id="smarty_function_html_select_date()">smarty_function_html_select_date</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_html_select_date (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {html_select_date} plugin</p><p>Type:     function<br>
Name:     html_select_date<br>
Purpose:  Prints the dropdowns for date selection.</p><p>ChangeLog:
<pre></p>
<ul>
<li>1.0 initial release</li>
<li>1.1 added support for +/- N syntax for begin
and end year values. (Monte)</li>
<li>1.2 added support for yyyy-mm-dd syntax for
time value. (Jan Rosier)</li>
<li>1.3 added support for choosing format for
month values (Gary Loescher)</li>
<li>1.3.1 added support for choosing format for
day values (Marcus Bointon)</li>
<li>1.3.2 support negative timestamps, force year
dropdown to include given date unless explicitly set (Monte)</li>
<li>1.3.4 fix behaviour of 0000-00-00 00:00:00 dates to match that
of 0000-00-00 dates (cybot, boots)</li>
<li>2.0 complete rewrite for performance,
added attributes month_names, *_id</li>
</ul>
<p></pre></p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.html.select.date.php">{html_select_date} (Smarty online manual)</a></code></dd>
<dt>Version:</dt>
<dd>2.0</dd>
<dt>Author:</dt>
<dd>Andrei Zmievski</dd>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>Rodney Rehm</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_select_time.php#L34" target='_blank'>framework\libs\smarty\plugins\function.html_select_time.php at line 34</a>

<h3 id="smarty_function_html_select_time()">smarty_function_html_select_time</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_html_select_time (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {html_select_time} function plugin</p><p>Type:     function<br>
Name:     html_select_time<br>
Purpose:  Prints the dropdowns for time selection</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.html.select.time.php">{html_select_time} (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Roberto Berto <roberto@berto.net></dd>
<dd>Monte Ohrt <monte AT ohrt DOT com></dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
<dt>Uses:</dt>
<dd>smarty_make_timestamp()</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_table.php#L50" target='_blank'>framework\libs\smarty\plugins\function.html_table.php at line 50</a>

<h3 id="smarty_function_html_table()">smarty_function_html_table</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_html_table (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {html_table} function plugin</p><p>Type:     function<br>
Name:     html_table<br>
Date:     Feb 17, 2003<br>
Purpose:  make an html table from an array of data<br>
Params:
<pre></p>
<ul>
<li>loop       - array to loop through</li>
<li>cols       - number of columns, comma separated list of column names
or array of column names</li>
<li>rows       - number of rows</li>
<li>table_attr - table attributes</li>
<li>th_attr    - table heading attributes (arrays are cycled)</li>
<li>tr_attr    - table row attributes (arrays are cycled)</li>
<li>td_attr    - table cell attributes (arrays are cycled)</li>
<li>trailpad   - value to pad trailing cells with</li>
<li>caption    - text for caption element</li>
<li>vdir       - vertical direction (default: "down", means top-to-bottom)</li>
<li>hdir       - horizontal direction (default: "right", means left-to-right)</li>
<li>inner      - inner loop (default "cols": print $loop line by line,
$loop will be printed column by column otherwise)</li>
</ul>
<p></pre>
Examples:
<pre>
{table loop=$data}
{table loop=$data cols=4 tr_attr='"bgcolor=red"'}
{table loop=$data cols="first,second,third" tr_attr=$colors}
</pre></p>
<dl>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>credit to Messju Mohr <messju at lammfellpuschen dot de></dd>
<dd>credit to boots <boots dot smarty at yahoo dot com></dd>
<dt>Version:</dt>
<dd>1.1</dd>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.html.table.php">{html_table} (Smarty online manual)</a></code></dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.html_table.php#L166" target='_blank'>framework\libs\smarty\plugins\function.html_table.php at line 166</a>

<h3 id="smarty_function_html_table_cycle()">smarty_function_html_table_cycle</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_function_html_table_cycle (mixed name, mixed var, mixed no)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.mailto.php#L51" target='_blank'>framework\libs\smarty\plugins\function.mailto.php at line 51</a>

<h3 id="smarty_function_mailto()">smarty_function_mailto</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_mailto (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {mailto} function plugin</p><p>Type:     function<br>
Name:     mailto<br>
Date:     May 21, 2002
Purpose:  automate mailto address link creation, and optionally encode them.<br>
Params:
<pre></p>
<ul>
<li>address    - (required) - e-mail address</li>
<li>text       - (optional) - text to display, default is address</li>
<li>encode     - (optional) - can be one of:
* none : no encoding (default)
* javascript : encode with javascript
* javascript_charcode : encode with javascript charcode
* hex : encode with hexidecimal (no javascript)</li>
<li>cc         - (optional) - address(es) to carbon copy</li>
<li>bcc        - (optional) - address(es) to blind carbon copy</li>
<li>subject    - (optional) - e-mail subject</li>
<li>newsgroups - (optional) - newsgroup(s) to post to</li>
<li>followupto - (optional) - address(es) to follow up to</li>
<li>extra      - (optional) - extra tags for the href link</li>
</ul>
<p></pre>
Examples:
<pre>
{mailto address="me@domain.com"}
{mailto address="me@domain.com" encode="javascript"}
{mailto address="me@domain.com" encode="hex"}
{mailto address="me@domain.com" subject="Hello to you!"}
{mailto address="me@domain.com" cc="you@domain.com,they@domain.com"}
{mailto address="me@domain.com" extra='class="mailto"'}
</pre></p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.mailto.php">{mailto} (Smarty online manual)</a></code></dd>
<dt>Version:</dt>
<dd>1.2</dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>credits to Jason Sweat (added cc, bcc and subject functionality)</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/function.math.php#L24" target='_blank'>framework\libs\smarty\plugins\function.math.php at line 24</a>

<h3 id="smarty_function_math()">smarty_function_math</h3>
<span class='k'></span> <span class='nx'>string|null</span> smarty_function_math (array params, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Smarty {math} function plugin</p><p>Type:     function<br>
Name:     math<br>
Purpose:  handle math computations in template</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.function.math.php">{math} (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dd>template - template object</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/shared.literal_compiler_param.php#L19" target='_blank'>framework\libs\smarty\plugins\shared.literal_compiler_param.php at line 19</a>

<h3 id="smarty_literal_compiler_param()">smarty_literal_compiler_param</h3>
<span class='k'></span> <span class='nx'>mixed</span> smarty_literal_compiler_param (array params, integer index, mixed default)

<div class="details">
<p>evaluate compiler parameter</p>
<dl>
<dt>Parameters:</dt>
<dd>params - parameter array as given to the compiler function</dd>
<dd>index - array index of the parameter to convert</dd>
<dd>default - value to be returned if the parameter is not present</dd>
<dt>Returns:</dt>
<dd>evaluated value of parameter or $default</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if parameter is not a literal (but an expression, variable, …)</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/shared.make_timestamp.php#L17" target='_blank'>framework\libs\smarty\plugins\shared.make_timestamp.php at line 17</a>

<h3 id="smarty_make_timestamp()">smarty_make_timestamp</h3>
<span class='k'></span> <span class='nx'>int</span> smarty_make_timestamp (DateTime|int|string string)

<div class="details">
<p>Function: smarty_make_timestamp<br>
Purpose:  used by other smarty functions to make a timestamp from a string.</p>
<dl>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>string - date object, timestamp or string that can be converted using strtotime()</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/shared.mb_unicode.php#L36" target='_blank'>framework\libs\smarty\plugins\shared.mb_unicode.php at line 36</a>

<h3 id="smarty_mb_from_unicode()">smarty_mb_from_unicode</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_mb_from_unicode (integer|array unicode, string encoding)

<div class="details">
<p>convert unicodes to the character of given encoding</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.ibm.com/developerworks/library/os-php-unicode/index.html#listing3">for inspiration</a></code></dd>
<dt>Parameters:</dt>
<dd>unicode - single unicode or list of unicodes to convert</dd>
<dd>encoding - encoding of returned string, if null mb_internal_encoding() is used</dd>
<dt>Returns:</dt>
<dd>unicode as character sequence in given $encoding</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/shared.mb_str_replace.php#L20" target='_blank'>framework\libs\smarty\plugins\shared.mb_str_replace.php at line 20</a>

<h3 id="smarty_mb_str_replace()">smarty_mb_str_replace</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_mb_str_replace (string search, string replace, string subject, int &$count, int count)

<div class="details">
<p>Multibyte string replace</p>
<dl>
<dt>Parameters:</dt>
<dd>search - the string to be searched</dd>
<dd>replace - the replacement string</dd>
<dd>subject - the source string</dd>
<dd>&$count - number of matches found</dd>
<dt>Returns:</dt>
<dd>replaced string</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/shared.mb_unicode.php#L18" target='_blank'>framework\libs\smarty\plugins\shared.mb_unicode.php at line 18</a>

<h3 id="smarty_mb_to_unicode()">smarty_mb_to_unicode</h3>
<span class='k'></span> <span class='nx'>array</span> smarty_mb_to_unicode (string string, string encoding)

<div class="details">
<p>convert characters to their decimal unicode equivalents</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.ibm.com/developerworks/library/os-php-unicode/index.html#listing3">for inspiration</a></code></dd>
<dt>Parameters:</dt>
<dd>string - characters to calculate unicode of</dd>
<dd>encoding - encoding of $string, if null mb_internal_encoding() is used</dd>
<dt>Returns:</dt>
<dd>sequence of unicodes</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/shared.mb_wordwrap.php#L22" target='_blank'>framework\libs\smarty\plugins\shared.mb_wordwrap.php at line 22</a>

<h3 id="smarty_mb_wordwrap()">smarty_mb_wordwrap</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_mb_wordwrap (string str, int width, string break, boolean cut)

<div class="details">
<p>Wrap a string to a given number of characters</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://php.net/manual/en/function.wordwrap.php">for similarity</a></code></dd>
<dt>Parameters:</dt>
<dd>str - the string to wrap</dd>
<dd>width - the width of the output</dd>
<dd>break - the character used to break the line</dd>
<dd>cut - ignored parameter, just for the sake of</dd>
<dt>Returns:</dt>
<dd>wrapped string</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.capitalize.php#L25" target='_blank'>framework\libs\smarty\plugins\modifier.capitalize.php at line 25</a>

<h3 id="smarty_modifier_capitalize()">smarty_modifier_capitalize</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_capitalize (string string, boolean uc_digits, boolean lc_rest)

<div class="details">
<p>Smarty capitalize modifier plugin</p><p>Type:     modifier<br>
Name:     capitalize<br>
Purpose:  capitalize words in the string</p><p>{$string|capitalize:true:true is the fastest option for MBString enabled systems }}</p>
<dl>
<dt>Parameters:</dt>
<dd>string - string to capitalize</dd>
<dd>uc_digits - also capitalize "x123" to "X123"</dd>
<dd>lc_rest - capitalize first letters, lowercase all following letters "aAa" to "Aaa"</dd>
<dt>Returns:</dt>
<dd>capitalized string</dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>Rodney Rehm</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.date_format.php#L29" target='_blank'>framework\libs\smarty\plugins\modifier.date_format.php at line 29</a>

<h3 id="smarty_modifier_date_format()">smarty_modifier_date_format</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_date_format (string string, string format, string default_date, string formatter)

<div class="details">
<p>Smarty date_format modifier plugin</p><p>Type:     modifier<br>
Name:     date_format<br>
Purpose:  format datestamps via strftime<br>
Input:<br></p>
<ul>
<li>string: input date string</li>
<li>format: strftime format for output</li>
</ul>
<p>- default_date: default date if $string is empty</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.date.format.php">date_format (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>string - input date string</dd>
<dd>format - strftime format for output</dd>
<dd>default_date - default date if $string is empty</dd>
<dd>formatter - either 'strftime' or 'auto'</dd>
<dt>Returns:</dt>
<dd>|void</dd>
<dt>Uses:</dt>
<dd>smarty_make_timestamp()</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.debug_print_var.php#L22" target='_blank'>framework\libs\smarty\plugins\modifier.debug_print_var.php at line 22</a>

<h3 id="smarty_modifier_debug_print_var()">smarty_modifier_debug_print_var</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_debug_print_var (array|object var, integer depth, integer length)

<div class="details">
<p>Smarty debug_print_var modifier plugin</p><p>Type:     modifier<br>
Name:     debug_print_var<br>
Purpose:  formats variable contents for display in the console</p>
<dl>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>var - variable to be formatted</dd>
<dd>depth - maximum recursion depth if $var is an array</dd>
<dd>length - maximum string length if $var is a string</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.escape.php#L24" target='_blank'>framework\libs\smarty\plugins\modifier.escape.php at line 24</a>

<h3 id="smarty_modifier_escape()">smarty_modifier_escape</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_escape (string string, string esc_type, string char_set, boolean double_encode)

<div class="details">
<p>Smarty escape modifier plugin</p><p>Type:     modifier<br>
Name:     escape<br>
Purpose:  escape string for output</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.count.characters.php">count_characters (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>string - input string</dd>
<dd>esc_type - escape type</dd>
<dd>char_set - character set, used for htmlspecialchars() or htmlentities()</dd>
<dd>double_encode - encode already encoded entitites again, used for htmlspecialchars() or htmlentities()</dd>
<dt>Returns:</dt>
<dd>escaped input string</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.regex_replace.php#L24" target='_blank'>framework\libs\smarty\plugins\modifier.regex_replace.php at line 24</a>

<h3 id="smarty_modifier_regex_replace()">smarty_modifier_regex_replace</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_regex_replace (string string, string|array search, string|array replace)

<div class="details">
<p>Smarty regex_replace modifier plugin</p><p>Type:     modifier<br>
Name:     regex_replace<br>
Purpose:  regular expression search/replace</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://smarty.php.net/manual/en/language.modifier.regex.replace.php">regex_replace (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>string - input string</dd>
<dd>search - regular expression(s) to search for</dd>
<dd>replace - string(s) that should be replaced</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.replace.php#L23" target='_blank'>framework\libs\smarty\plugins\modifier.replace.php at line 23</a>

<h3 id="smarty_modifier_replace()">smarty_modifier_replace</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_replace (string string, string search, string replace)

<div class="details">
<p>Smarty replace modifier plugin</p><p>Type:     modifier<br>
Name:     replace<br>
Purpose:  simple search/replace</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://smarty.php.net/manual/en/language.modifier.replace.php">replace (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>string - input string</dd>
<dd>search - text to search for</dd>
<dd>replace - replacement text</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.spacify.php#L21" target='_blank'>framework\libs\smarty\plugins\modifier.spacify.php at line 21</a>

<h3 id="smarty_modifier_spacify()">smarty_modifier_spacify</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_spacify (string string, string spacify_char)

<div class="details">
<p>Smarty spacify modifier plugin</p><p>Type:     modifier<br>
Name:     spacify<br>
Purpose:  add spaces between characters in a string</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://smarty.php.net/manual/en/language.modifier.spacify.php">spacify (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>string - input string</dd>
<dd>spacify_char - string to insert between characters.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifier.truncate.php#L27" target='_blank'>framework\libs\smarty\plugins\modifier.truncate.php at line 27</a>

<h3 id="smarty_modifier_truncate()">smarty_modifier_truncate</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_truncate (string string, integer length, string etc, boolean break_words, boolean middle)

<div class="details">
<p>Smarty truncate modifier plugin</p><p>Type:     modifier<br>
Name:     truncate<br>
Purpose:  Truncate a string to a certain length if necessary,
optionally splitting in the middle of a word, and
appending the $etc string or inserting $etc into the middle.</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://smarty.php.net/manual/en/language.modifier.truncate.php">truncate (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dt>Parameters:</dt>
<dd>string - input string</dd>
<dd>length - length of truncated text</dd>
<dd>etc - end string</dd>
<dd>break_words - truncate at word boundary</dd>
<dd>middle - truncate in the middle of text</dd>
<dt>Returns:</dt>
<dd>truncated string</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.cat.php#L25" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.cat.php at line 25</a>

<h3 id="smarty_modifiercompiler_cat()">smarty_modifiercompiler_cat</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_cat (array params, mixed compiler)

<div class="details">
<p>Smarty cat modifier plugin</p><p>Type:     modifier<br>
Name:     cat<br>
Date:     Feb 24, 2003<br>
Purpose:  catenate a value to a variable<br>
Input:    string to catenate<br>
Example:  {$var|cat:"foo"}</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://smarty.php.net/manual/en/language.modifier.cat.php">cat (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.count_characters.php#L21" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.count_characters.php at line 21</a>

<h3 id="smarty_modifiercompiler_count_characters()">smarty_modifiercompiler_count_characters</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_count_characters (array params, mixed compiler)

<div class="details">
<p>Smarty count_characters modifier plugin</p><p>Type:     modifier<br>
Name:     count_characteres<br>
Purpose:  count the number of characters in a text</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.count.characters.php">count_characters (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.count_paragraphs.php#L22" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.count_paragraphs.php at line 22</a>

<h3 id="smarty_modifiercompiler_count_paragraphs()">smarty_modifiercompiler_count_paragraphs</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_count_paragraphs (array params, mixed compiler)

<div class="details">
<p>Smarty count_paragraphs modifier plugin</p><p>Type:     modifier<br>
Name:     count_paragraphs<br>
Purpose:  count the number of paragraphs in a text</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.count.paragraphs.php">count_paragraphs (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.count_sentences.php#L22" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.count_sentences.php at line 22</a>

<h3 id="smarty_modifiercompiler_count_sentences()">smarty_modifiercompiler_count_sentences</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_count_sentences (array params, mixed compiler)

<div class="details">
<p>Smarty count_sentences modifier plugin</p><p>Type:     modifier<br>
Name:     count_sentences
Purpose:  count the number of sentences in a text</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.count.paragraphs.php">count_sentences (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.count_words.php#L21" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.count_words.php at line 21</a>

<h3 id="smarty_modifiercompiler_count_words()">smarty_modifiercompiler_count_words</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_count_words (array params, mixed compiler)

<div class="details">
<p>Smarty count_words modifier plugin</p><p>Type:     modifier<br>
Name:     count_words<br>
Purpose:  count the number of words in a text</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.count.words.php">count_words (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.default.php#L21" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.default.php at line 21</a>

<h3 id="smarty_modifiercompiler_default()">smarty_modifiercompiler_default</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_default (array params, mixed compiler)

<div class="details">
<p>Smarty default modifier plugin</p><p>Type:     modifier<br>
Name:     default<br>
Purpose:  designate default value for empty variables</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.default.php">default (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.escape.php#L26" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.escape.php at line 26</a>

<h3 id="smarty_modifiercompiler_escape()">smarty_modifiercompiler_escape</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_escape (array params, mixed compiler)

<div class="details">
<p>Smarty escape modifier plugin</p><p>Type:     modifier<br>
Name:     escape<br>
Purpose:  escape string for output</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/docsv2/en/language.modifier.escape">count_characters (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.from_charset.php#L20" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.from_charset.php at line 20</a>

<h3 id="smarty_modifiercompiler_from_charset()">smarty_modifiercompiler_from_charset</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_from_charset (array params, mixed compiler)

<div class="details">
<p>Smarty from_charset modifier plugin</p><p>Type:     modifier<br>
Name:     from_charset<br>
Purpose:  convert character encoding from $charset to internal encoding</p>
<dl>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.indent.php#L21" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.indent.php at line 21</a>

<h3 id="smarty_modifiercompiler_indent()">smarty_modifiercompiler_indent</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_indent (array params, mixed compiler)

<div class="details">
<p>Smarty indent modifier plugin</p><p>Type:     modifier<br>
Name:     indent<br>
Purpose:  indent lines of text</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.indent.php">indent (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.lower.php#L22" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.lower.php at line 22</a>

<h3 id="smarty_modifiercompiler_lower()">smarty_modifiercompiler_lower</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_lower (array params, mixed compiler)

<div class="details">
<p>Smarty lower modifier plugin</p><p>Type:     modifier<br>
Name:     lower<br>
Purpose:  convert string to lowercase</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.lower.php">lower (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Monte Ohrt <monte at ohrt dot com></dd>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.noprint.php#L20" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.noprint.php at line 20</a>

<h3 id="smarty_modifiercompiler_noprint()">smarty_modifiercompiler_noprint</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_noprint (array params, mixed compiler)

<div class="details">
<p>Smarty noprint modifier plugin</p><p>Type:     modifier<br>
Name:     noprint<br>
Purpose:  return an empty string</p>
<dl>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.string_format.php#L21" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.string_format.php at line 21</a>

<h3 id="smarty_modifiercompiler_string_format()">smarty_modifiercompiler_string_format</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_string_format (array params, mixed compiler)

<div class="details">
<p>Smarty string_format modifier plugin</p><p>Type:     modifier<br>
Name:     string_format<br>
Purpose:  format strings via sprintf</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.string.format.php">string_format (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.strip.php#L25" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.strip.php at line 25</a>

<h3 id="smarty_modifiercompiler_strip()">smarty_modifiercompiler_strip</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_strip (array params, mixed compiler)

<div class="details">
<p>Smarty strip modifier plugin</p><p>Type:     modifier<br>
Name:     strip<br>
Purpose:  Replace all repeated spaces, newlines, tabs
with a single space or supplied replacement string.<br>
Example:  {$var|strip} {$var|strip:"&nbsp;"}<br>
Date:     September 25th, 2002</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.strip.php">strip (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.strip_tags.php#L21" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.strip_tags.php at line 21</a>

<h3 id="smarty_modifiercompiler_strip_tags()">smarty_modifiercompiler_strip_tags</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_strip_tags (array params, mixed compiler)

<div class="details">
<p>Smarty strip_tags modifier plugin</p><p>Type:     modifier<br>
Name:     strip_tags<br>
Purpose:  strip html tags from text</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://www.smarty.net/manual/en/language.modifier.strip.tags.php">strip_tags (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.to_charset.php#L20" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.to_charset.php at line 20</a>

<h3 id="smarty_modifiercompiler_to_charset()">smarty_modifiercompiler_to_charset</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_to_charset (array params, mixed compiler)

<div class="details">
<p>Smarty to_charset modifier plugin</p><p>Type:     modifier<br>
Name:     to_charset<br>
Purpose:  convert character encoding from internal encoding to $charset</p>
<dl>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.unescape.php#L20" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.unescape.php at line 20</a>

<h3 id="smarty_modifiercompiler_unescape()">smarty_modifiercompiler_unescape</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_unescape (array params, mixed compiler)

<div class="details">
<p>Smarty unescape modifier plugin</p><p>Type:     modifier<br>
Name:     unescape<br>
Purpose:  unescape html entities</p>
<dl>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.upper.php#L21" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.upper.php at line 21</a>

<h3 id="smarty_modifiercompiler_upper()">smarty_modifiercompiler_upper</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_upper (array params, mixed compiler)

<div class="details">
<p>Smarty upper modifier plugin</p><p>Type:     modifier<br>
Name:     lower<br>
Purpose:  convert string to uppercase</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://smarty.php.net/manual/en/language.modifier.upper.php">lower (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/modifiercompiler.wordwrap.php#L21" target='_blank'>framework\libs\smarty\plugins\modifiercompiler.wordwrap.php at line 21</a>

<h3 id="smarty_modifiercompiler_wordwrap()">smarty_modifiercompiler_wordwrap</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifiercompiler_wordwrap (array params, mixed compiler)

<div class="details">
<p>Smarty wordwrap modifier plugin</p><p>Type:     modifier<br>
Name:     wordwrap<br>
Purpose:  wrap a string of text at a given length</p>
<dl>
<dt>See Also:</dt>
<dd><code><a href="http://smarty.php.net/manual/en/language.modifier.wordwrap.php">wordwrap (Smarty online manual)</a></code></dd>
<dt>Author:</dt>
<dd>Uwe Tews</dd>
<dt>Parameters:</dt>
<dd>params - parameters</dd>
<dt>Returns:</dt>
<dd>with compiled code</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/outputfilter.trimwhitespace.php#L20" target='_blank'>framework\libs\smarty\plugins\outputfilter.trimwhitespace.php at line 20</a>

<h3 id="smarty_outputfilter_trimwhitespace()">smarty_outputfilter_trimwhitespace</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_outputfilter_trimwhitespace (string source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> smarty)

<div class="details">
<p>Smarty trimwhitespace outputfilter plugin</p><p>Trim unnecessary whitespace from HTML markup.</p>
<dl>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Parameters:</dt>
<dd>source - input string</dd>
<dd>smarty - Smarty object</dd>
<dt>Returns:</dt>
<dd>filtered output</dd>
<dt>Todo:</dt>
<dd>substr_replace() is not overloaded by mbstring.func_overload - so this function might fail!</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/SmartyBC.class.php#L454" target='_blank'>framework\libs\smarty\SmartyBC.class.php at line 454</a>

<h3 id="smarty_php_tag()">smarty_php_tag</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_php_tag (array params, string content, object template, boolean &$repeat, mixed repeat)

<div class="details">
<p>Smarty {php}{/php} block function</p>
<dl>
<dt>Parameters:</dt>
<dd>params - parameter list</dd>
<dd>content - contents of the block</dd>
<dd>template - template object</dd>
<dd>&$repeat - repeat flag</dd>
<dt>Returns:</dt>
<dd>content re-formatted</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/plugins/variablefilter.htmlspecialchars.php#L16" target='_blank'>framework\libs\smarty\plugins\variablefilter.htmlspecialchars.php at line 16</a>

<h3 id="smarty_variablefilter_htmlspecialchars()">smarty_variablefilter_htmlspecialchars</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_variablefilter_htmlspecialchars (string source, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> smarty)

<div class="details">
<p>Smarty htmlspecialchars variablefilter plugin</p>
<dl>
<dt>Parameters:</dt>
<dd>source - input string</dd>
<dd>smarty - Smarty object</dd>
<dt>Returns:</dt>
<dd>filtered output</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L155" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 155</a>

<h3 id="yy_r1_13()">yy_r1_13</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_13 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L166" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 166</a>

<h3 id="yy_r1_14()">yy_r1_14</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_14 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L177" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 177</a>

<h3 id="yy_r1_15()">yy_r1_15</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_15 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L188" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 188</a>

<h3 id="yy_r1_16()">yy_r1_16</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_16 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L199" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 199</a>

<h3 id="yy_r1_17()">yy_r1_17</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_17 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L206" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 206</a>

<h3 id="yy_r1_18()">yy_r1_18</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_18 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L213" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 213</a>

<h3 id="yy_r1_19()">yy_r1_19</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_19 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L225" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 225</a>

<h3 id="yy_r1_20()">yy_r1_20</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_20 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L230" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 230</a>

<h3 id="yy_r1_21()">yy_r1_21</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_21 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L235" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 235</a>

<h3 id="yy_r1_22()">yy_r1_22</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_22 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L240" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 240</a>

<h3 id="yy_r1_23()">yy_r1_23</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r1_23 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L438" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 438</a>

<h3 id="yy_r2_10()">yy_r2_10</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_10 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L445" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 445</a>

<h3 id="yy_r2_11()">yy_r2_11</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_11 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L451" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 451</a>

<h3 id="yy_r2_12()">yy_r2_12</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_12 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L456" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 456</a>

<h3 id="yy_r2_13()">yy_r2_13</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_13 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L461" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 461</a>

<h3 id="yy_r2_14()">yy_r2_14</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_14 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L466" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 466</a>

<h3 id="yy_r2_15()">yy_r2_15</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_15 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L471" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 471</a>

<h3 id="yy_r2_16()">yy_r2_16</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_16 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L476" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 476</a>

<h3 id="yy_r2_17()">yy_r2_17</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_17 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L481" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 481</a>

<h3 id="yy_r2_18()">yy_r2_18</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_18 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L486" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 486</a>

<h3 id="yy_r2_19()">yy_r2_19</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_19 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L491" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 491</a>

<h3 id="yy_r2_20()">yy_r2_20</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_20 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L496" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 496</a>

<h3 id="yy_r2_22()">yy_r2_22</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_22 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L501" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 501</a>

<h3 id="yy_r2_24()">yy_r2_24</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_24 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L506" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 506</a>

<h3 id="yy_r2_26()">yy_r2_26</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_26 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L511" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 511</a>

<h3 id="yy_r2_27()">yy_r2_27</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_27 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L516" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 516</a>

<h3 id="yy_r2_28()">yy_r2_28</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_28 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L521" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 521</a>

<h3 id="yy_r2_29()">yy_r2_29</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_29 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L526" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 526</a>

<h3 id="yy_r2_30()">yy_r2_30</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_30 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L531" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 531</a>

<h3 id="yy_r2_31()">yy_r2_31</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_31 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L536" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 536</a>

<h3 id="yy_r2_32()">yy_r2_32</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_32 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L541" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 541</a>

<h3 id="yy_r2_33()">yy_r2_33</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_33 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L546" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 546</a>

<h3 id="yy_r2_34()">yy_r2_34</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_34 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L551" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 551</a>

<h3 id="yy_r2_35()">yy_r2_35</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_35 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L556" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 556</a>

<h3 id="yy_r2_36()">yy_r2_36</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_36 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L561" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 561</a>

<h3 id="yy_r2_37()">yy_r2_37</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_37 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L566" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 566</a>

<h3 id="yy_r2_38()">yy_r2_38</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_38 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L571" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 571</a>

<h3 id="yy_r2_39()">yy_r2_39</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_39 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L576" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 576</a>

<h3 id="yy_r2_40()">yy_r2_40</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_40 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L581" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 581</a>

<h3 id="yy_r2_41()">yy_r2_41</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_41 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L586" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 586</a>

<h3 id="yy_r2_42()">yy_r2_42</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_42 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L591" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 591</a>

<h3 id="yy_r2_43()">yy_r2_43</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_43 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L596" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 596</a>

<h3 id="yy_r2_47()">yy_r2_47</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_47 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L601" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 601</a>

<h3 id="yy_r2_48()">yy_r2_48</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_48 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L606" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 606</a>

<h3 id="yy_r2_49()">yy_r2_49</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_49 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L392" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 392</a>

<h3 id="yy_r2_5()">yy_r2_5</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_5 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L611" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 611</a>

<h3 id="yy_r2_50()">yy_r2_50</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_50 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L616" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 616</a>

<h3 id="yy_r2_51()">yy_r2_51</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_51 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L621" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 621</a>

<h3 id="yy_r2_52()">yy_r2_52</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_52 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L626" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 626</a>

<h3 id="yy_r2_53()">yy_r2_53</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_53 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L631" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 631</a>

<h3 id="yy_r2_54()">yy_r2_54</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_54 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L636" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 636</a>

<h3 id="yy_r2_55()">yy_r2_55</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_55 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L641" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 641</a>

<h3 id="yy_r2_57()">yy_r2_57</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_57 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L646" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 646</a>

<h3 id="yy_r2_59()">yy_r2_59</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_59 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L403" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 403</a>

<h3 id="yy_r2_6()">yy_r2_6</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_6 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L651" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 651</a>

<h3 id="yy_r2_60()">yy_r2_60</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_60 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L656" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 656</a>

<h3 id="yy_r2_61()">yy_r2_61</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_61 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L661" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 661</a>

<h3 id="yy_r2_62()">yy_r2_62</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_62 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L666" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 666</a>

<h3 id="yy_r2_63()">yy_r2_63</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_63 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L671" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 671</a>

<h3 id="yy_r2_64()">yy_r2_64</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_64 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L676" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 676</a>

<h3 id="yy_r2_65()">yy_r2_65</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_65 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L682" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 682</a>

<h3 id="yy_r2_66()">yy_r2_66</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_66 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L688" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 688</a>

<h3 id="yy_r2_67()">yy_r2_67</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_67 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L693" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 693</a>

<h3 id="yy_r2_68()">yy_r2_68</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_68 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L698" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 698</a>

<h3 id="yy_r2_69()">yy_r2_69</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_69 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L414" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 414</a>

<h3 id="yy_r2_7()">yy_r2_7</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_7 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L703" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 703</a>

<h3 id="yy_r2_70()">yy_r2_70</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_70 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L708" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 708</a>

<h3 id="yy_r2_71()">yy_r2_71</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_71 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L713" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 713</a>

<h3 id="yy_r2_72()">yy_r2_72</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_72 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L718" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 718</a>

<h3 id="yy_r2_73()">yy_r2_73</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_73 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L723" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 723</a>

<h3 id="yy_r2_74()">yy_r2_74</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_74 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L728" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 728</a>

<h3 id="yy_r2_75()">yy_r2_75</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_75 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L733" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 733</a>

<h3 id="yy_r2_76()">yy_r2_76</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_76 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L425" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 425</a>

<h3 id="yy_r2_8()">yy_r2_8</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_8 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L431" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 431</a>

<h3 id="yy_r2_9()">yy_r2_9</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r2_9 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L811" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 811</a>

<h3 id="yy_r3_4()">yy_r3_4</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r3_4 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L816" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 816</a>

<h3 id="yy_r3_5()">yy_r3_5</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r3_5 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L821" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 821</a>

<h3 id="yy_r3_6()">yy_r3_6</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r3_6 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L826" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 826</a>

<h3 id="yy_r3_7()">yy_r3_7</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r3_7 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L979" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 979</a>

<h3 id="yy_r4_10()">yy_r4_10</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_10 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L987" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 987</a>

<h3 id="yy_r4_11()">yy_r4_11</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_11 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L992" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 992</a>

<h3 id="yy_r4_12()">yy_r4_12</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_12 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L997" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 997</a>

<h3 id="yy_r4_13()">yy_r4_13</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_13 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L1002" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 1002</a>

<h3 id="yy_r4_17()">yy_r4_17</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_17 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L926" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 926</a>

<h3 id="yy_r4_4()">yy_r4_4</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_4 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L937" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 937</a>

<h3 id="yy_r4_5()">yy_r4_5</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_5 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L948" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 948</a>

<h3 id="yy_r4_6()">yy_r4_6</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_6 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L959" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 959</a>

<h3 id="yy_r4_7()">yy_r4_7</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_7 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L966" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 966</a>

<h3 id="yy_r4_8()">yy_r4_8</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_8 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L973" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 973</a>

<h3 id="yy_r4_9()">yy_r4_9</h3>
<span class='k'></span> <span class='nx'>void</span> yy_r4_9 (mixed yy_subpatterns)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L261" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 261</a>

<h3 id="yylex2()">yylex2</h3>
<span class='k'></span> <span class='nx'>void</span> yylex2 ()

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L741" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 741</a>

<h3 id="yylex3()">yylex3</h3>
<span class='k'></span> <span class='nx'>void</span> yylex3 ()

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L849" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 849</a>

<h3 id="yylex4()">yylex4</h3>
<span class='k'></span> <span class='nx'>void</span> yylex4 ()

<div class="details">
</div>

- - -

