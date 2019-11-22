THRUX Implementation Guide
==========================

Introduction
------------

This guide is aimed to help designers manage their workflows throughout the design lifecycles of their projects.  And it will also show examples of how to turn their THRUX models into deliverable documents.

We will cover Branches, Issuances, and exporting your designs to AutoCAD or Excel.

.. _Branching:

Branching
---------

What is a Branch?  What are common ways to use Branches?

Branching is a tool to help aid the efforts of project management.

Every project has a default Branch which is called the Base Branch.

.. figure:: images/Branching-0.PNG
    :align: center

    Issuance Log displays the default Base Branch

The idea is to create a Branch once you know the scope of work for your next issuance.

Creating a Branch is like creating a copy of a Branch, however, this allows for additional functionality.

A Branch can be compared against one of it's previous Branches.

.. figure:: images/Branching-1.PNG
    :align: center

    Using the Issuance Log to view the project history

A timeline is displayed at the bottom of the Issuance Log to help visualize change management.

.. figure:: images/Branching-2.PNG
    :align: center

    Branch History is displayed at the bottom of the Issuance Log

Preparing Drawings
------------------

Once your design is reviewed and ready to be issued, the next step is to export your design.  

The goal is to get a THRUX model into a drafting environment like AutoCAD or Revit to produce a deliverable to Contractors.

The Riser, One-Line, and Schedules are exportable to AutoCAD.

Schedules are also exportable to Excel.

The Studies are flexible reports which can be printed in PDF format.

Once you have built a THRUX model, export the documents you need as necessary.  The following information is exportable:
  * Riser
  * One-Line
  * Schedules
  * Studies
  * Pricing Report

Riser
^^^^^

Export the Riser to AutoCAD by clicking on the down arrow.

.. figure:: images/ExportRiser.PNG
    :align: center

One-Line
^^^^^^^^

Export the One-Line to AutoCAD by clicking on the down arrow.

.. figure:: images/ExportOneLine.PNG
    :align: center

.. _Schedule-Views:

Schedules and Schedule Views
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Schedule Views are groupings of electrical Schedules.  For example, designers may group their Schedules by size or by priority.  In other words, the main or larger panels are grouped together, and the utility or emergency panels are placed in another group.

It is possible to export all of your Schedules at the same time, however, that operation may take longer and it may be more beneficial to export Schedules in smaller groups.

These Views can be viewed at any time. 

.. figure:: images/ScheduleSetup-0.PNG
    :align: center

    Saving a group of Schedules as a Schedule View

After you create your Views, you can export your Schedules to AutoCAD.  

Click on the down arrow and then click "Export To AutoCAD: Selected."

.. figure:: images/ScheduleSetup-1.PNG
    :align: center

    Saving a group of Schedules as E-500

Name the file with the same name as your Schedule .

  * FileName_Equipment_Name.dwg

You should see multiple instances of AcCoreConsole (Command Prompt) opening on your screen.  This will create multiple AutoCAD files in your directory.

.. figure:: images/ScheduleSetup-2.PNG
    :align: center

    Exporting Schedules to AutoCAD

We've created a folder which holds all of our THRUX exports.

.. figure:: images/ScheduleSetup-3.PNG
    :align: center

    THRUX Schedules

In AutoCAD, now we can set up a single drawing which XREFs our THRUX Schedules.  When the design changes, we can export our schedules, and our drawings will update.


Summary
-------

Create a :ref:`Branch <Branching>` once you know the scope of work for your next Issuance.  Various aspects of THRUX models are exportable in multiple formats.  Set up :ref:`Schedule Views <Schedule-Views>` to view Schedules in groups and to set up your AutoCAD XREFs.

Feel free to contact us at Support with any questions.

  * thruxservices@thrux.io
  * https://www.thrux.io