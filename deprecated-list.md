- - -

#Deprecated API#

- - -

##Contents##


* <a href="#deprecated_class">Deprecated Classes</a>
* <a href="#deprecated_method">Deprecated Methods</a>
* <a href="#deprecated_global">Deprecated Globals</a>

<table id="deprecated_class" class="detail">
<tr><th colspan="2" class="title">Deprecated Classes</th></tr>
<tr><td class="name"><a href="http_session2/http_session2_container_db.md">HTTP_Session2\HTTP_Session2_Container_DB</a></td><td class="description">Database container for session dataCreate the following table to store session data

CREATE TABLE `sessiondata` (
`id` CHAR(32) NOT NULL,
`expiry` INT UNSIGNED NOT NULL DEFAULT 0,
`data` TEXT NOT NULL,
PRIMARY KEY (`id`)
);
</td></tr>
<tr><td class="name"><a href="smarty/smarty_internal_resource_registered.md">Smarty\Smarty_Internal_Resource_Registered</a></td><td class="description">Smarty Internal Plugin Resource RegisteredImplements the registered resource for Smarty template</td></tr>
</table>

<table id="deprecated_method" class="detail">
<tr><th colspan="2" class="title">Deprecated Methods</th></tr>
<tr>
<td class="name"><a href="hirudo/impl/joomla/joomlarequest.md">Hirudo\Impl\Joomla\JoomlaRequest\submitted</a></td>
<td class="description">Determines if there is any data in the $_POST array.</td>
</tr>
<tr>
<td class="name"><a href="hirudo/core/context/request.md">Hirudo\Core\Context\Request\submitted</a></td>
<td class="description">Determines if there is any data in the $_POST array.</td>
</tr>
<tr>
<td class="name"><a href="hirudo/impl/standalone/sarequest.md">Hirudo\Impl\StandAlone\SARequest\submitted</a></td>
<td class="description">Determines if there is any data in the $_POST array.</td>
</tr>
</table>

<table id="deprecated_global" class="detail">
<tr><th colspan="2" class="title">Deprecated Globals</th></tr>
<tr>
<td class="name"><a href="default namespace/package-globals.md">Default namespace\SMARTY_RESOURCE_CHAR_SET</a></td>
<td class="description"></td>
</tr>
<tr>
<td class="name"><a href="default namespace/package-globals.md">Default namespace\SMARTY_RESOURCE_DATE_FORMAT</a></td>
<td class="description"></td>
</tr>
</table>

