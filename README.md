# openam-scope-sample

## Warning
**This code is not supported by ForgeRock and it is your responsibility to verify that the software is suitable and safe for use.**

## About

*An OpenAM Sample OAuth 2.0 Scope Validator Plugin*

For instructions on using this sample OAuth 2.0 scope validator plugin
with OpenAM see the chapter,
*[Customizing OAuth 2.0 Scope Handling](http://openam.forgerock.org/openam-documentation/openam-doc-source/doc/dev-guide/index/chap-oauth2-scopes.html)*,
in the OpenAM *Developer's Guide*.

Before building the sample scope validator plugin,
update the OpenAM version in the POM
to match the version of OpenAM that you are using.

The line to update is:

    <openam.version>12.0.0-SNAPSHOT</openam.version>

For versions earlier than 12.0.0-SNAPSHOT,
use the `DeprecatedCustomScope` plugin with OpenAM instead.

* * *

This work is licensed under the Creative Commons
Attribution-NonCommercial-NoDerivs 3.0 Unported License.
To view a copy of this license, visit
<http://creativecommons.org/licenses/by-nc-nd/3.0/>
or send a letter to Creative Commons, 444 Castro Street,
Suite 900, Mountain View, California, 94041, USA.

Copyright 2013-2014 ForgeRock AS
