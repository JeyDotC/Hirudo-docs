- - -

#Deprecated API#

- - -

##Contents##


* <a href="#deprecated_class">Deprecated Classes</a>
* <a href="#deprecated_method">Deprecated Methods</a>

<table id="deprecated_class" class="detail">
<tr><th colspan="2">Deprecated Classes</th></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container_DB.md">HTTP_Session2\HTTP_Session2_Container_DB</a></td><td class="description">Database container for session dataCreate the following table to store session data

CREATE TABLE `sessiondata` (
`id` CHAR(32) NOT NULL,
`expiry` INT UNSIGNED NOT NULL DEFAULT 0,
`data` TEXT NOT NULL,
PRIMARY KEY (`id`)
);
</td></tr>
</table>

<table id="deprecated_method" class="detail">
<tr><th colspan="2" class="title">Deprecated Methods</th></tr>
<tr>
<td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Drupal/DrupalRequest.md#submitted">Hirudo\Impl\Drupal\DrupalRequest\submitted</a></td>
<td class="description">Determines if there is any data in the $_POST array.</td>
</tr>
<tr>
<td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Joomla/V15/JoomlaRequest.md#submitted">Hirudo\Impl\Joomla\V15\JoomlaRequest\submitted</a></td>
<td class="description">Determines if there is any data in the $_POST array.</td>
</tr>
<tr>
<td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Joomla/V30/JoomlaRequest.md#submitted">Hirudo\Impl\Joomla\V30\JoomlaRequest\submitted</a></td>
<td class="description">Determines if there is any data in the $_POST array.</td>
</tr>
<tr>
<td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Request.md#submitted">Hirudo\Core\Context\Request\submitted</a></td>
<td class="description">Determines if there is any data in the $_POST array.</td>
</tr>
<tr>
<td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/StandAlone/SARequest.md#submitted">Hirudo\Impl\StandAlone\SARequest\submitted</a></td>
<td class="description">Determines if there is any data in the $_POST array.</td>
</tr>
</table>

