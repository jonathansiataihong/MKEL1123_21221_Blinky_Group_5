Intel(R) Quartus(R) Prime Design Suite Standard Edition Version 21.1 README.TXT
===============================================================================

Although we have made every effort to ensure that this version of the Intel FPGA
software operates correctly, you can encounter problems that we have not 
discovered. If you have a question or problem that is not answered by the 
information provided in this readme.txt file, please go to 
https://www.intel.com/content/www/us/en/products/programmable.html 
and click Support, or submit a service request at 
https://premiersupport.intel.com.

This readme.txt file contains the following information:
* Intel Quartus Prime Design Suite Contents
   Lists the set of Intel design tools.
* Technical Documentation
   Directs you where to find documentation for Intel design tools.
* System Requirements
   Lists the system requirements.
* Useful Links
   Lists links to other Intel Quartus Prime resources including videos and 
   reference designs.
* Notices
   Trademark and other legal notices that apply to this document.


Intel Quartus Prime Design Suite Standard Edition Contents
==========================================================
*  Intel Quartus Prime Design Standard Edition Software
   (includes the Intel FPGA IP Library and Intel Nios(R) II Embedded Design Suite)
*  Questa(*)- Intel FPGA Edition simulation tool
*  Questa - Intel FPGA Starter Edition simulation tool
*  Intel FPGA SoC Embedded Development Suite (Pro and Standard Editions)

You can download the Intel Quartus Prime software, as well as tools such 
as the Advanced Link Analyzer or Stand-Alone Programmer, from the
Intel FPGA and Programmable Devices Download Center on the Intel website:
https://www.intel.com/content/www/us/en/programmable/downloads/download-center.html


Technical Documentation
=======================

Release Notes
-------------
*  Intel Quartus Prime Software and Device Support Release Notes
   Provides information about new features and enhancements, known issues,
   workarounds, device support information, memory requirements for design
   processing, and timing and power model status. This document is available on 
   the Intel FPGA website:
   https://www.intel.com/content/dam/altera-www/global/en_US/pdfs/literature/rn/rn-qts-std-dev-support.pdf

*  Intel FPGA IP Release Notes
   Provides information about new features and enhancements, errata, and
   workarounds. For a complete list of all Intel FPGA IP release notes, see the 
   Intel FPGA and Programmable Devices Release Notes page on the Intel FPGA 
   website:
   https://www.intel.com/content/www/us/en/programmable/documentation/lit-rn.html

*  Intel Nios II Release Notes
   Provides information about new features, enhancements, bug fixes, and
   known issues for the Nios(R) II Embedded Design Suite (EDS), Nios(R) 
   Processor IP, and Embedded Intellectual Property (IP). This document is 
   available on the Intel FPGA website:
   https://www.intel.com/content/dam/altera-www/global/en_US/pdfs/literature/rn/rn_nios2.pdf
   
*  Intel SoC Embedded Development Suite Release Notes
   Provides information about new features, enhancements, bug fixes and known 
   issues for both Pro and Standard Editions. This document is available on the
   Intel FPGA website:
   https://www.intel.com/content/dam/altera-www/global/en_US/pdfs/literature/rn/rn_soc_eds.pdf

Errata
------
   You can find information, errata, and workarounds by searching the Intel FPGA
   Knowledge Base:
   https://www.intel.com/content/www/us/en/programmable/support/support-resources/knowledge-base/kdb-filter.html

Other Technical Documentation
-----------------------------
*  Intel Quartus Prime Software Download and Installation Quick Start Guide
   Provides directions on how to download and install both Windows and Linux
   versions of the Quartus Prime Design Suite software. This document is 
   available on the Intel FPGA website:
   https://fpgasoftware.intel.com/static/quick_start_guide/quick_start_guide_21.1_en.pdf

*  Intel FPGA Software Installation and Licensing Manual 21.1
   Provides information about installing and licensing your Intel FPGA design
   software. This document is available on the Intel FPGA website:
   https://www.intel.com/content/dam/altera-www/global/en_US/pdfs/literature/manual/quartus_install.pdf

*  Introduction to the Intel Quartus Prime Software
   Provides an introduction to using the Intel Quartus Prime software. This 
   document is available on the Intel FPGA website:
   https://www.intel.com/content/dam/altera-www/global/en_US/pdfs/literature/br/br-quartus-prime-software.pdf

*  Intel Quartus Prime User Guides
   Provides detailed information about all aspects of
   the Intel Quartus Prime software. These documents are available on the Intel
   FPGA website:
   https://www.intel.com/content/www/us/en/programmable/products/design-software/fpga-design/quartus-prime/user-guides.html

*  AN 320: Intel FPGA IP Evaluation Mode
   https://www.intel.com/content/dam/altera-www/global/en_US/pdfs/literature/an/an320.pdf


System Requirements
===================

Operating system support
------------------------
Intel Quartus Prime Design Suite components support one or more of the following
operating systems:
*  CentOS(*) 7.7
*  CentOS 8.2
*  Red Hat(*) Enterprise Linux(*) 7.7
*  Red Hat Enterprise Linux 8.2
*  SUSE(*) Linux Enterprise Server 12.0 SP5
*  SUSE Linux Enterprise Server 15.0 LTS
*  Ubuntu(*) 16.04.06
*  Ubuntu 18.04.01
*  Ubuntu 20.04 LTS
*  Windows(*) 10
*  Windows Server(*) 2012
*  Windows Server 2016
*  Windows Server 2019

Review the notes that follow to check operating system support for the 
components that you use.

Notes:
  * Only 64-bit operating systems are supported.
  * Intel Quartus Prime Standard and Lite editions are supported on all listed 
    operating systems.
  * Questa - Intel FPGA Edition and Questa - Intel FPGA Starter Edition are 
    supported only on the following operating systems:
         *  CentOS 7
         *  CentOS 8
         *  Red Hat Enterprise Linux 7
         *  Red Hat Enterprise Linux 8
         *  SUSE Linux Enterprise Server 12
         *  SUSE Linux Enterprise Server 15
         *  Windows 10
	  Red Hat Enterprise Linux operating systems require 32-bit library files.
   * Nios II EDS Standard Edition is supported only on the following operating 
     systems:
         *  SUSE Linux Enterprise Server 12
         *  Windows 10
  * Intel Quartus Prime Stand-Alone Programmer Standard Editions is 
    supported on all listed operating systems.
  * Intel SoC FPGA EDS Standard Editions is supported only on the following 
    operating systems:
         *  Windows 10
         *  Red Hat Enterprise Linux 6
         *  Ubuntu 18
 	 Red Hat Enterprise Linux 6 support requires 32-bit library files.
  * Intel Advanced Link Analyzer is supported only on Windows operating systems.

Operating System Support information including an updated list of limitations 
for all editions of the Intel Quartus Prime software can be found on the 
Intel FPGA website:
https://www.intel.com/content/www/us/en/programmable/support/support-resources/download/os-support.html

FLEXlm
------
   For more information on the FLEXlm license server software, refer to the 
   Intel FPGA Software Installation and Licensing manual:
   https://www.intel.com/content/dam/altera-www/global/en_US/pdfs/literature/manual/quartus_install.pdf

KDE or GNOME Display Manager
----------------------------
   *  Version included with your Linux operating system installation.


Useful Links
============
*  You can create a My Intel account where you can file a service request,
   register for a class, download software, and more on the Intel website.
   https://www.intel.com/content/www/us/en/secure/my-intel/dashboard.html

*  You can view video demonstrations for Intel(R) Quartus(R) Prime and Nios II 
   software on the Intel FPGA website:
   https://www.intel.com/content/www/us/en/programmable/support/training/demonstrations/dem-index.html

*  You can download reference designs that show efficient solutions for common 
   system design problems from Intel FPGA and our partners on the
   Intel FPGA website:
   https://www.intel.com/content/www/us/en/programmable/support/support-resources/reference-designs.html

*  You can compare the features of the Pro, Standard and Lite Editions of the 
   Intel(R) Quartus(R) Prime Software on the Intel FPGA website:
   https://www.intel.com/content/www/us/en/software/programmable/quartus-prime/download.html


Notices
=======
This product includes software derived from the RSA Data Security, Inc. 
MD5 Message-Digest Algorithm.

Intel, Nios, and Quartus words and logos are trademarks of Intel Corporation 
or its subsidiaries in the U.S. and/or other countries.

OpenCL and the OpenCL logo are trademarks of Apple Inc. used by permission of
the Khronos Group(TM).

Other names and brands may be claimed as the property of others.