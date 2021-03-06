[Bludit](https://www.bludit.com/)
================================
**Fast**, **simple**, **extensible** and **flat file** CMS.

Bludit is a simple web application to make your own **blog** or **site** in seconds, it's completely **free and open source**. Bludit uses flat-files to store the posts and pages, you don't need to install or configure a database. Bludit supports **Markdown** and HTML code for the content of the posts and pages.

- [Documentation](https://docs.bludit.com)
- [Help and Support](https://forum.bludit.com)
- [Plugins](https://plugins.bludit.com)
- [Themes](https://themes.bludit.com)
- [More plugins and themes](https://forum.bludit.com/viewforum.php?f=14)

Social networks
---------------

- [Twitter](https://twitter.com/bludit)
- [Facebook](https://www.facebook.com/bluditcms)
- [Google+](https://plus.google.com/+Bluditcms)
- [Freenode IRC](https://webchat.freenode.net) channel **#bludit**

[![Join the chat at https://gitter.im/dignajar/bludit](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dignajar/bludit?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Requirements
------------

You just need a web server with PHP support.

- PHP v5.3 or higher.
- PHP [mbstring](http://php.net/manual/en/book.mbstring.php) module for full UTF-8 support.
- PHP [gd](http://php.net/manual/en/book.image.php) module for image processing.
- PHP [dom](http://php.net/manual/en/book.dom.php) module for DOM manipulation.
- PHP [json](http://php.net/manual/en/book.json.php) module for JSON manipulation.
- Supported web servers:
  * PHP Built-in web server
  * Apache with module [mod_rewrite](http://httpd.apache.org/docs/current/mod/mod_rewrite.html)
  * Lighttpd with module [mod_rewrite](http://redmine.lighttpd.net/projects/1/wiki/docs_modrewrite)
  * Nginx with module [ngx_http_rewrite_module](http://nginx.org/en/docs/http/ngx_http_rewrite_module.html)
  * Other

Installation guide
------------------

1. Download the latest version from https://s3.amazonaws.com/bludit-s3/bludit-builds/bludit_latest.zip
2. Extract the zip file into a directory like `bludit`.
3. Upload the directory `bludit` to your hosting server.
4. Done!

License
-------
Bludit is open source software licensed under the [MIT license](https://tldrlegal.com/license/mit-license).
