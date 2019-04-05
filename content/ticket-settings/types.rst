Types
=====

Good Key Performance Indicators (KPI) require knowing the type of work your organization performs. Not all tasks take the same amount of effort even when performed by the same team. Creating a queue structure for this purpose can be overpowered due to the amount of configuration required to create and manage a queue.

Basic KPI measurement is achived in OTRS with minimal overhead by using ticket types. Typical types used in IT service desks are *unclassified*, *incident* and *problem*. You can quickly define new types with ease. Using these types, a statistic can be generated for use in reports to show how many incidents have been reported since a specific change was made. This could indicate a problem after the change. A reduction in incidents, can releate to a successful change.

Use this screen to add types to the system. A fresh OTRS installation contains an *unclassified* type by default. The type management screen is available in the *Types* module of the *Ticket Settings* group.

.. figure:: images/type-management.png
   :alt: Type Management Screen

   Type Management Screen

.. warning::

   Services must first be activated via :doc:`../administration/system-configuration` under the *Administration* group to be selectable in the ticket screens. You may click on the link in the warning message to directly jump to the configuration setting.

.. figure:: images/type-activate-warning.png
   :alt: Type Activation Warning

   Type Activation Warning


Manage Types
------------

To add a type:

1. Click on the *Add Ticket Type* button in the left sidebar.
2. Fill in the required fields.
3. Click on the *Save* button.

.. figure:: images/type-add.png
   :alt: Add Type Screen

   Add Type Screen

.. warning::

   Types can not be deleted from the system. They can only be deactivated by setting the *Validity* option to *invalid* or *invalid-temporarily*.

To edit a type:

1. Click on a type in the list of types.
2. Modify the fields.
3. Click on the *Save* or *Save and finish* button.

.. figure:: images/type-edit.png
   :alt: Edit Type Screen

   Edit Type Screen

.. note::

   If several types are added to the system, use the filter box to find a particular type by just typing the name to filter.


Type Settings
-------------

The following settings are available when adding or editing this resource. The fields marked with an asterisk are mandatory.

Name \*
   The name of this resource. Any type of characters can be entered to this field including uppercase letters and spaces. The name will be displayed in the overview table.

Validity \*
   Set the validity of this resource. Each resource can be used in OTRS only, if this field is set to *valid*. Setting this field to *invalid* or *invalid-temporarily* will disable the use of the resource.
