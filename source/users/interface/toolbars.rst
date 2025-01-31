.. SPDX-FileCopyrightText: 2024 Qelectrotech Team <license@qelectrotech.org>
..
.. SPDX-License-Identifier: GPL-2.0-only

.. _interface/toolbars:

Toolbars
========

In addition to the different `menus`_, QElectroTech also provides toolbars. The toolbars are 
groups of buttons with icons which initiate accions. In general, these buttons have its 
counterpart at one of the menus from the `menu bar`_. 

.. note::

   To help the user, a tooltip is displayed when the arrow is placed on each button.

Toolbar Tools
~~~~~~~~~~~~~

.. figure:: /_external/_images/en/qet_toolbar/qet_toolbar_tools.png
   :align: center

   Figure: QElectroTech toolbar Tools 

The different buttons from toolbar **Tools** are: 

+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Tool            | Function                                                         | Keyboard shortcut         | Icon               |
+==================+==================================================================+===========================+====================+
|  New             | Creates a new Project                                            |                           | |project-new|      |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Open            | Opens an existing project                                        |   ``Ctrl + o``            | |project|          | 
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Save            | Saves the current project and all its folios                     |   ``Ctrl + s``            | |document-save|    |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Save as         | Saves the current project with a different file name             |                           | |document-save-as| |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Close           | Closes the current project                                       |   ``Ctrl + w``            | |project-close|    |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Print           | Print one or more folio of the current project                   |   ``Ctrl + p``            | |document-print|   |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Undo            | Undoes the previous action                                       |  ``Ctrl + z``             | |edit-undo|        |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Redo            | Restores the undone action                                       |  ``Ctrl + Shift + z``     | |edit-redo|        |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Cut             | Puts selected elements into the clipboard                        |  ``Ctrl + x``             | |edit-cut|         |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Copy            | Copies selected elements                                         |  ``Ctrl + c``             | |edit-copy|        |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Paste           | Pastes elements from the clipboard into the folio                |  ``Ctrl + v``             | |edit-paste|       |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Delete          | Removes selected elements from the folio                         |  ``Del``                  | |edit-delete|      |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+
|  Rotate          | Rotates selected elements and texts                              |  ``Space``                | |transform-rotate| |
+------------------+------------------------------------------------------------------+---------------------------+--------------------+   

.. note::

   Select **Settings > display > Tools** menu item to display or hidden the toolbar **Tools**.

Toolbar Display
~~~~~~~~~~~~~~~

.. figure:: /_external/_images/en/qet_toolbar/qet_toolbar_display.png
   :align: center

   Figure: QElectroTech toolbar Display

The different buttons from toolbar **Display** are:

+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+-------------------+
| Tool                           | Function                                                                                   | Keyboard shortcut      | Icon              |
+================================+============================================================================================+========================+===================+
| Select                         | Allows to select elements                                                                  |                        | |select|          |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+-------------------+
| Move                           | Allows to view the folio without modifying it                                              |                        | |move|            |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+-------------------+
| Display the grid               | Displays or hidden the grid of folio                                                       |                        | |grid|            |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+-------------------+
| Background color white / gray  | Displays the background color of the folio in white or gray                                |                        | |diagram_bg|      |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+-------------------+
| Zoom content                   | Adjusts the zoom to display all the content of folio regardless of context                 |  ``Ctrl + 8``          ||zoom-draw|        |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+-------------------+
| Fit in view                    | Adjusts the zoom on exactly trhe part of the folio                                         |  ``Ctrl + 9``          ||view-fit-window|  |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+-------------------+
| Reset zoom                     | Restores default zoom level                                                                |  ``Ctrl + 0``          ||zoom-original|    |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+-------------------+

.. note::

   Select **Settings > Display > Display** menu item to display or hidden the toolbar **Display**.

Toolbar Diagram
~~~~~~~~~~~~~~~

.. figure:: /_external/_images/en/qet_toolbar/qet_toolbar_diagram.png
   :align: center

   Figure: QElectroTech toolbar Diagram

The different buttons from toolbar **Diagram** are:

+-------------------------------------------+----------------------------------------------------------------------+---------------------------+--------------------------+
| Tool                                      | Function                                                             | Keyboard shortcut         | Icon                     |
+===========================================+======================================================================+===========================+==========================+
|  Folio properties                         | Edits the properties of the folio                                    |  ``Ctrl + l``             | |dialog-information|     |
+-------------------------------------------+----------------------------------------------------------------------+---------------------------+--------------------------+
|  Reset conductors                         | Resets the conductors path ignoring the user changes                 |  ``Ctrl + k``             | |conductor2|             |
+-------------------------------------------+----------------------------------------------------------------------+---------------------------+--------------------------+
|  Automatic creation conductor             | Using the automatic creation of conductor (s) when possible          |                           | |autoconnect|            |
+-------------------------------------------+----------------------------------------------------------------------+---------------------------+--------------------------+

.. note::

   Select **Settings > Display > Diagram** menu item to display or hidden the toolbar **Diagram**.

Toolbar Add
~~~~~~~~~~~

.. figure:: /_external/_images/en/qet_toolbar/qet_toolbar_add.png
   :align: center

   Figure: QElectroTech toolbar Add

The different buttons from toolbar **Add** are:

+----------------------+---------------------------------------------------------+---------------------------+----------------+
| Tool                 | Function                                                | Keyboard shortcut         | Icon           |
+======================+=========================================================+===========================+================+
|  Add a textfield     | Adds a text field to the current folio                  |                           | |textfield|    |
+----------------------+---------------------------------------------------------+---------------------------+----------------+
|  Add a picture       | Adds an image to the current folio                      |                           | |insert-image| |
+----------------------+---------------------------------------------------------+---------------------------+----------------+
|  Add line            | Adds a line to the current folio                        |                           | |line|         |
+----------------------+---------------------------------------------------------+---------------------------+----------------+
|  Add a rectangle     | Adds a rectangle to the current folio                   |                           ||rectangle|     |
+----------------------+---------------------------------------------------------+---------------------------+----------------+
|  Add an ellipse      | Adds an ellipse to the current folio                    |                           | |ellipse|      |
+----------------------+---------------------------------------------------------+---------------------------+----------------+
|  Add a polygon       | Adds a polyline to the current folio                    |                           | |polygon|      |
+----------------------+---------------------------------------------------------+---------------------------+----------------+

.. note::

   Select **Settings > Display > Add** menu item to display or hidden the toolbar **Add**.

Toolbar Depth
~~~~~~~~~~~~~

.. figure:: /_external/_images/en/qet_toolbar/qet_toolbar_depth.png
   :align: center

   Figure: QElectroTech toolbar Depth 

The different buttons from toolbar **Depth** are:

+---------------------+-----------------------------------------------------------+---------------------------+-------------------+
| Tool                | Function                                                  | Keyboard shortcut         | Icon              |
+=====================+===========================================================+===========================+===================+
|  Bring forward      | Brings the selection (s) to front                         |  ``Ctrl + shift + Home``  | |bring_forward|   |
+---------------------+-----------------------------------------------------------+---------------------------+-------------------+
|  Raise              | Approach the selection (s)                                |  ``Ctrl + shift + Up``    | |raise|           |
+---------------------+-----------------------------------------------------------+---------------------------+-------------------+
|  Lower              | Moves away the selection (s)                              |  ``Ctrl + shift + Down``  | |lower|           |
+---------------------+-----------------------------------------------------------+---------------------------+-------------------+
|  Send backwards     | Sends in the backwards the selection (s)                  |  ``Ctrl + shift + End``   | |send_backward|   |
+---------------------+-----------------------------------------------------------+---------------------------+-------------------+

.. note::

   Select **Settings > Display > Depth** menu item to display or hidden the toolbar **Depth**.

.. _menus: ../interface/menu_bar.html
.. _menu bar: ../interface/menu_bar.html

.. |project-new| image:: /_external/_images/_site-assets/user/ico/22x22/project/project-new.png
.. |project| image:: /_external/_images/_site-assets/user/ico/22x22/project/project.png
.. |document-save| image:: /_external/_images/_site-assets/user/ico/22x22/document/document-save.png
.. |document-save-as| image:: /_external/_images/_site-assets/user/ico/22x22/document/document-save-as.png
.. |project-close| image:: /_external/_images/_site-assets/user/ico/22x22/project/project-close.png
.. |document-print| image:: /_external/_images/_site-assets/user/ico/22x22/document/document-print.png
.. |edit-undo| image:: /_external/_images/_site-assets/user/ico/22x22/edit/edit-undo.png
.. |edit-redo| image:: /_external/_images/_site-assets/user/ico/22x22/edit/edit-redo.png
.. |edit-cut| image:: /_external/_images/_site-assets/user/ico/22x22/edit/edit-cut.png
.. |edit-copy| image:: /_external/_images/_site-assets/user/ico/22x22/edit/edit-copy.png
.. |edit-paste| image:: /_external/_images/_site-assets/user/ico/22x22/edit/edit-paste.png
.. |edit-delete| image:: /_external/_images/_site-assets/user/ico/22x22/edit/edit-delete.png
.. |transform-rotate| image:: /_external/_images/_site-assets/user/ico/16x16/transform-rotate.png
.. |select| image:: /_external/_images/_site-assets/user/ico/22x22/select.png
.. |move| image:: /_external/_images/_site-assets/user/ico/22x22/move.png
.. |grid| image:: /_external/_images/_site-assets/user/ico/22x22/grid.png
.. |diagram_bg| image:: /_external/_images/_site-assets/user/ico/22x22/diagram/diagram_bg.png
.. |zoom-draw| image:: /_external/_images/_site-assets/user/ico/22x22/zoom/zoom-draw.png
.. |view-fit-window| image:: /_external/_images/_site-assets/user/ico/22x22/view/view-fit-window.png
.. |zoom-original| image:: /_external/_images/_site-assets/user/ico/22x22/zoom/zoom-original.png
.. |dialog-information| image:: /_external/_images/_site-assets/user/ico/22x22/dialog/dialog-information.png
.. |conductor2| image:: /_external/_images/_site-assets/user/ico/22x22/conductor2.png
.. |autoconnect| image:: /_external/_images/_site-assets/user/ico/22x22/autoconnect.png
.. |textfield| image:: /_external/_images/_site-assets/user/ico/22x22/textfield.png
.. |insert-image| image:: /_external/_images/_site-assets/user/ico/22x22/insert-image.png
.. |line| image:: /_external/_images/_site-assets/user/ico/22x22/line.png
.. |ellipse| image:: /_external/_images/_site-assets/user/ico/22x22/ellipse.png
.. |rectangle| image:: /_external/_images/_site-assets/user/ico/22x22/rectangle.png
.. |polygon| image:: /_external/_images/_site-assets/user/ico/22x22/polygon.png
.. |bring_forward| image:: /_external/_images/_site-assets/user/ico/22x22/bring_forward.png
.. |raise| image:: /_external/_images/_site-assets/user/ico/22x22/raise.png
.. |lower| image:: /_external/_images/_site-assets/user/ico/22x22/lower.png
.. |send_backward| image:: /_external/_images/_site-assets/user/ico/22x22/send_backward.png