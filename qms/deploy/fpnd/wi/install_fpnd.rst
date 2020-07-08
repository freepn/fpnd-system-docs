==================================================
 Installation / Checkout of fpnd On A User Device
==================================================

.. |Version| replace:: 0.9.0

:date: |date|, |time| PST8PDT
:authors: SLA
:tags: fpnd, deploy, install, checkout
:category: work_instruction
:slug: fpnd_install_wi
:summary: fpnd installation work instruction
:version: |Version|

.. |date| date::
.. |time| date:: %H:%M

.. contents:: Table of Contents

.. raw:: pdf

   PageBreak

Revisions
=========

.. list-table::
   :widths: 9 19 11 33
   :header-rows: 1

   * - Revision 
     - Author
     - Date
     - Description
   * - 0.0.1 
     - SLA
     - 2020-07-07
     - Initial draft

.. raw:: pdf

   PageBreak

1.0 - Purpose
=============

The parent installation procedure describes the overall flow for installation
and checkout of a single FreePN release on a valid target device (where "valid"
device = a real hardware device or full hardware VM) with a supported Linux
distribution.

The purpose of the installation procedure is to control the installation/checkout
process and make it repeatable.  This work instruction documents the steps to
perform the installation and checkout task on a single user device, and provides
for the proper communication and validation of any anomalies found.

2.0 - Scope
===========

Installation/upgrade and checkout of versioned fpnd release package on a
single user device.

2.1 - fpnd user node
--------------------

Device post-install state:

* The .deb package is successfully installed with no errors --or--
* The .ebuild is built and installed with no errors

Requires internet access:

* Verify blah
* Verify foo

3.0 - Records
=============

3.1 - Customer Data
-------------------

Not defined or implemented yet (TBD).

3.2 - Machine/Device Data
-------------------------

Not defined or implemented yet (TBD).

.. FIXME records

4.0 - Related Documents
=======================

4.1 - Work Instructions
-----------------------

* fpnd-system-docs/qms/deploy/fpnd/wi/TBD

.. FIXME add repository hyperlinks and related siblings

4.2 - Procedures
----------------

* fpnd-system-docs/qms/deploy/fpnd/fpnd_install_procedure.rst

.. FIXME add repository hyperlinks

4.3 - Other Documents
---------------------

Not enough QMS docs yet (in progress).

For now, see the following fpnd repo docs:

* `fpnd installation`_ - current README with ppa/install instructions

.. TODO more QMS documents

5.0 - Definitions
=================

5.1 Terms
---------

:`fpnd`_: the FreePN daemon
:`freepn-gtk3-indicator`_: desktop tray GUI for control/status of fpnd
 

5.2 - Acronyms and Abbreviations
--------------------------------

:amd64: Gentoo 64 bit Intel-compatible architecture name
:arm/armhf: Gentoo/Debian 32 bit ARM architecture name
:arm64/aarch64: Gentoo/Debian 64 bit ARM architecture name
:CDROM: Compact Disk Read-Only Memory
:CM: Configuration Management
:DVD: Digital Video Disk
:FAT: ancient simple 8.3 filesystem based on File Allocation Tables
:i686: generic 32 bit Intel-compatible architecture (Linux kernel)
:QA: Quality Assurance
:QMS: Quality Management System
:USB: Universal Serial Bus
:vfat: broken FAT filesystem with fake long filenames
:x86: Gentoo 32 bit Intel-compatible architecture name
:x86_64: generic 64 bit Intel-compatible architecture (Linux kernel)

6.0 - Responsibility
====================

(who maintains this procedure and associated work instructions;
normally this would be maintained by the engineering manager and/or
document CM/QA)

6.1 - Maintaining Organizations
-------------------------------

.. FIXME responsibility

7.0 - Prerequisites and Required Items
======================================

Any required software or other tools needed for this work instruction (may
include other related work instructions).

7.1 - Install Requirements
--------------------------

* Approved Linux distribution on supported hardware device
* The PPA (Ubuntu) or the python-overlay (Gentoo) installed and working
* A working internet connection


8.0 - Safety Requirements
=========================

Any required items such as safety glasses, grounding strap, etc.

Typically N/A (unless disassembling/assembling hardware).


9.0 - Instructions
==================

Complete install and checkout of fpnd on a user target device.  See the
sibling work instructions for other details

9.1 - Pre-install Checklist
---------------------------

Minimum required hardware:


9.2 - Installing or upgrading a release package
-----------------------------------------------

**On Ubuntu**


**On Gentoo**


9.3 - Expected Install Results
------------------------------


