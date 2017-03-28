---
layout: default
title: FastCGI.com Archives
description: This is the Github FastCGI Archives of FastCGI.com site.
---


<p align="center">
  <a href='https://github.com/FastCGI-Archives'><img src="https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/litespeed-screenshot.jpg?raw=true" alt="FastCGI Logo"/></a>
</p>

# About FastCGI

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

## [FastCGI Licence](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/Licence%20_%20FastCGI%20-.md)

## [New FAQ](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/FAQ%20(Newer)%20_%20FastCGI%20-.md)

## [FAQ](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/FastCGI%20FAQ.md)
Frequently asked questions, examples and explanations.

## [FastCGI White Paper](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/FastCGI_%20A%20High-Performance%20Web%20Server%20Interface%20_%20FastCGI%20-.md)
Describes the motivation for FastCGI, the FastCGI interface, FastCGI application roles, the FastCGI application library, and FastCGI performance.

## [Understanding FastCGI Application Performance](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/Understanding%20FastCGI%20Application%20Performance%20_%20FastCGI%20-.md)
Why FastCGI applications often run faster than applications coded directly to Web server APIs.

## [FastCGI Developer' Kit](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/FastCGI%20Developer's%20Kit%20_%20FastCGI%20-.md)
How to configure and build the kit, and write applications using the FastCGI application libraries.

## [FastCGI Programmer' Guide](https://htmlpreview.github.io/?https://github.com/FastCGI-Archives/fcgi2/blob/master/doc/fastcgi-prog-guide/cover.htm)
Programmer-oriented documentation for developers of FastCGI applications. The content overlaps considerably with the Developer's Kit document.

## [FastCGI Specification](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/FastCGI%20Specification.md)
Defines the interface between a FastCGI application and the Web server.

## [FastCGI - A High-Performance Gateway Interface](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/FastCGI_%20A%20High-Performance%20Gateway%20Interface%20_%20FastCGI%20-.md)
Position paper presented at the workshop "Programming the Web -- a search for APIs", Fifth International World Wide Web Conference, 6 May 1996, Paris, France.

## Rob's Open Source '99 Presentations
Two FastCGI related presentations given at O'reilly's Open Source '99 Conference in Monterey, CA.

**From the Perl Conference (Applying Perl track):**

Scaling CGI with Perl  | [PDF](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/docs/FastCGI-Perl.pdf) |  [PowerPoint](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/docs/FastCGI-Perl.ppt)

**From the Apache Conference:**

The Apache FastCGI Implementation  | [PDF](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/docs/FastCGI.pdf) |  [PowerPoint](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/docs/FastCGI.ppt)

## [The Apache FastCGI Process Manager](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/The%20Apache%20FastCGI%20Process%20Manager%20_%20FastCGI%20-.md)
A description of some of the functionality of the process manager in mod_fastcgi. I'm not sure how accurate it is.

# Servers that support FastCGI
* Apache - [http://www.apache.org](http://www.apache.org)
  * Apache 2.4 native support :
     - [mod_proxy_fcgi](https://httpd.apache.org/docs/2.4/mod/mod_proxy_fcgi.html)
     - [mod_authnz_fcgi](https://httpd.apache.org/docs/2.4/mod/mod_authnz_fcgi.html)
  * Apache 2.x [Mod_fcgid](http://httpd.apache.org/mod_fcgid/)
  
  * Open Market mod_fastcgi free, open-source Apache httpd module. 
  
       Current: [download](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/original_snapshot/mod_fastcgi-SNAP-0910052141.tar.gz) | [docs](https://htmlpreview.github.io/?https://github.com/FastCGI-Backups/mod_fastcgi/blob/master/docs/mod_fastcgi.html) | git: [history](https://github.com/FastCGI-Archives/mod_fastcgi)

      * [Apache install instructions](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/Apache%20Install%20_%20FastCGI%20-.md)
      * [Apache FAQ](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/Apache%20FAQ%20_%20FastCGI%20-.md)

* Microsoft IIS - [http://www.iis.net/fastcgi/configuration](http://www.iis.net/fastcgi/configuration)
* Microsoft IIS (second generation) - [http://www.coastrd.com/Home](http://www.coastrd.com/Home) which supports SIGTERM and the Aprellium Abyss server as well
* SunOne - [https://docs.oracle.com/cd/E19146-01/821-1828/6nmpm01ns/index.html](https://docs.oracle.com/cd/E19146-01/821-1828/6nmpm01ns/index.html)
* Lighttpd - [http://trac.lighttpd.net/trac/wiki/Docs%3AModFastCGI](http://trac.lighttpd.net/trac/wiki/Docs%3AModFastCGI)
* Premium thttpd [http://schumann.cx/premium-thttpd/](http://schumann.cx/premium-thttpd/)
* MyServer - [http://www.myserverproject.net/](http://www.myserverproject.net/)
* Pi3Web - [http://pi3web.sourceforge.net/](http://pi3web.sourceforge.net/)
* Nginx - [http://wiki.nginx.org/NginxHttpFcgiModule](http://wiki.nginx.org/NginxHttpFcgiModule)
* Cherokee - [http://cherokee-project.com/doc/modules_handlers_fcgi.html](http://cherokee-project.com/doc/modules_handlers_fcgi.html)

## API/Libraries

The FastCGI application libraries.

*   The Development Kit - **C**, **C++**, **Perl**, and **Java**, libraries as well as assorted documentation.  

    Current: [download](https://github.com/FastCGI-Archives/FastCGI.com/raw/master/original_snapshot/fcgi-2.4.1-SNAP-0910052249.tar.gz) | [docs](https://htmlpreview.github.io/?https://github.com/FastCGI-Archives/fcgi2/blob/master/doc/overview.html) | [browse](https://github.com/FastCGI-Archives/fcgi2)
*   [FastCGI4D](http://dsource.org/projects/fastcgi4d/wiki) A Tango compatible FastCGI library for the D language
*   [Perl](http://www.perl.org/)
    *   [Perl FCGI](http://www.cpan.org/modules/by-module/FCGI/)
    *   [FCGI wrapper for Microsoft ™ IIS](http://search.cpan.org/~cosmicnet/) by Lyle Hopkins.
    *   [FCGI](http://search.cpan.org/~skimo/) by Sven Verdoolaege.
    *   [CGI::Fast](http://search.cpan.org/dist/CGI.pm/CGI/Fast.pm) by Lincoln D. Stein.
    *   [Perl Usage Instructions](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/Perl _ FastCGI -.md)
    *   [Catalyst](http://catalyst.perl.org/) MVC For Perl
*   [PHP](http://www.php.net/)
    *   [PHP Usage Instructions](https://github.com/FastCGI-Archives/FastCGI.com/blob/master/docs/PHP _ FastCGI -.md)
    *   [Fastcgi Process manager](http://php-fpm.org/) (requires php 5.3.3)
*   [Fastcgi for Ruby](https://rubyforge.org/projects/fcgi/)
*   [Python](http://www.python.org/)
    *   Jon Ribbens' multi-threaded 'servlet' interface - [jonpy](http://jonpy.sourceforge.net/)
    *   Peter Åstrand's multi-threaded module - [thfcgi.py](http://cvs.lysator.liu.se/viewcvs/viewcvs.cgi/webkom/thfcgi.py?cvsroot=webkom)
    *   Andreas Jung's multi-threaded wrapper for fcgi.py - [sz_fcgi.py](http://www.suxers.de/python/fcgi.htm)
    *   Robin Dunn's improvements to Digicool's module - [fcgi.py](http://alldunn.com/python/fcgi.py)
*   [TCL](http://www.tcl-tk.net/) - [TCL](http://www.nyx.net/~tpoindex/tcl.html#Fcgi)
*   [Common Lisp](#CommonLisp)

*   John Hinsdale's [module](http://clisp.cons.org/impnotes/modules.html#fastcgi) for [CLISP](http://clisp.cons.org/)
*   Teemu Kalva's [module](http://www.s2.org/~chery/projects/fastcgi-cmucl) for [CMUCL](http://www.cons.org/cmucl/)

*   [Goanna Eiffel](http://goanna.info/) - The Goanna Eiffel project includes a native implementation of FastCGI for use with its web application libraries.
*   [Smalltalk](http://www.smalltalk.org/)
    *   [FasTalk](http://www.mod.smalltalk.org/)
    *   [FS FastCGI](http://www.dolphinharbor.org/dh/projects/fs/index.html) for [Dolphin Smalltalk](http://www.object-arts.com/)
*   Jeff Coffield's VMS [module](http://www.digitalsynergyinc.com/fastcgi.html).
