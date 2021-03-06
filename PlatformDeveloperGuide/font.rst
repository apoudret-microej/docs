.. _section_fonts:

Fonts
=====

The Font Engine is composed of:

-  The "Font Engine Core" module which decodes and prints at application
   runtime the platform-dependent fonts files generated by the "Font
   Generator."

-  A "Font Designer" module: a graphical tool which runs within the
   MicroEJ Workbench used to build and edit MicroUI fonts; it stores
   fonts in a platform-independent format.

-  A "Font Generator" module, for converting fonts from the
   platform-independent format into a platform-dependent format.

The three modules are complementary: a MicroUI font must be created and
edited with the Font Designer before being integrated as a resource by
the Font Generator. Finally the Font Engine Core uses the generated
fonts at runtime.

The Font Designer module and Font Generator module options are the
direct consequence of the Font Engine Core capacities. You must
understand the Font Engine Core capacities in order to correctly use the
modules.

.. toctree::
    :maxdepth: 2

    fontCore
    fontGenerator

..
   | Copyright 2008-2020, MicroEJ Corp. Content in this space is free 
   for read and redistribute. Except if otherwise stated, modification 
   is subject to MicroEJ Corp prior approval.
   | MicroEJ is a trademark of MicroEJ Corp. All other trademarks and 
   copyrights are the property of their respective owners.
