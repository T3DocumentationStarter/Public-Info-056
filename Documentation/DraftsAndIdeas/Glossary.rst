
.. include:: ../Includes.txt

.. Suggestions:
   1. Keep text here short and link to relevant sections in manual.
   2. Do not use

==============
TYPO3 Glossary
==============

Overview of basic terms, acronyms and hashtags used throughout the TYPO3 documentation
and TYPO3 community.

.. hint::

   This is a first draft. The idea is: When people are new to TYPO3, 
   they might get confused by the terminology. This should serve as
   a handy reference. The explanations should be kept short and link 
   to the places in the documentation where the terms are explained 
   in more detail.
   
   
.. _backend:

Backend 	
=======

TYPO3 provides a view for editing and administrating the TYPO3 
installation. In order to interact with the backend, you need to 
login as a backend user.

See

* :ref:`Backend and Frontend <t3start:backend-and-frontend>` 
  (Getting started tutorial)
* :ref:`Backend interface <t3inside:backend-modules-structure>` 
  (Inside TYPO3)

.. _backend_module:

Backend module	
==============

In the backend of a TYPO3 installation, the left panel shows a 
module menu which lists all available backend modules. Backend 
modules are only available in the backend. 

Backend modules are provided by :ref:`extensions`, as are
:ref:`Plugin` (displayed in the Frontend).

See

* :ref:`Backend Modules <t3inside:backend-modules-structure>` 
  (Inside TYPO3)
* :ref:`Extension Architecture <t3coreapi:extension-architecture-introduction>` 
  (Core API)

.. _cache:

Cache
=====



.. _ckeditor:

Ckeditor
========



.. _composer:

Composer
========

Composer is not specific to TYPO3.

Composer is a tool for dependency management in PHP. It can be used
to setup / manage a TYPO3 installation including the required 
extensions (and their dependencies). Currently, there is more than 
one way to setup a TYPO3 installation. It can be done with composer 
or without. The recommended way is to use composer

See

* `Composer <https://getcomposer.org/>`_
* `How to install TYPO3 using composer 
  <https://typo3.com/blog/how-to-install-typo3-using-composer-in-less-than-5-minutes/>`__ 
  (Core API)


.. _core:

Core
====

TYPO3 basic code and functionality. Since (almost) everything is an
extension in TYPO3, core functionality is bundled inside the extension 
"core".

.. _datahandler:

DataHandler
===========

Formerly known as TCEmain. 

DataHandler provides an API for modifying (creating, modifying, copying, 
deleting) TYPO3 database records.

See

* :ref:`DataHandler basics (Core API) <t3coreapi:tce-database-basics>`

.. _doctrine_dbal:

Doctrine DBAL
=============

Doctrine is not specific to TYPO3.

Doctrine DBAL (database abstraction & access layer) is an abstraction layer 
for accessing various databases. It is used in TYPO3 since TYPO3 8.

See

* :ref:`Database overview (Core API) <t3coreapi:Database_Introduction>`

.. _Extbase:

Extbase
=======

.. The following sentence was copied verbatim from the manual. See the provided link. Feel free to modify and improve. 

Extbase is a framework for TYPO3 extension development. 

See

* :ref:`Introduction (TYPO3 Extbase guide) <t3extguide>`


.. _extensions:


.. _extension_builder:

Extension Builder
=================




Extensions
==========

Extensions are software components for TYPO3. An extension must 
adhere to some standards in order to be detected and loaded by TYPO3. 

Extensions may be installed via the :ref:`extension_manager` or via 
:ref:`composer`.  

The TYPO3 source code itself consists mostly of extensions.

The Extension Architecture of TYPO3 makes TYPO3 very extendable and flexible. 

A large number of Extensions provided by 3rdparties are available 
via the TYPO3 Extension Repository (:ref:`ter`) or `Packagist
<https://packagist.org/packages/typo3/>`__ (if you use composer). 

Extensions are typically developed using :ref:`extbase` / :ref:`fluid`. 

See

* :ref:`Extension Architecture 
  <t3coreapi:extension-architecture-introduction>` 
  (Core API)
* `TYPO3 Extension Repository 
  <https://extensions.typo3.org/>`__ 
  (TER)

.. _extension_manager:

Extension Manager
=================

The Extension Manager is accessible in the :ref:`backend` of a TYPO3
Installation. It can be used to configure Extensions, execute update 
scripts of Extensions, import, install, uninstall, update and remove 
Extensions.

If :ref:`composer` is used to setup a TYPO3 installation, all installation 
/ deinstallation of Extensions is done via composer. In this case, it 
is not possible to do this with the Extension Manager.

See

* :ref:`Extension Manager <t3start:extension-manager>` (Getting Started)
* :ref:`Extension Manager <t3coreapi:extension-manager>` (Core API)


.. _fal:

FAL
===

FAL = File Abstraction Layer 

Abstraction Layer in the TYPO3 core for handling files. 

See

* :ref:<t3coreapi:fal_introduction> (Core API)
* :ref:`Using FAL <t3coreapi:using-fal>` (Core API)


.. _flash_messages:

Flash messages
==============

.. _flexform:

Flexform
========

.. This is a first draft for a text. I didn't really find a place in the documentation where flexforms are explained. 

Flexforms are used to configure plugins. A configuration schema is defined in XML. It can contain text fields, lists and other elements. This defineds how the plugin is configured in the TYPO3 backend. The configuration is stored into a single field pi_flexform inside the tt_content table. 

See

* fixme: add link

.. _Fluid:

Fluid
=====

Fluid is a templating engine used by TYPO3. 

See

* :ref:`Fluid <t3extguide:start>` (Extbase / Fluid guide)

.. _frontend:

Frontend
========


.. _formengine:

FormEngine
==========

See

* :ref:`FormEngine <t3coreapi:FormEngine-Introduction>` (Core API)


.. _hook:

Hook
====


.. _install_tool:

Install Tool
============


.. _neos:

Neos
====

.. _plugins:

Plugins
=======

See

* * :ref:`Extension Architecture <t3coreapi:extension-architecture-introduction>` (Core API)


.. _rte:

RTE
===

.. _scheduler:

Scheduler
=========


.. _signal:

Signal
======

.. _system_log:

System Log
==========

.. _tca:

.. _t3dd:

t3dd
====

TYPO3 developer days (Event) 

.. _t3uxw:

T3uxw
=====

TYPO3 User Experience Week (Event)

TCA
===

TCA = Table Configuration Array

.. The following sentence was copied almost verbatim from the tca reference. The rest was added later. See the provided link. Feel free to modify and improve. 

A global array $GLOBALS['TCA']. which extends the definition of 
database tables beyond what can be done strictly with SQL.


TCA defines / configures properties and relations between database 
tables and fields. It can be used to:

* define which tables / fields are editable in the TYPO3 backend
* configure what is displayed in the backend
* define relations between tables
* configure validators for database fields 

See

* :ref:`Introduction <t3tca:introduction>` (TCA Reference)

.. _tce:

TCE
===

TCE = TYPO3 core engine

The TYPO3 Core Engine handles all data writing to database tables 
as configured in TCA. 

See

* :ref:`TYPO3 Core Engine <t3coreapi:tce-introduction>` (Core API)

.. _tcemain:

TCEmain
=======

Deprecated term, see :ref:`datahandler`.

.. _tceform:

TCEform
=======


.. _template:

Template
========

In the context of TYPO3, template can mean one of many things:

* a :ref:`typoscript` template, which is a set of TypoScript configuration connected to a specific page (and it's subpages)
* a :ref:`fluid` template file defining how a plugin / content element / page is to be rendered
* the general process of using a template as a general blueprint for the site layout. The template contains static parts and dynamic parts that will be filled differently for each page

fixme: 

.. _ter:

TER
===

TYPO3 Extension Repository

See

* `TER <https://extensions.typo3.org/>`__

.. _tsconfig:

TSConfig
========


.. tsfe:

TSFE
====

TSFE = TypoScript Frontend

$GLOBALS['TSFE'] is an array which contains information for the currently rendered page, e.g. the current language or pid.  

See

* fixme: add link

.. I did not find any place in the docs where TSFE is explained ... 

.. _typo3:


TYPO3
=====

.. _typo3_cms:

TYPO3 CMS
=========

.. _typo3_association:

TYPO3 Association
=================

.. _typo3_cms:

TYPO3 CMS
=========

.. _typo3_gmbh:

TYPO3 GmbH
===========


.. _typoscript:

TypoScript
==========

.. _user_int:

USER / USER_INT
===============