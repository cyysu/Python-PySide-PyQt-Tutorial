# Introduction to PyQt5

This is an introductory PyQt5 tutorial. The purpose of this tutorial is to get you started with the PyQt5 toolkit. The tutorial has been created and tested on Linux. PyQt4 tutorial covers PyQt4, which is a blending of the Python language (2.x and 3.x) to the Qt4 library.  

## About PyQt5

PyQt5 is a set of Python bindings for Qt5 application framework from Digia. It is available for the Python 2.x and 3.x. This tutorial uses Python 3. Qt library is one of the most powerful GUI libraries. The official home site for PyQt5 is www.riverbankcomputing.co.uk/news. PyQt5 is developed by Riverbank Computing.  

PyQt5 is implemented as a set of Python modules. It has over 620 classes and 6000 functions and methods. It is a multiplatform toolkit which runs on all major operating systems, including Unix, Windows, and Mac OS. PyQt5 is dual licensed. Developers can choose between a GPL and a commercial license.  

PyQt5's classes are divided into several modules, including the following:  

- QtCore
- QtGui
- QtWidgets
- QtMultimedia
- QtBluetooth
- QtNetwork
- QtPositioning
- Enginio
- QtWebSockets
- QtWebKit
- QtWebKitWidgets
- QtXml
- QtSvg
- QtSql
- QtTest

The QtCore module contains the core non GUI functionality. This module is used for working with time, files and directories, various data types, streams, URLs, mime types, threads or processes. The QtGui contains classes for windowing system integration, event handling, 2D graphics, basic imaging, fonts and text. The QtWidgets module contains classes that provide a set of UI elements to create classic desktop-style user interfaces. The QtMultimedia contains classes to handle multimedia content and APIs to access camera and radio functionality. The QtBluetooth module contains classes to scan for devices and connect and interact with them. The QtNetwork module contains the classes for network programming. These classes facilitate the coding of TCP/IP and UDP clients and servers by making the network programming easier and more portable. The QtPositioning contains classes to determine a position by using a variety of possible sources, including satellite, Wi-Fi, or a text file. The Enginio module implements the client-side library for accessing the Qt Cloud Services Managed Application Runtime. The QtWebSockets module contains classes that implement the WebSocket protocol. The QtWebKit contains classes for a web browser implementation based on the WebKit2 library. The QtWebKitWidgets contains classes for a WebKit1 based implementation of a web browser for use in QtWidgets based applications. The QtXml contains classes for working with XML files. This module provides implementation for both SAX and DOM APIs. The QtSvg module provides classes for displaying the contents of SVG files. Scalable Vector Graphics (SVG) is a language for describing two-dimensional graphics and graphical applications in XML. The QtSql module provides classes for working with databases. The QtTest contains functions that enable unit testing of PyQt5 applications.  

## PyQt4 and PyQt5 differences PyQt4和PyQt5的区别

The PyQt5 is not backward compatible with PyQt4; there are several significant changes in PyQt5. However, it is not very difficult to adjust older code to the new library. The differences are, among others, the following:  

PyQt5向后并不兼容于PyQt4；在PyQt5中有很多的重要的改变。不过，将旧代码调整以适应新的库也不是难事。它们之间的区别如下：  

Python modules have been reorganized. Some modules have been dropped (QtScript), others have been split into submodules (QtGui, QtWebKit).  

Python模块被重新组织了。部分模块被丢弃（QtScript），部分模块被分割到了自模块中（QtGui, QtWebKit）。

New modules have been introduced, including QtBluetooth, QtPositioning, or Enginio.  

新的模块被引进，包括tBluetooth, QtPositioning, 或者 Enginio。  

PyQt5 supports only the new-style signal and slots handlig. The calls to SIGNAL() or SLOT() are no longer supported.
PyQt5 does not support any parts of the Qt API that are marked as deprecated or obsolete in Qt v5.0.  

PyQt5仅支持新风格的信号与插槽处理。对SIGNAL()或者SLOT()的调用不再被支持。PyQt5不支持任何已经在Qt5.0版本的Qt API中标记删除、或者过时的部分。  

img:omit  

python logo Python is a general-purpose, dynamic, object-oriented programming language. The design purpose of the Python language emphasizes programmer productivity and code readability. Python was initially developed by Guido van Rossum. It was first released in 1991. Python was inspired by ABC, Haskell, Java, Lisp, Icon, and Perl programming languages. Python is a high-level, general purpose, multiplatform, interpreted language. Python is a minimalistic language. One of its most visible features is that it does not use semicolons nor brackets. It uses indentation instead. There are two main branches of Python currently: Python 2.x and Python 3.x. Python 3.x breaks backward compatibility with previous releases of Python. It was created to correct some design flaws of the language and make the language more clean. The most recent version of Python 2.x is 2.7.9, and of Python 3.x is 3.4.2. Python is maintained by a large group of volunteers worldwide. Python is open source software. Python is an ideal start for those who want to learn programming.  

This tutorial uses Python 3.x version.  

Python programming language supports several programming styles. It does not force a programmer to a specific paradigm. Python supports object-oriented and procedural programming. There is also a limited support for functional programming.  

The official web site for the Python programming language is python.org  

Perl, Python, and Ruby are widely used scripting languages. They share many similarities and they are close competitors.  

This chapter was an introduction to PyQt5 toolkit.  
