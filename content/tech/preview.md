---
title: Sigasi Studio Preview (4.5)
layout: page
pager: true
date: 2019-08-16
comments: true
---

For those users who want to get early access to the features and bugfixes of upcoming Sigasi Studio releases, we have set up an extra release channel, called "*Sigasi Preview*".

The Sigasi Preview release channel offers more frequent releases than the official releases. This page gives an introduction to the most important changes.

Although these preview releases are less rigorously tested than than the official releases, they are stable enough for daily use.

**If you run into any problems, please let us know**.

# Current preview release

Most important changes since the [4.4 release](/releasenotes/sigasi-4.04):

* Report error when a package has multiple package bodies
* Better hover for procedures
* Add checking on library name
* Mixed component declaration templates now use integer as default type for generics
* Net search shows load when net is used in if statement with binary or unary expressions
* Net search shows loads and drives from concurrent assignments outside of processes
* Verilog blockdiagrams show wires for module instantiations using named associations
* Improved outline for concurrent signal assignments in VHDL
* Verilog comment folding with include files
* Resolved VHDL Formatting bug in indexed port map
* Added an icon for `Set Top` in the `Hierarchy View`
* Add lintings for packed struct/union and untagged unions
* Error/warning marker for duplicate labels
* Fixed bug when hovering over protected type
* Fixed out of memory exceptions for exotic Verilog code
* Show tabs in hover code
* VUnit run.py file can be a linked resource
* Packed unions can only contain members of integral data types
* Doubled Sigasi Studio's default stacksize
* Add linting for missing choices in SystemVerilog switch case
* Documentation can now be exported as HTML

# Update or install?

You can download the Stand-alone version of the latest preview version from:

* <https://download.sigasi.com/preview/latest/com.sigasi.hdt.product-linux.gtk.x86_64.zip>
* <https://download.sigasi.com/preview/latest/com.sigasi.hdt.product-macosx.cocoa.x86_64.zip>
* <https://download.sigasi.com/preview/latest/com.sigasi.hdt.product-win32.win32.x86_64.zip>

You can also update from (configure via Preferences > Install/Update > Available Software Sites > Add...) :
  https://download.sigasi.com/preview/studio/

SHA Sums ([more info](/faq#how-can-i-check-a-sha-sum)) can be checked via <https://download.sigasi.com/preview/latest/sha1.txt>

# Feedback

We welcome your feedback trough the usual channels or the comments below. Note that comments are cleared after each [official release](/releasenotes).
