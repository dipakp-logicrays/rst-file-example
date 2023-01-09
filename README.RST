===========================
This is the README.rst file
===========================


:Type: ``list``
:Options: ``htmlzip``, ``pdf``, ``epub``, ``all``
:Default: ``[]``

Paragraphs contain text and may contain inline markup:
*emphasis*,

**strong emphasis**,

`interpreted text`,

``inlineliterals``,

standalone hyperlinks (https://www.python.org),

===============
 Section Title
===============

---------------
 Section Title
---------------

Section Title
=============

Section Title
-------------

+------------------------------+
| paragraph                    |
|                              |
+------------------------------+

+------------------------------+
| paragraph                    |
|                              |
+------------------------------+

Lists
-----

- This is the first bullet list item.  The blank line above the
  first list item is required; blank lines between list items
  (such as below this paragraph) are optional.

- This is the first paragraph in the second item in the list.

  This is the second paragraph in the second item in the list.
  The blank line above this paragraph is required.  The left edge
  of this paragraph lines up with the paragraph above, both
  indented relative to the bullet.

  - This is a sublist.  The bullet lines up with the left edge of
    the text blocks above.  A sublist is a new list so requires a
    blank line above and below.

- This is the third item of the main list.

This paragraph is not part of the list.

Definition
-----------

term 1
    Definition 1.

term 2
    Definition 2, paragraph 1.

    Definition 2, paragraph 2.

term 3 : classifier
    Definition 3.

term 4 : classifier one : classifier two
    Definition 4.

\-term 5
    Without escaping, this would be an option list item.


Docinfo Example
===============

:Author: Dipak Prajapati
:Contact: dipakp@logicrays.com
:Date: 2023-01-09
:Status: Work In Progress
:Version: 1
:Filename: $RCSfile$
:Copyright: This document has been placed in the public domain.
:Version: 1
:Indentation: Since the field marker may be quite long, the second
   and subsequent lines of the field body do not have to line up
   with the first line, but they must be indented relative to the
   field name marker, and they must line up with each other.

Take it away, Eric the Orchestra Leader!

    | A one, two, a one two three four
    |
    | Half a bee, philosophically,
    |     must, *ipso facto*, half not be.
    | But half the bee has got to be,
    |     *vis a vis* its entity.  D'you see?
    |
    | But can a bee be said to be
    |     or not to be an entire bee,
    |         when half the bee is not a bee,
    |             due to some ancient injury?
    |
    | Singing...


This is an ordinary paragraph, introducing a block quote.

    "It is my business to know things.  That is my trade."

    -- Sherlock Holmes
    
Table
=====

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | Cells may span columns.          |
+------------------------+------------+---------------------+
| body row 3             | Cells may  | - Table cells       |
+------------------------+ span rows. | - contain           |
| body row 4             |            | - body elements.    |
+------------------------+------------+---------------------+


Admonitions
============

.. attention:: This is a attention admonition.
   This is the second line of the first paragraph.

   - The attention contains all indented body elements
     following.
   - It includes this bullet list.

.. caution:: This is a caution admonition.
   This is the second line of the first paragraph.

   - The caution contains all indented body elements
     following.
   - It includes this bullet list.


.. danger:: This is a danger admonition.
   This is the second line of the first paragraph.

   - The danger contains all indented body elements
     following.
   - It includes this bullet list.

.. error:: This is a error admonition.
   This is the second line of the first paragraph.

   - The error contains all indented body elements
     following.
   - It includes this bullet list.


.. hint:: This is a hint admonition.
   This is the second line of the first paragraph.

   - The hint contains all indented body elements
     following.
   - It includes this bullet list.

.. important:: This is a important admonition.
   This is the second line of the first paragraph.

   - The important contains all indented body elements
     following.
   - It includes this bullet list.

.. note:: This is a note admonition.
   This is the second line of the first paragraph.

   - The note contains all indented body elements
     following.
   - It includes this bullet list.

.. tip:: This is a tip admonition.
   This is the second line of the first paragraph.

   - The tip contains all indented body elements
     following.
   - It includes this bullet list.


.. warning:: This is a warning admonition.
   This is the second line of the first paragraph.

   - The warning contains all indented body elements
     following.
   - It includes this bullet list.


"To Ma Own Beloved Lassie: A Poem on her 17th Birthday", by
Ewan McTeagle (for Lassie O'Shea):

    .. line-block::

        Lend us a couple of bob till Thursday.
        I'm absolutely skint.
        But I'm expecting a postal order and I can pay you back
            as soon as it comes.
        Love, Ewan.
        

.. code:: python

  def my_function():
      "just a test"
      print 8/2

.. code:: json

  {
  	"Name":"Dipak",
  	"Age": 27
  }
  
.. code:: php

	<?php
	declare(strict_types=1);

	namespace Amasty\Mage24Fix\Plugin\Catalog\ViewModel\Product;

	use Magento\Catalog\ViewModel\Product\Breadcrumbs as MagentoBreadcrumbs;
	use Magento\Framework\App\Config\ScopeConfigInterface;
	use Magento\Store\Model\ScopeInterface;

	class BreadcrumbsPlugin
	{
	    public const XML_PATH_CATEGORY_URL_SUFFIX = 'catalog/seo/category_url_suffix';
	    public const XML_PATH_PRODUCT_USE_CATEGORIES = 'catalog/seo/product_use_categories';

	    /**
	     * @var ScopeConfigInterface
	     */
	    private $scopeConfig;

	    public function __construct(ScopeConfigInterface $scopeConfig)
	    {
	        $this->scopeConfig = $scopeConfig;
	    }
	}


.. csv-table:: Frozen Delights!
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"

I recommend you try |Python|_.

.. |Python| replace:: Python, *the* best language around
.. _Python: https://www.python.org/


Tab Example
----------------

.. tabs::

   .. tab:: Sphinx

      .. code:: yaml

         # Required
         version: 2

         # Set the version of Python and other tools you might need
         build:
           os: ubuntu-22.04
           tools:
             python: "3.11"

   .. tab:: MkDocs

      .. code:: yaml

         # Required
         version: 2

         # Set the version of Python and other tools you might need
         build:
           os: ubuntu-22.04
           tools:
             python: "3.11"

Dropdown Example
----------------

.. dropdown:: Easy to use
    :open:

    Documentation code doesn't have to be written by a programmer.

    Getting started is also made easy:

      * All new to this? Take the official :external+jupyterbook:doc:`Jupyter Book Tutorial <start/your-first-book>`
      * Curious for practical code? See :doc:`/examples`
      * Familiar with Sphinx? See :doc:`/guides/jupyter`
      
      
Grid Example:
=============

.. grid:: 3
    :gutter: 2
    :padding: 0

    .. grid-item-card:: Jupyter Project Documentation
      :img-top: img/logo_jupyter.png
      :link: https://docs.jupyter.org/

    .. grid-item-card:: Chainladder - Property and Casualty Loss Reserving in Python
      :img-top: img/logo_chain_ladder.png
      :link: https://chainladder-python.readthedocs.io/

    .. grid-item-card:: Feature-engine - A Python library for Feature Engineering and Selection
      :img-top: img/logo_feature_engine.png
      :link: https://feature-engine.readthedocs.io/en/latest/
      
Download file
--------------

You may use this :download:`PGP key </_static/security/pgpkey.txt>`


Tree level titles
-----------------

Quick summary
-------------

Features
--------


Redirect types
--------------

Prefix redirects
~~~~~~~~~~~~~~~~


Page redirects
~~~~~~~~~~~~~~

Exact redirects
~~~~~~~~~~~~~~~

Exact redirects examples
^^^^^^^^^^^^^^^^^^^^^^^^

Redirecting a single URL
````````````````````````


**Result**

Quick summary

Features

Redirect types

    Prefix redirects

    Page redirects

    Exact redirects

        Exact redirects examples

            Redirecting a single URL
