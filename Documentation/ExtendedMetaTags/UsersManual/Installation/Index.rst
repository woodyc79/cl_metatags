

.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. ==================================================
.. DEFINE SOME TEXTROLES
.. --------------------------------------------------
.. role::   underline
.. role::   typoscript(code)
.. role::   ts(typoscript)
   :class:  typoscript
.. role::   php(code)


Installation
^^^^^^^^^^^^

Install the extension. Select the template view and click on your
template. You will see a few new settings in the category
“plugin.clmetatags”.


Overriding global values
""""""""""""""""""""""""

This is an example for overriding typoscript variables by language id
in the constant-section of your template:

::

   [globalVar = GP:L = 1]
   plugin.clmetatags.description = Global description
   [global]

