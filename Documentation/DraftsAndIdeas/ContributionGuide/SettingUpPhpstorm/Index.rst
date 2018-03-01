.. include:: ../../../Includes.txt

.. important::
   This chapter was written from scratch. Please review carefully.

Current status: Very rough draft. Still needs more work!

.. _phpstorm-setup:

==========================
Draft: Setting up Phpstorm
==========================

Conventions on this page
========================

* If you need to select something from the menu in Phpstorm, menu items are displayed like this: `File: Settings: ....`

General setup
=============

`File: Settings: Languages & Frameworks: PHP`
   - `PHP Language Level`: choose appropriate version
   - `CLI Interpreter`: choose appropriate version

.. image:: _assets/settings-language+frameworks-php.png
   :align: center
   :alt: Setup Phpstorm PHP settings


.. _phpstorm-setup-cgl:

Coding Guidelines
=================

PHP files
---------

`File: Settings: Editor: Code Style : PHP : Set From : Predefined Style`: choose PSR-1 / PSR-2


.. image:: _assets/settings-codestyle-php-setfrom.png
   :align: center
   :alt: Setup Phpstorm Predefined Code Style


In order to test this, use `Code: Reformat Code` to reformat a PHP file

**See also:**

* `Coding guidelines for TYPO3 <https://docs.typo3.org/typo3cms/CoreApiReference/CodingGuidelines/Index.html>`__


Xliff files
-----------

Language files are usually stored in a Folder Resources/Private/Language in files with the ending *.xlf*. While no
tabs are allowed to indent in PHP files, you should edit Xliff files using tabs.

.. Todo: How to set this up in Phpstorm, by default "Reformat code" converts .xlf files using spaces. Xliff is not
   listed in the standard Code Style file types, need to set "Other file types"?

.. Todo: Check for other file types (Typescript etc.): default?

.. _phpstorm-setup-plugins:

Recommended Plugins
====================

Install Plugins:

`File: Settings: Plugins`


* `DynamicReturnTypePlugin <https://plugins.jetbrains.com/plugin/7251-dynamicreturntypeplugin>`__
* `Php Inspections (EA Extended) <https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended->`__
* `TYPO3 CMS Plugin <https://plugins.jetbrains.com/plugin/9496-typo3-cms-plugin>`__
* `TYPO3 XLIFF Utility <https://plugins.jetbrains.com/plugin/8098-typo3-xliff-utility>`__
* `TypoScript plugin <https://plugins.jetbrains.com/plugin/7463-typoscript-plugin>`__


.. _phpstorm-setup-xdebug:

Setting up Phpstorm for Xdebug
==============================


.. _phpstorm-setup-testing:

Setting up  Phpstorm for the Testing Framework
==============================================

First setup the Testing Framework. Replace <YOUR_WEBROOT> with your path to the web directory. You must use absolute
paths for this.

`File: Settings: Languages & Frameworks: PHP: Test Frameworks`:

* Use composer autoloader
* `Path to script`: <YOUR_WEBROOT>/vendor/autoload.php
* Test runner: Defaut configuration file: <YOUR_WEBROOT>/vendor/typo3/testing-framework/Resources/Core/Build/UnitTests.xml
* Test Runner: Default bootstrap file: <YOUR_WEBROOT>/vendor/typo3/testing-framework/Resource/Core/Build/UnitTestsBootstrap.php


.. image:: _assets/settings-testing-framework.png
   :align: center
   :alt: Setup Testing Framework

Other Resources
===============

* https://wiki.typo3.org/Development/PHPStorm_Settings