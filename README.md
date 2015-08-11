# Teleport Boilerplate Project

Use this project with `composer create-project` to start developing custom [Teleport](https://github.com/modxcms/teleport/) project to maintain your own [custom Actions](http://modxcms.github.io/teleport/extend/custom-actions/) or [Extract tpls](http://modxcms.github.io/teleport/extend/custom-extract-tpls/).

    php composer.phar create-project modxcms/teleport-project teleport-of-mine/

You can use `composer update` on the resulting project to stay up-to-date with the latest release of Teleport. You can also use `bin/compile` to create your own `teleport.phar` from your custom project. NOTE that all bin scripts from Teleport are copied to the local `bin/` and that the files and folders from Teleport's `tpl/` directory are symlinked in the local `tpl/` directory.
