
![alt text](media/logo/logo.gif "Awesome Automotive")
___

 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)   list of delightful and free automotive resources. Please read the [contribution guidelines](contributing.md) and start contributing !

## Contents

- [Autosar](#autosar)
- [Automotive SPICE](#automotive-spice)
- [Bus Systems](#bus-systems)
  - [Automotive Ethernet](#automotive-ethernet)
  - [CAN](#can)
  - [FlexRay](#flexray)
  - [LIN](#lin)
  - [MOST](#most)
- [Functional Safety](#functional-safety)
- [Cyber Security](#cyber-security)
- [Vehicle Diagnostics](#vehicle-diagnostics)
- [Requirements Engineering](#requirements-engineering)
  - [Polarion Software](#polarion-software-hammer_and_wrench)
  - [Rational DOORS](#rational-doors-hammer_and_wrench)
- [Software Development](#software-development)
  - [C/C++](#c/c++)
  - [Enterprise Architect](#enterprise-architect) 
  - [MULTI](#multi) 
  - [Trace32](#trace32)
- [Testing](#testing)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Books](#books)
  - [Magazines](#magazine)
  - [Podcasts](#podcasts)
  - [Press releases](#press-releases)
  - [Miscellaneous](#miscellaneous)

## Autosar

- [autosar.org](https://www.autosar.org/) - official website
  - [Classic Platform](https://www.autosar.org/standards/classic-platform/)
  - [Layered Software Architecture](https://www.autosar.org/fileadmin/user_upload/standards/classic/4-3/AUTOSAR_EXP_LayeredSoftwareArchitecture.pdf/)
  - [Adaptive Platform](https://www.autosar.org/standards/adaptive-platform/)
- ["Introduction to Autosar"](https://elearning.vector.com/mod/page/view.php?id=437) - Vector e-learning module
- [Technical Papers on the Development of Embedded Electronics - chapter 6  <img src="media/icons/pdf.png" width="18"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf#page=4) - Vector – Automotive. Embedded. Engineering, 2018 

## Automotive SPICE

- [ASPICE ](http://www.automotivespice.com/download/) - latest version of the Automotive SPICE® Process Assessment Model (PAM) and Process Reference Model (PRM)

## Bus Systems
- [Technical Papers on the Development of Embedded Electronics - chapter 1 <img src="media/icons/pdf.png" width="18"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf#page=3) - Vector – Automotive. Embedded. Engineering, 2018 

### Automotive Ethernet

- ["Introduction to Automotive Ethernet"](https://elearning.vector.com/mod/page/view.php?id=149) - Vector e-learning module
- [A TCP/IP Tutorial <img src="media/icons/student.png" width="18"/>](https://tools.ietf.org/html/rfc1180l) - RFC 1180, short overview on ethernet
- [OPEN Alliance. "Automotive Ethernet Specifications"](http://opensig.org/about/specifications/)
- [SOME/IP specifications and standards](http://some-ip.com/papers.shtml)
- [vsomeip in 10 minutes](https://github.com/GENIVI/vsomeip/wiki/vsomeip-in-10-minutes) - SOME/IP introduction based on GENIVI implementation
- Automotive Ethernet Stack with rederence to free standards
 <table style="border-collapse:collapse;border-spacing:0;table-layout: fixed; width: 612px" class="tg"><colgroup><col style="width: 87px"><col style="width: 61px"><col style="width: 66px"><col style="width: 76px"><col style="width: 66px"><col style="width: 77px"><col style="width: 62px"><col style="width: 117px"></colgroup><tr><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:normal;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Use Case</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Audio<br>Video<br></th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Time<br> Sync</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Network <br>Managment</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Service <br>Control</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;borgit statusder-color:inherit;text-align:center;vertical-align:middle">Diagnostic</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Address <br>Config</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Helper<br>Protocols</th></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Application</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" rowspan="2"><a href="http://read.pudn.com/downloads191/doc/899044/ISO+14229+(2006).pdf">UDS*</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Presentation</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Session</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" rowspan="3">IEEE<br>1722<br> <br>(AVTP)<br></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" rowspan="3">IEEE <br>802.1AS<br><br>(PTP)<br></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">UDP-NM</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"><a href="http://some-ip.com/papers.shtml">SOME/IP</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"><a href="http://read.pudn.com/downloads721/ebook/2887987/BS%20ISO%2013400-2-2012.pdf">DoIP*</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"><a href="https://tools.ietf.org/html/rfc2131">DHCP</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Transport</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" colspan="4"><a href="https://tools.ietf.org/html/rfc793">TCP</a> and/or <a href="https://tools.ietf.org/html/rfc768">UDP</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Network<br></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" colspan="4"><a href="https://tools.ietf.org/html/rfc791">IPv4</a>/<a href="https://tools.ietf.org/html/rfc2460">IPv6</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"><a href="https://tools.ietf.org/html/rfc792">ICMP</a>, <a href="https://tools.ietf.org/html/rfc4443">ICMPv6</a>, <a href="https://tools.ietf.org/html/rfc826">ARP</a>, <a href="https://tools.ietf.org/html/rfc4861">NDP</a></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Data Link</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" colspan="7">Ethernet MAC + VLAN (802.1Q)</td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Physical</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" colspan="7">Automotive Ethernet Physical <br>(Ethernet, <a href="http://opensig.org/about/specifications/">OPEN Alliance BroadR-Reach</a>, Reduced twisted-pair Gigabit Ethernet)</td></tr></table>
(*) - superseded by newer version of standard


### CAN

- [Bosch specification <img src="media/icons/pdf.png" width="18"/>](http://esd.cs.ucr.edu/webres/can20.pdf) - old document, superseded by the standard [ISO 11898](https://www.iso.org/standard/63648.html)
- [Bosch CAN FD specification Version 1.0 <img src="media/icons/pdf.png" width="18"/>](https://web.archive.org/web/20151211125301/http://www.bosch-semiconductors.de/media/ubk_semiconductors/pdf_1/canliteratur/can_fd_spec.pdf)
- [Controller Area Network (CAN) Schedulability Analysis: Refuted, Revisited and Revised](https://link.springer.com/article/10.1007%2Fs11241-007-9012-7)
- [Controller Area Network (CAN) Implementation Guide <img src="media/icons/pdf.png" width="18"/>](https://www.analog.com/media/en/technical-documentation/application-notes/AN-1123.pdf)
- ["Introduction to CAN"](https://elearning.vector.com/mod/page/view.php?id=333) - Vector e-learning module
- [Controller Area Network <img src="media/icons/pdf.png" width="18"/>](http://inst.cs.berkeley.edu/~ee249/fa08/Lectures/handout_canbus1.pdf) -  presentation UC Berkeley
- [Understanding and Using the Controller Area Network <img src="media/icons/pdf.png" width="18"/>](http://inst.cs.berkeley.edu/~ee249/fa08/Lectures/handout_canbus2.pdf) -  UC Berkeley, CAN 2.0b
- [CAN Protocol <img src="media/icons/student.png" width="18"/>](https://www.kvaser.com/course/can-protocol-tutorial/) - tutorial prepared by Kvaser (CAN products supplier). On their [site](https://www.kvaser.com/) can find lots of great resources
- [CAN Newsletter](https://can-newsletter.org/magazine)


### FlexRay

- [FlexRay Specification <img src="media/icons/pdf.png" width="18"/>](https://svn.ipd.kit.edu/nlrp/public/FlexRay/FlexRay%E2%84%A2%20Protocol%20Specification%20Version%203.0.1.pdf)
- [FlexRay Overview](https://www.ni.com/pl-pl/innovations/white-papers/06/flexray-automotive-communication-bus-overview.html) - Technical Overview of FlexRay by National Instruments
- ["Introduction to FlexRay"](https://elearning.vector.com/mod/page/view.php?id=371) - Vector e-learning module
- ["The FlexRay Electrical Physical Layer Evolution" <img src="media/icons/pdf.png" width="18"/>](https://web.archive.org/web/20150216112537/http://www.hanser-automotive.de/fileadmin/heftarchiv/FLEX_10_ONL_NXP-Y.pdf) - Lorenz Steffen, magazine Automotive 2010


### LIN

- ["Introduction to LIN"](https://elearning.vector.com/mod/page/view.php?id=309) - Vector e-learning module
- [LIN Supplier ID Registration Authority](https://www.lin-cia.org/id/) - Registration Authority for the LIN Supplier ID standardized in the ISO 17987 series
- ["The LIN Short Story" <img src="media/icons/pdf.png" width="18"/>](https://www.nxp.com/files-static/training_pdf/29021_S08_SLIN_WBT.pdf)


### MOST

- [MOST Cooperation Website](https://www.mostcooperation.com/)

## Functional Safety
- [ISO 26262-1:2011(en) (Road vehicles — Functional safety — Part 1: Vocabulary](https://www.iso.org/obp/ui/#iso:std:iso:26262:-1:ed-1:v1:en) -  ISO Online Browsing Platform (OBP)
- [What is the ISO 26262 Functional Safety Standard ?](https://www.ni.com/pl-pl/innovations/white-papers/11/what-is-the-iso-26262-functional-safety-standard-.html#toc2) - National Instruments White Paper on ISO 26262 functional safety standard
- [Criticality categories across safety standards in different domains <img src="media/icons/pdf.png" width="18"/>](https://web1.see.asso.fr/erts2012/Site/0P2RUC89/1A-1.pdf) - ERTS2 Congress. Embedded Real Time Software and Systems.
- [Technical Papers on the Development of Embedded Electronics - chapter 7 <img src="media/icons/pdf.png" width="18"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf#page=4) - Vector – Automotive. Embedded. Engineering, 2018 

## Cyber Security
- [Awesome Vehicle Security ](https://www.mostcooperation.com/) list of awesome resources, books, hardware, software, applications, people to follow, and more cool stuff about vehicle security, car hacking, and tinkering with the functionality of your car.
- [Technical Papers on the Development of Embedded Electronics - chapter 8 <img src="media/icons/pdf.png" width="18"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf#page=4) - Vector – Automotive. Embedded. Engineering, 2018 
## Vehicle Diagnostics

- [ISO 14229-1:2006(E) <img src="media/icons/pdf.png" width="18"/>](http://read.pudn.com/downloads191/doc/899044/ISO+14229+(2006).pdf) - Unified diagnostic services (UDS) specification, old document, superseded by the standard [ISO 14229-1:2013](https://www.iso.org/standard/55283.html) 
- [ ISO 13400-2:2012 <img src="media/icons/pdf.png" width="18"/>](http://read.pudn.com/downloads721/ebook/2887987/BS%20ISO%2013400-2-2012.pdf) - Road vehicles - Diagnostic communication over Internet Protoco (DoIP)
- [Technical Papers on the Development of Embedded Electronics - chapter 4 <img src="media/icons/pdf.png" width="18"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf#page=4) - Vector – Automotive. Embedded. Engineering, 2018 

## Requirements Engineering
### Polarion Software
- [Polarion course <img src="media/icons/student.png" width="18"/><img src="media/icons/video.png" width="18"/>](https://polarion.plm.automation.siemens.com/tutorials) 

### Rational DOORS 
- [Getting started <img src="media/icons/student.png" width="18"/>](https://www.ibm.com/developerworks/rational/library/getting-started-ibm-rational-doors/index.html) - tutorial for IBM Rational DOORS and IBM Rational DOORS Web Access
- [Documentation](https://www.ibm.com/support/pages/node/594725) - library pages contain documentation for earlier versions of Rational products
- [Essentials <img src="media/icons/video.png" width="18"/>](https://www.youtube.com/playlist?list=PLFB5C518530CFEC93) 
- [Using DXL](https://www.ibm.com/support/knowledgecenter/SSYQBZ_9.5.0/com.ibm.doors.configuring.doc/topics/c_dxl.html) - The Rational® DOORS® eXtension Language (DXL) is an easy-to-learn scripting language that you can use to control and extend Rational DOORS functions
- [The DXL Reference Manual](https://www.ibm.com/support/knowledgecenter/SSYQBZ_9.5.0/com.ibm.doors.requirements.doc/topics/dxl_reference_manual.pdf?view=kc)


## Software Development

### C/C++

- [Modern Embedded Systems Programming <img src="media/icons/student.png" width="18"/><img src="media/icons/video.png" width="18"/>](https://www.youtube.com/playlist?list=PLPW8O6W-1chwyTzI3BHwBLbGQoPFxPAPM)
- [awesome C/C++ resources list](https://github.com/fffaraz/awesome-cpp#readme)

###  Enterprise Architect
- [Enterprise Architect ](https://sparxsystems.com/products/ea/) - official product page, Sparx Systems

### MULTI
- [MULTI Integrated Development Environment ](https://www.ghs.com/products/MULTI_IDE.html)

### Trace32 
- [Lauterbach GmbH](https://www.lauterbach.com/frames.html?home.html) - tutorials, webinars, publications
- [Lauterbach GmbH <img src="media/icons/video.png" width="18"/>](https://www.youtube.com/channel/UCwHuwQUTt_FquA86O6DaLnQ) - YouTube channel
- [Nohau Lauterbach <img src="media/icons/video.png" width="18"/>](https://www.youtube.com/playlist?list=PL1sbHjUq1DdqQSBlk-uM-EJ3O1iof0-IN) - playlist with examples

## Testing
- [Programming with CAPL <img src="media/icons/pdf.png" width="18"/>](https://can-newsletter.org/assets/files/media/raw/a456e3078f907a0482182ce831912427.pdf)
- [Tips and Tricks for the Use of CAPL](https://kb.vector.com/entry/875/) three consecutive articles, for all levels of user knowledge [Part One](https://kb.vector.com/upload_551/file/CAPL_1_CANNewsletter_201406_PressArticle_EN.pdf), [Part Two](https://kb.vector.com/upload_551/file/CAPL_2_CANNewsletter_201409_PressArticle_EN.pdf), [Part Three](https://kb.vector.com/upload_551/file/CAPL_3_CANNewsletter_201411_PressArticle_EN.pdf)
- [Technical Papers on the Development of Embedded Electronics - chapter 3 <img src="media/icons/pdf.png" width="18"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf#page=3) - Vector – Automotive. Embedded. Engineering, 2018 
- [List of Free Software Testing Resources](https://github.com/ligurio/awesome-software-quality#readme) 
## Resources
### Blogs
- [just auto](https://www.just-auto.com/) - Global automotive industry news, data and analysis. Recent information about OEMs and suppliers
- [automotivetechis](https://automotivetechis.wordpress.com/)
- [automotive wiki](https://automotive.wiki/index.php/Main_Page) - provided by [SCHEID automotive GmbH ](https://www.scheid-automotive.com/)
### Books
- [Technical Papers on the Development of Embedded Electronics <img src="media/icons/pdf.png" width="18"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf) - Vector – Automotive. Embedded. Engineering, 2018
- [Automotive Embedded Systems Handbook <img src="media/icons/pdf.png" width="18"/>](https://d1.amobbs.com/bbs_upload782111/files_38/ourdev_629261ASTZIF.pdf) - Nicolas Navet, 2009
- [Understanding Automotive Electronics <img src="media/icons/pdf.png" width="18"/>](https://www.engbookspdf.com/uploads/pdf-books/UnderstandingAutomotiveElectronics8theditionbyWilliamB.Ribbens-1.pdf) - Eighth Edition, William B. Ribbens, 2017
- [Ford FMEA Handbook <img src="media/icons/pdf.png" width="18"/>](https://fsp.portal.covisint.com/documents/106025/14555722/FMEA%20Handbook%20v4.2/4c14da5c-0842-4e60-a88b-75c18e143cf7) - 2011
- [XCP – The Standard Protocol for ECU Development <img src="media/icons/pdf.png" width="18"/>](https://assets.vector.com/cms/content/application-areas/ecu-calibration/xcp/XCP_ReferenceBook_V3.0_EN.pdf) - Andreas Patzer, Rainer Zaiser
Vector Informatik GmbH, 2016
- [engineeringbookspdf](https://www.engineeringbookspdf.com/automobile-engineering/) - portal offers free access to about 150 automotive books
- [engbookspdf](https://www.engbookspdf.com/Automobile/)  - portal offers free access to about 35 automotive books
- [engbookspdf](http://www.engineering108.com/pages/Automobile_Engineering/Automobile-engineering-ebooks-free-download.html)  - portal offers free access to about 5 automotive books
- [list of free programming books](https://github.com/EbookFoundation/free-programming-books#readme) 

### Magazines

- [SAE Magazines](https://www.sae.org/publications/magazines) - set of free magazines from automotive industry
- [Vehicle Electronics](https://vehicle-electronics.biz/) - free monthly magazine for automotive electronics engineers
- [CAN Newsletter](https://can-newsletter.org/magazine)

### Podcasts

- [SAE Tomorrow Today ](https://www.sae.org/podcasts) - from SAE International, provides unique and dynamic perspectives from innovative industry leaders on the challenges of tomorrow
- [Matrickz](https://www.matrickz.de/en/podcasts.html) - by Matrickz GmbH mainly related to ASPICE, Security and ISO26262

### Press releases

- [Continental AG](https://www.continental.com/en/press/press-releases)
- [Elektrobit (EB)](https://www.elektrobit.com/tech-corner/)
- [Renesas Electronics Corporation](https://www.renesas.com/us/en/solutions/automotive.html)
- [OPEN Alliance](http://opensig.org/news/press-releases/)
- [SAE International](https://www.sae.org/news/press-room)
- [Softing Automotive Electronics GmbH](https://automotive.softing.com/en/service/press-publications/press-releases.html)
- [Vector Informatik GmbH](https://www.vector.com/int/en/search/?tx_solr%5Bfilter%5D%5B0%5D=contentType%3Atx_solr_file&tx_solr%5Bsort%5D=datetime+desc&tx_solr%5BresultsPerPage%5D=10)



### Miscellaneous

- [Vector Support & Downloads](https://www.vector.com/int/en/search/?tx_solr%5Bfilter%5D%5B0%5D=contentType%3Atx_solr_file&tx_solr%5Bsort%5D=datetime+desc&tx_solr%5BresultsPerPage%5D=10) - Over 1000 great materials: webinars, articles ...
- [Vector Knowledge Base](https://kb.vector.com/) - Vector platform with examples and solutions for problems related to offered products
- [Vector Consulting Services <img src="media/icons/video.png" width="18"/>](https://www.youtube.com/channel/UC-yhIPWuNcXm-DRPPsC8wiA/featured)
- [TOP 100 OEM suppliers](https://www.autonews.com/assets/PDF/CA89220617.PDF)
- [Information Post](https://automotive.softing.com/en/service/order-of-information-poster.html) -  Softing Automotive information posters relatd to Vehicle Diagnostic



## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Marcin has waived all copyright and
related or neighboring rights to this work.
