# silence
Blank Page for Default Site Setup on New Servers

Used when creating new servers in Laravel Forge.

Forge creates a default site, that shows a PHP Info page by default.

This repo is used to replace that with a blank page, to prevent access to PHP information in the case someone requests the server directly or using a wildcard domain pointing to the server.
