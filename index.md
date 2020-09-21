---
layout: default
title: FastCGI.com Archives
description: This is the Github FastCGI Archives of FastCGI.com site.
meta: fastcgi, cgi, protocol
---


# About FastCGI original official site

Since fastcgi.com is not available anymore (last backup on wayback machine are at [20/03/2016](http://web.archive.org/web/20160320065247/http://www.fastcgi.com/drupal/)), I ([mcarbonneaux](https://github.com/mcarbonneaux)) created this repository and linked website [fastcgi-archives.github.io](https://fastcgi-archives.github.io/) to host the FastCGI information backup.

## Contents of this site

This repository contains the backup of the original site :

  * The original version from fastcgi.com, pulled from the Wayback Machine archive with the last wayback backup at [20/03/2016](http://web.archive.org/web/20160320065247/http://www.fastcgi.com/drupal/), to [FastCGI-Archives/FastCGI.com](https://github.com/FastCGI-Archives/FastCGI.com/tree/master/docs) github project.

  * A markdown version, manually converted from the original, at [FastCGI-Archives/fastcgi-archives.github.io](https://github.com/FastCGI-Archives/fastcgi-archives.github.io).

This repository also contains the backup the original site source code :
  * In [FastCGI-Archives/FastCGI.com github project](https://github.com/FastCGI-Archives/FastCGI.com/tree/master/original_snapshot) are the original last snapshot pulled from the Wayback Machine archive of the source of the fcgi sdk and mod_fastcgi apache module.

  * In [FastCGI-Archives/fcgi2 github project](https://github.com/FastCGI-Archives/fcgi2) the source fork of the fcgi sdk.
  * In [FastCGI-Archives/mod_fastcgi github project](https://github.com/FastCGI-Archives/mod_fastcgi) the source fork of the apache mod_fastcgi module.


## FastCGI Specification copyright

This is not an official repository nor is it linked in any way to the original fastcgi.com website and FastCGI copyright owners.

The FastCGI Specification is intellectual property of Open Market Inc.
Copyright © 1996 Open Market, Inc. 245 First Street, Cambridge, MA 02142 U.S.A.
Tel: 617-621-9500 Fax: 617-621-1703 URL: http://www.openmarket.com/

# Original maintainers and autor at FastCGI.com

Based on last backup on wayback machine at [13/03/2016](https://web.archive.org/web/20160313121910/http://fastcgi.com/drupal/node/8):
- Original designer and developer: [Mark R. Brown (when at OpenMarket)](https://www.linkedin.com/in/mark-brown-32a01b11/)
- Last Maintainer: [Rob Saccoccio (when at Infinite Technology Inc.)](https://www.linkedin.com/in/rob-saccoccio-792ba3b/)
- Website Editor: [Daniel Lo](https://www.linkedin.com/in/lodaniel/)
- PERL ISS Windows binaries.: [Lyle Hopkins](https://www.linkedin.com/in/hopkinslyle/)
- Wrote and maintains the indispensable FCGI module for Perl : [Sven Verdoolaege](https://www.linkedin.com/in/skimo/)
- Cheer leading, testing, and system administration advice and support : David Birnbaum

# About FastCGI protocol

### FastCGI is simple because it is actually CGI with only a few extensions.

* Like CGI, FastCGI is also language-independent. For instance, FastCGI provides a way to improve the performance of the thousands of Perl applications that have been written for the Web.

* Like CGI, FastCGI runs applications in processes isolated from the core Web server, which provides greater security than APIs. (APIs link application code into the core Web server, which means that a bug in one API-based application can corrupt another application or the core server; a malicious API-based application can, for example, steal key security secrets from another application or the core server.)

* Although FastCGI cannot duplicate the universality of CGI overnight, the FastCGI developers are committed to propagating FastCGI as an open standard. To that end, free FastCGI application libraries (C/C++, Java, Perl, Tcl) and upgrade modules for popular free servers (Apache, ISS, Lighttpd) are available.

* Like CGI, FastCGI is not tied to the internal architecture of any Web server and is therefore stable even when server technology changes. An API reflects the internal architecture of a Web server, so when that architecture changes, so does the API.

### Not only does FastCGI restore the strengths of CGI, it also adds two new benefits:

* Distributed computing: Companies can run their FastCGI application on a different machine from the one on which they run their Web server. Distributed computing is a proven technique for scaling, linking to existing corporate systems, improving system availability, and improving security via compartmentalization, such as firewalls.

* Multiple and extensible roles: CGI applications compute the response to an HTTP request. FastCGI applications can do that and more, such as perform modular authentication and authorization checks and translate data from one type to another. FastCGI is designed so that more roles can be introduced in the future.

### Development on FastCGI:

There is not much development on FastCGI because it is a very stable protocol / application.

But, yes, we are here...

## [FastCGI Licence](LICENCE.md)

## [New FAQ](FAQ_Newer_FastCGI.md)

## [FAQ](FastCGI_FAQ.md)
Frequently asked questions, examples and explanations.

## [FastCGI White Paper](FastCGI_A_High-Performance_Web_Server_Interface_FastCGI.md)
Describes the motivation for FastCGI, the FastCGI interface, FastCGI application roles, the FastCGI application library, and FastCGI performance.

## [Understanding FastCGI Application Performance](Understanding_FastCGI_Application_Performance_FastCGI.md)
Why FastCGI applications often run faster than applications coded directly to Web server APIs.

## [FastCGI Developer' Kit](FastCGI_Developers_Kit_FastCGI.md)
How to configure and build the kit, and write applications using the FastCGI application libraries.

## [FastCGI Programmer' Guide](https://htmlpreview.github.io/?https://github.com/FastCGI-Archives/fcgi2/blob/master/doc/fastcgi-prog-guide/cover.htm)
Programmer-oriented documentation for developers of FastCGI applications. The content overlaps considerably with the Developer's Kit document.

## [FastCGI Specification](FastCGI_Specification.md)
Defines the interface between a FastCGI application and the Web server.

## [FastCGI - A High-Performance Gateway Interface](FastCGI_A_High-Performance_Gateway_Interface_FastCGI.md)
Position paper presented at the workshop "Programming the Web -- a search for APIs", Fifth International World Wide Web Conference, 6 May 1996, Paris, France.

## Rob's Open Source '99 Presentations
Two FastCGI related presentations given at O'reilly's Open Source '99 Conference in Monterey, CA.

**From the Perl Conference (Applying Perl track):**

Scaling CGI with Perl  | [PDF](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/docs/FastCGI-Perl.pdf) |  [PowerPoint](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/docs/FastCGI-Perl.ppt)

**From the Apache Conference:**

The Apache FastCGI Implementation  | [PDF](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/docs/FastCGI.pdf) |  [PowerPoint](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/docs/FastCGI.ppt)

## [The Apache FastCGI Process Manager](The_Apache_FastCGI_Process_Manager_FastCGI.md)
A description of some of the functionality of the process manager in mod_fastcgi. I'm not sure how accurate it is.

# <a name="ServerSupport">Servers that support FastCGI<a>
* Apache - [http://www.apache.org](http://www.apache.org)
  * Apache 2.4 native support :
     - [mod_proxy_fcgi](https://httpd.apache.org/docs/2.4/mod/mod_proxy_fcgi.html)
     - [mod_authnz_fcgi](https://httpd.apache.org/docs/2.4/mod/mod_authnz_fcgi.html)
  * Apache 2.x [Mod_fcgid](http://httpd.apache.org/mod_fcgid/)

  * Open Market mod_fastcgi free, open-source Apache httpd module.

       Current: [download](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/original_snapshot/mod_fastcgi-SNAP-0910052141.tar.gz) | [docs](mod_fastcgi.md) | git: [history](https://github.com/FastCGI-Archives/mod_fastcgi)

      * [Apache install instructions](Apache_Install_FastCGI.md)
      * [Apache FAQ](Apache_FAQ_FastCGI.md)

* Nginx - [http://nginx.org/en/docs/http/ngx_http_fastcgi_module.html](http://nginx.org/en/docs/http/ngx_http_fastcgi_module.html)
* Lighttpd :
  - FastCGI Module : [http://trac.lighttpd.net/trac/wiki/Docs%3AModFastCGI](http://trac.lighttpd.net/trac/wiki/Docs%3AModFastCGI)
  - FastCGI Usage : [https://redmine.lighttpd.net/projects/1/wiki/docs_modfastcgi](https://redmine.lighttpd.net/projects/1/wiki/docs_modfastcgi)
* Cherokee - [http://cherokee-project.com/doc/modules_handlers_fcgi.html](http://cherokee-project.com/doc/modules_handlers_fcgi.html)
* Microsoft IIS
   - [http://www.iis.net/fastcgi/configuration](http://www.iis.net/fastcgi/configuration)
   - (second generation) - [http://www.coastrd.com/fastcgi](http://www.coastrd.com/fastcgi) which supports SIGTERM and the Aprellium Abyss server as well
   - IIS >7 - [https://www.iis.net/configreference/system.webserver/fastcgi](https://www.iis.net/configreference/system.webserver/fastcgi)
* Resin :
   - Proxy Fastcgi to backend : [http://wiki4.caucho.com/Application_Server:_Native_PHP_With_FastCGIServlet](http://wiki4.caucho.com/Application_Server:_Native_PHP_With_FastCGIServlet)
   - Front End : [http://www.caucho.com/resin-4.0/changes/resin-4.0.0.xtp#fastcgisupport](http://www.caucho.com/resin-4.0/changes/resin-4.0.0.xtp#fastcgisupport)
* SunOne - [https://docs.oracle.com/cd/E19146-01/821-1828/6nmpm01ns/index.html](https://docs.oracle.com/cd/E19146-01/821-1828/6nmpm01ns/index.html)
* Premium thttpd [http://schumann.cx/premium-thttpd/](http://schumann.cx/premium-thttpd/)
* MyServer - [http://www.myserverproject.net/](http://www.myserverproject.net/)
* Pi3Web - [http://pi3web.sourceforge.net/](http://pi3web.sourceforge.net/)
* Jetty - [http://www.eclipse.org/jetty/documentation/current/fastcgi.html](http://www.eclipse.org/jetty/documentation/current/fastcgi.html)
* caddy web server [https://caddyserver.com/docs/fastcgi](https://caddyserver.com/docs/fastcgi)

## <a name="apilib">API/Libraries</a>

The FastCGI application libraries.

*   The Development Kit - **C**, **C++**, **Perl**, and **Java**, libraries as well as assorted documentation.

    Current: [download](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/original_snapshot/fcgi-2.4.1-SNAP-0910052249.tar.gz) | [docs](https://htmlpreview.github.io/?https://github.com/FastCGI-Archives/fcgi2/blob/master/doc/overview.html) | [browse](https://github.com/FastCGI-Archives/fcgi2)
*   [Wireshark protocol decode module](https://wiki.wireshark.org/FastCGI)

*   [PHP](http://www.php.net/)
    *   [PHP Usage Instructions](PHP_FastCGI.md)
    *   [Fastcgi Process manager 5.3.3](http://php-fpm.org/)
    *   [Fastcgi Process Manager integrated in php >5.3](http://php.net/manual/fr/install.fpm.php)
    *   [HHVM FastCGI support](http://hhvm.com/blog/1817/fastercgi-with-hhvm)
*   [Perl](http://www.perl.org/)
    *   [Perl Usage Instructions](Perl_FastCGI.md)
    *   [Perl FCGI](http://www.cpan.org/modules/by-module/FCGI/)
    *   [FCGI wrapper for Microsoft ™ IIS](http://search.cpan.org/~cosmicnet/) by Lyle Hopkins.
    *   [FCGI](http://search.cpan.org/~skimo/) by Sven Verdoolaege.
    *   [CGI::Fast](http://search.cpan.org/dist/CGI-Fast/) by Lincoln D. Stein.
    *   [Catalyst](http://catalyst.perl.org/) MVC For Perl
*   [Fastcgi for Ruby](http://www.rubydoc.info/gems/fcgi/)
*   [Python](http://www.python.org/)
    *   Native support of FastCGI [pyhton fastcgi](https://docs.python.org/2/howto/webservers.html#setting-up-fastcgi)
    *   Jon Ribbens' multi-threaded 'servlet' interface - [jonpy](http://jonpy.sourceforge.net/)
    *   Robin Dunn's improvements to Digicool's module - [fcgi.py](http://alldunn.com/python/fcgi.py)
    *   Quentin Pradet's fork of flup-py module for Python 3 - [flup-py3](https://github.com/pquentin/flup-py3)
*   [FastCGI for .NET](http://fastcgi-for-net.readthedocs.io/en/latest/)
*   [FastCGI / CGI C++ Library](http://cgi.sourceforge.net/)
*   [jFastCGI Servlet](http://jfastcgi.org/)
*   [Golang](https://golang.org)
    *   [fcgi](https://golang.org/pkg/net/http/fcgi/) - Core library for implementing fastcgi application (responder role only).
    *   [gofast](https://github.com/yookoala/gofast) - Library for implementing fastcgi web server.
*   [Nodejs](https://nodejs.org/)
    *   [fastcgi](https://www.npmjs.com/package/fastcgi) - An extremely simple web server that serves a FastCGI application.
    *   [node-fastcgi](https://www.npmjs.com/package/node-fastcgi) - Library for implementing fastcgi application (all 3 roles).
*   [kcgi – minimal CGI and FastCGI library in C](https://kristaps.bsd.lv/kcgi/archive.html)
*   [Rust FastCGI package](https://crates.io/crates/fastcgi)
*   [Lua FastCGI extension](https://github.com/LuaDist/fcgi)
*   [haskell FastCGI package](https://hackage.haskell.org/package/fastcgi)
*   [FastCGI4D](http://dsource.org/projects/fastcgi4d/wiki) A Tango compatible FastCGI library for the D language
*   [TCL](http://www.tcl-tk.net/) - [TCL](http://www.nyx.net/~tpoindex/tcl.html#Fcgi)
*   Common Lisp
    *   John Hinsdale's [module](http://www.clisp.org/impnotes/fastcgi.html) for [CLISP](http://www.clisp.org/)
    *   Teemu Kalva's [module](http://www.s2.org/~chery/projects/fastcgi-cmucl) for [CMUCL](http://www.cons.org/cmucl/)
*   [Goanna Eiffel](http://goanna.sourceforge.net/) - The Goanna Eiffel project includes a native implementation of FastCGI for use with its web application libraries.
*   [GNU Smalltalk](http://smalltalk.gnu.org/)
    *   [NicolasPetton FCGI for gnu smalltalk](https://github.com/NicolasPetton/fcgi)
*   Jeff Coffield's VMS [module](http://www.digitalsynergyinc.com/fastcgi.html).
*   Scheme
    *    Phil Eaton's [module](https://github.com/eatonphil/pine) for Chicken Scheme
*   [NoSQL-Database GT.M](https://github.com/shabiel/fis-gtm) 
    *    Aalen University [FastCGI-for-GT.M](https://github.com/informatik-aalen/FastCGI-for-GT.M)

# Articles on FastCGI

*  [FastCGI — The Forgotten Treasur](http://www.nongnu.org/fastcgi/) from Peter Simons
*  [FastCGI: Persistent Applications for Your Web Server](http://www.linuxjournal.com/article/2607) from Paul Heinlein of linuxjournal
