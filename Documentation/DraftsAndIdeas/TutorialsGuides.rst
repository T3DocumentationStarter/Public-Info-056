.. include:: ../Includes.txt
.. highlight:: bash

====================================
DRAFT: Tutorials and Guides (merged)
====================================

See https://docs.typo3.org/typo3cms/GuidesAndTutorials/Index.html

.. toctree::
   :hidden:

   Getting Started Tutorial ➜              <https://docs.typo3.org/typo3cms/GettingStartedTutorial/>
   Installation & Upgrade Guide ➜        <https://docs.typo3.org/typo3cms/InstallationGuide/>
   Frontend Localization ➜                 <https://docs.typo3.org/typo3cms/FrontendLocalizationGuide/>
   Tutorial for Editors ➜                  <https://docs.typo3.org/typo3cms/EditorsTutorial/>
   TypoScript in 45 Minutes ➜              <https://docs.typo3.org/typo3cms/TyposcriptIn45MinutesTutorial/>
   Sitepackage Tutorial ➜                  <https://docs.typo3.org/typo3cms/SitePackageTutorial/>
   Templating Tutorial ➜                    <https://docs.typo3.org/typo3cms/TemplatingTutorial/>
   Developing TYPO3 Extensions with Extbase and Fluid (book)  ➜ <https://docs.typo3.org/typo3cms/ExtbaseFluidBook/Index.html>
   Extbase & Fluid Guide ➜                       <https://docs.typo3.org/typo3cms/ExtbaseGuide/>
   Core Contribution Guide ➜               <https://docs.typo3.org/typo3cms/ContributionWorkflowGuide/>
   Writing Documentation ➜                 <https://docs.typo3.org/typo3cms/HowToDocument/>
   Documentation Rendering With Docker ➜   <https://github.com/t3docs/docker-render-documentation/blob/master/README.rst>

.. _getting-started:

Getting Started
===============

It is recommended to begin with the :ref:`t3start:start` and then continue
with the documentation that is best suited for your background and the
task at hand. So, if you are a developer, look in the :ref:`tutguides-developers`
section on this page. There are also sections for :ref:`tutguides-editors`,
:ref:`tutguides-integrators`, :ref:`tutguides-devops`, :ref:`tutguides-sysad`
and :ref:`tutguides-docs`.


.. t3-field-list-table::
 :header-rows: 1

 - :Title:        Title
   :Category:     Category
   :Description:  Description

 - :Title:        `Getting Started Tutorial <https://docs.typo3.org/typo3cms/GettingStartedTutorial/>`__
   :Category:     Getting started
   :Description:  The official tutorial to discover the main features and concepts of TYPO3 CMS.
                  It is based on the Introduction Package.

 - :Title:        :ref:`t3install:start`
   :Category:     Installation & Upgrade
   :Description:  How to **install** TYPO3 (with or without composer) and
                  how to **upgrade** an existing installation.

 - :Title:        :ref:`t3l10n:start`
   :Category:     Translation
   :Description:  Everything you need to know about **multiple languages**
                  and **translation** in TYPO3.

.. tip::

   Did you know, you can click on "Related links" at the bottom of a page in most
   manuals to select a different version? The versions of the manual correspond to the TYPO3
   version. :ref:`Read more ... <usage-version-selector>`

.. _tutguides-editors:

Editors
=======

For a detailed list of resources see :ref:`t3start:next-steps-editors`
in the "Getting Started Tutorial".


.. t3-field-list-table::
 :header-rows: 1

 - :Title:        Title
   :Category:     Category
   :Description:  Description

 - :Title:        `Tutorial for Editors <https://docs.typo3.org/typo3cms/EditorsTutorial/>`__
   :Category:     Editing
   :Description:  How to create pages and content elements, access control
                  and working with multiple languages.

.. _tutguides-integrators:

Integrators
===========

For a detailed list of resources see :ref:`t3start:next-steps-developers`
in the "Getting Started Tutorial".

Integrators should also look in the :ref:`references` section.

.. t3-field-list-table::
 :header-rows: 1

 - :Title:        Title
   :Category:     Category
   :Description:  Description


 - :Title:        :ref:`TypoScript in 45 Minutes <t3ts45:start>`
   :Category:     Development / Integration
   :Description:  TypoScript is a configuration language that is specific to TYPO3.
                  This guide will walk you through the basics. For more information
                  see :ref:`t3tsref:start`.

 - :Title:        `Sitepackage Tutorial <https://docs.typo3.org/typo3cms/SitePackageTutorial/>`__
   :Category:     Development / Integration
   :Description:  Integrate frontend templates and TYPO3 configuration in
                  your own sitepackage extension using the Fluid templating engine.
                  :ref:`[read more] <news-2018-06-13>`

 - :Title:        :ref:`Templating Tutorial <t3templating:start>`
   :Category:     Development / Integration
   :Description:  The tutorial now teaches templating with FLUIDTEMPLATE (recommended)
                  in its `master branch <https://docs.typo3.org/typo3cms/TemplatingTutorial/>`__.
                  *Marker based templating* used to be prevalent before. It can
                  be found in the `7.6 branch
                  <https://docs.typo3.org/typo3cms/TemplatingTutorial/7.6/>`__.
                  The `Sitepackage Tutorial
                  <https://docs.typo3.org/typo3cms/SitePackageTutorial/>`__
                  covers FLUIDTEMPLATE as well.

.. _tutguides-developers:

Developers
==========

For a detailed list of resources see
:ref:`t3start:next-steps-developers` in the
"Getting Started Tutorial".

Developers should also look in the :ref:`references` section.

.. t3-field-list-table::
 :header-rows: 1

 - :Title:        Title
   :Category:     Category
   :Description:  Description

 - :Title:        :ref:`Developing TYPO3 Extensions with Extbase and Fluid (book) <t3extbasebook:start>`
   :Category:     Development
   :Description:  An extensive walkthrough on extension development for
                  TYPO3 using the **Extbase** framework and **Fluid**
                  templating engine. (Warning: is partly outdated and incomplete)

 - :Title:        :ref:`t3extbase:start`
   :Category:     Development
   :Description:  This contains some information about **Extbase** and **Fluid**
                  for extension development but is
                  not a comprehensive Guide or Tutorial at this point.
                  Also available a complete :ref:`ViewHelper reference <t3viewhelper:start>`.

 - :Title:        :ref:`t3contribute:start`
   :Category:     Development
   :Description:  How to contribute to the **TYPO3 codebase** and how to
                  **submit issues** (e.g. Bug reports).


.. _tutguides-docs:

Documentation Writers
=====================

The following  is about contributing to the documentation on docs.typo3.org,
to the Changelog in the TYPO3 core and for adding documentation to an
extension.

A good start page is :ref:`h2document:getting-started` in "Writing Documentation".

.. t3-field-list-table::
 :header-rows: 1

 - :Title:        Title
   :Category:     Category
   :Description:  Description

 - :Title:        :ref:`h2document:start`
   :Category:     Documentation
   :Description:  Provides all necessary information about writing documentation.
                  Explains how to write documentation, either for an TYPO3
                  extensions, TYPO3 changelog, TYPO3 core, or official TYPO3
                  Documentation. The same markup and rendering toolchain is used
                  in all cases.

 - :Title:        `Render TYPO3 Documentation With Docker <https://github.com/t3docs/docker-render-documentation/blob/master/README.rst>`__
   :Category:     Documentation
   :Description:  How to render the documentation locally with Docker.

 - :Title:        :ref:`rendert3docs:start`
   :Category:     Documentation
   :Description:  How the TYPO3 documentation is rendered. This guide is a work in progess and currently
                  heavily under construction.
                  At the moment, it is recommended to go directly to
                  `Render TYPO3 Documentation With Docker <https://github.com/t3docs/docker-render-documentation/blob/master/README.rst>`__
                  for information about local rendering with Docker.


Example Manuals
---------------

*Example manuals* for both extensions and official manuals,
which also serve as guidelines to the usage of reStructuredText.


.. t3-field-list-table::
 :header-rows: 1

 - :Title:        Title
   :Description:  Description

 - :Title:        `Extension Manual <https://docs.typo3.org/typo3cms/ExtensionManualExample>`__
   :Description:


.. _tutguides-devops:

DevOps
======

.. t3-field-list-table::
 :header-rows: 1

 - :Title:        Title
   :Category:     Category
   :Description:  Description

 - :Title:        `TYPO3 Surf <https://docs.typo3.org/surf/>`__
   :Category:     Deployment
   :Description:  Surf package is a complete automated deployment tool.


.. _tutguides-sysad:

System Administrators
=====================

The following guides or sections should be relevant for you:

* :ref:`t3install:start`
* :ref:`Security Guidelines for System Administrators <t3coreapi:security-administrators>`
