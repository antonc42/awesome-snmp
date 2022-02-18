<!--lint disable double-link-->
# Awesome SNMP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!-- TODO: Enable the badge when the repository is mature enough, older than 30 days. -->
<!-- [![Awesome lint](https://github.com/eozer/awesome-snmp/actions/workflows/awesome-lint.yml/badge.svg)](https://github.com/eozer/awesome-snmp/actions/workflows/awesome-lint.yml) -->

Simple Network Management Protocol (SNMP) is an Internet Standard protocol for collecting and organizing information about managed devices on IP networks and for modifying that information to change device behaviour.

This is a curated list of awesome SNMP libraries, tools, and other resources. Contributions are welcome!


## Contents
- [Libraries](#libraries)
- [Tools](#tools)
- [Publications](#publications)
- [Miscellaneous](#miscellaneous)


## Libraries
_Helpful to write SNMP applications._

### C/C++
- [net-snmp](http://www.net-snmp.org/) - A suite of software for using and deploying the SNMP protocol (v1, v2c and v3 and the AgentX subagent protocol). Contains also Python bindings.
- [SNMP++](https://www.agentpp.com/api/cpp/snmp_pp.html) - BSD licensed SNMP implemention from HP. Supports SNMP v1/2c/v3, thread-safety, and many more.
- [AGENT++](https://www.agentpp.com/api/cpp/agent_pp.html) - The AGENT++ C++ framework provides a complete tri-lingual SNMP v1/2c/3 protocol engine and dispatcher for the development of SNMP agents. Apache licensed.
- [AgentX++](https://www.agentpp.com/api/cpp/agentx_pp.html) - The AgentX++ C++ framework provides a complete AgentX protocol (RFC 2741) implementation that adds AgentX master and sub-agent support to AGENT++ (`Commercial`).
- [openSNMP](https://sourceforge.net/projects/opensnmp/) - BSD licensed multi-threaded implementation of SNMPv3.

### C#
- [sharpSNMP](https://github.com/lextudio/sharpsnmplib) - MIT licensed SNMP library for .NET/Xamarin/Mono.
- [SnmpSharpNet](https://github.com/rqx110/SnmpSharpNet) - Simple Network Management Protocol (SNMP) .Net library written in C# (csharp). Implements protocol version 1, 2 and 3.

### Erlang
- [Erlang/OTP SNMP](https://www.erlang.org/doc/apps/snmp/users_guide.html) - SNMP development is included as a component of the Erlang/Open Telecom Platform development environment.

### Go
- [gosnmp/gosnmp](https://github.com/gosnmp/gosnmp) - An SNMP library written in Go. It provides Get, GetNext, GetBulk, Walk, BulkWalk, Set and Traps. It supports IPv4/IPv6, using SNMP v1/v2c/v3.
- [sleepinggenius2/gosmi)](https://github.com/sleepinggenius2/gosmi) - MIB parser in Go language.
- [posteo/go-agentx](https://github.com/posteo/go-agentx) - A library with a pure Go implementation of the AgentX-Protocol.

### Java
- [SNMP4J](https://www.agentpp.com/api/java/snmp4j.html) - SNMP4J is an enterprise class, free open source, and state-of-the-art SNMP v1/2c/v3 implementation for Java™.
- [SNMP4J-Agent](https://www.agentpp.com/api/java/snmp4jagent.html) - SNMP4J-Agent is a Java™ API on top of the core SNMP4J API for the development of SNMP agents (command responders).
- [joeSNMP](https://sourceforge.net/projects/joesnmp/) - joeSNMP is an open-source Java SNMP class library published under the LGPL.
- [Westhawk's SNMP](https://snmp.westhawk.co.uk/) - An open-sourced Java library that can be used for SNMP v1/v2c/v3. Supports traps, authentication and privacy. As authentication protocols it offers MD5 and SHA1.
- [mibble](https://github.com/cederberg/mibble) - Mibble is an open-source SNMP MIB (or SMI) parser library for Java.

### JavaScript
- [node-net-snmp](https://github.com/markabrahams/node-net-snmp) -  JavaScript implementation of the Simple Network Management Protocol (SNMP), implements versions 1, 2c and 3.
- [node-snmp-native](https://github.com/calmh/node-snmp-native) -  Native JavaScript SNMP library for Node.js.
- [node-snmpjs](https://github.com/joyent/node-snmpjs) - This package provides a toolkit for SNMP agents and management applications in Node.js.
- [snmp-node](https://github.com/neias/snmp-node) - Native JavaScript SNMP library for Node.js.

### PHP
- [SNMP](https://github.com/FreeDSx/SNMP) - A Pure PHP SNMP Library.

### Python
- [pysnmp](https://github.com/etingof/pysnmp) - This is a pure-Python, open source and free implementation of v1/v2c/v3 SNMP engine distributed under 2-clause BSD license.
- [pysmi](https://github.com/etingof/pysmi) - PySMI is a pure-Python implementation of SNMP SMI MIB parser.
- [net-snmp Python bindings](http://www.net-snmp.org/wiki/index.php/Python_Bindings) - Net-SNMP 5.4 and later contains Python bindings in the "python" sub-directory, though, they are not built by default.
- [puresnmp](https://github.com/exhuma/puresnmp) - Pure Python3 SNMPv2 library without any dependencies.
- [snimpy](https://github.com/vincentbernat/snimpy) - Snimpy is a Python-based tool providing a simple interface to build SNMP query.
- [python-netsnmpagent](https://github.com/pief/python-netsnmpagent) - This package allows to write net-snmp subagents in Python.
- [hnmp](https://github.com/trehn/hnmp) - HNMP is a high-level Python library to ease the pain of retrieving and processing data from SNMP-capable devices such as network switches, routers, and printers.
- [aiosnmp](https://github.com/hh-h/aiosnmp) - Python package aiosnmp is an asynchronous SNMP client for use with asyncio. Only SNMP v2c is supported.
- [robotframework-snmplibrary](https://github.com/kontron/robotframework-snmplibrary) - SNMPLibrary is a Robot Framework test library for testing SNMP.

### Ruby
- [ruby-netsnmp](https://github.com/swisscom/ruby-netsnmp) - SNMP library in ruby (v1, v2c, v3).

### Rust
- [snmp-parser](https://github.com/rusticata/snmp-parser) - SNMP parser written in rust with nom parser combinator framework.
- [davedufresne/modern_snmp](https://github.com/davedufresne/modern_snmp) - Modern SNMP is a pure-Rust library for SNMPv3. This repository includes snmp_mp (SNMPv3 Message Processing) and snmp_usm (Implementation of the User-based Security Model (USM) for SNMPv3) crates.
- [Svedrin/sunt](https://github.com/Svedrin/sunt) - This repository implements an SNMP Agent written in Rust.

**[⬆ back to top](#contents)**


## Tools
_You use these to work with SNMP easier._

### CLIs
- [net-snmp tools](http://www.net-snmp.org/) - The applications listed here are part of net-snmp.
  - [encode_keychange](http://www.net-snmp.org/docs/man/encode_keychange.html) - Produces the KeyChange string for SNMPv3.
  - [snmptranslate](http://www.net-snmp.org/docs/man/snmptranslate.html) - Translates MIB OID names between numeric and textual forms.
  - [snmpget](http://www.net-snmp.org/docs/man/snmpget.html) - Communicates with a network entity using SNMP GET requests.
  - [snmpgetnext](http://www.net-snmp.org/docs/man/snmpgetnext.html) - Communicates with a network entity using SNMP GETNEXT requests.
  - [snmpbulkget](http://www.net-snmp.org/docs/man/snmpbulkget.html) - Communicates with a network entity using SNMP GETBULK requests.
  - [snmpwalk](http://www.net-snmp.org/docs/man/snmpwalk.html) - Retrieves a subtree of management values using SNMP GETNEXT requests.
  - [snmpbulkwalk](http://www.net-snmp.org/docs/man/snmpbulkwalk.html) - Retrieves a subtree of management values using SNMP GETBULK requests.
  - [snmpset](http://www.net-snmp.org/docs/man/snmpset.html) - Communicates with a network entity using SNMP SET requests.
  - [snmptest](http://www.net-snmp.org/docs/man/snmptest.html) - Communicates with a network entity using SNMP requests.
  - [snmptable](https://net-snmp.sourceforge.io/docs/man/snmptable.html) - Retrieve an SNMP table and display it in tabular form.
  - [snmpdelta](https://net-snmp.sourceforge.io/docs/man/snmpdelta.html) - Monitor delta differences in SNMP Counter values.
  - [snmpusm](http://www.net-snmp.org/docs/man/snmpusm.html) - Manipulates the SNMPv3 User-based-security user table.
  - [snmpvacm](http://www.net-snmp.org/docs/man/snmpvacm.html) - Manipulates the SNMPv3 View-based-access-control-module configuration tables.
  - [snmpstatus](https://net-snmp.sourceforge.io/docs/man/snmpstatus.html) - Retrieves a fixed set of management information from a network entity
  - [snmpnetstat](https://net-snmp.sourceforge.io/docs/man/snmpnetstat.html) - Display networking status and configuration information from a network entity via SNMP.
  - [snmpdf](http://www.net-snmp.org/docs/man/snmpdf.html) - Displays disk information like the unix df tool using information collected from SNMP.
  - [snmptrap](http://www.net-snmp.org/docs/man/snmptrap.html) - Sends SNMP TRAP or INFORM notification messages.
  - [snmptrapd](http://www.net-snmp.org/docs/man/snmptrapd.html) - An SNMP daemon that listens for SNMP TRAPs or INFORMs and logs or acts upon them.
  - [traptoemail](https://net-snmp.sourceforge.io/docs/man/traptoemail.html) - This an snmptrapd handler script to convert snmp traps into emails.
  - [net-snmp-config](https://net-snmp.sourceforge.io/docs/man/net-snmp-config.html) - Returns information about installed net-snmp libraries and binaries.
  - [snmpconf](https://net-snmp.sourceforge.io/docs/man/snmpconf.html) - Creates and modifies SNMP configuration files.
  - [fixproc](https://net-snmp.sourceforge.io/docs/man/fixproc.html) - Fixes a process by performing the specified action.
  - [snmpd](http://www.net-snmp.org/docs/man/snmpd.html) - An SNMP agent that responds to SNMP requests for a given host.
  - [mib2c](https://net-snmp.sourceforge.io/docs/man/mib2c.html) - A MIB conversion utility that can translate MIB structures into other forms, such as C-code.
  - [mib2c-update](https://net-snmp.sourceforge.io/docs/man/mib2c-update.html) - This a script to merge custom code into updated mib2c code.
- [SNMP4JCLT](https://www.agentpp.com/tools/snmp4jclt.html) - Use the SNMP4J Command Line Tool (CLT) to send SNMPv1/v2c/v3 requests and traps to a target with IPv4 or v6 based UDP, TCP, or TLSv1,2 transport (`Commercial`).
- [libsmi tools](https://www.ibr.cs.tu-bs.de/projects/libsmi/) - Applications built on top of libsmi and an sh/awk script that are integrated with the libsmi distribution.
  - [smilint](https://www.ibr.cs.tu-bs.de/projects/libsmi/smilint.html) - This is used to check MIB or PIB modules for syntax errors and semantics at some degree. SMIv1/v2 style MIB modules as well as SPPI PIB modules are supported.
  - [smidump](https://www.ibr.cs.tu-bs.de/projects/libsmi/smidump.html) - This is a MIB/PIB compiler. It allows to dump the contents of a module in various formats: SMIv1, SMIv2, SMIng, SPPI, Import Trees, Type Definition Trees, OID Node Trees, MOSY Style, and CORBA IDL definitions according to the JIDM Specs, and others.
  - [smidiff](https://www.ibr.cs.tu-bs.de/projects/libsmi/smidiff.html) - This is a tool that parses two revisions of a MIB module and analyzes the modifications from the old to the new revision.
  - [smiquery](https://www.ibr.cs.tu-bs.de/projects/libsmi/smiquery.html) - This is a MIB/PIB query front end. It can be used to query single items from the command line.
  - [smistrip](https://www.ibr.cs.tu-bs.de/projects/libsmi/smistrip.html) - This is a simple shell/awk script that allows to extract MIB and PIB modules from documents, such as RFCs or Internet Drafts.
- [snmpsim](https://github.com/etingof/snmpsim) - This is a pure-Python, open source and free implementation of SNMP agents simulator distributed under 2-clause BSD license.
- [snmpfwd](https://github.com/etingof/snmpfwd) - The SNMP Proxy Forwarder tool works as an application-level proxy with a built-in SNMP message router. Typical use case for an SNMP proxy is to work as an application-level firewall or a protocol translator that enables SNMPv3 access to a SNMPv1/SNMPv2c entity or vice versa.
- [snmpclitools](https://github.com/etingof/snmpclitools) - This is a collection of command-line SNMP tools written in pure-Python. The tools mimic their famous Net-SNMP counterparts. It includes snmpget.py, snmpset.py, snmpwalk.py, snmpbulkwalk.py, snmptrap.py, and snmptranslate.py, see [here](https://snmplabs.thola.io/snmpclitools/) for more details.
- [snmpwn](https://github.com/hatlord/snmpwn) - SNMPwn is an SNMPv3 user enumerator and attack tool.
- [trapperkeeper](https://github.com/dropbox/trapperkeeper) - A suite of tools for ingesting and displaying SNMP traps. This is designed as a replacement for snmptrapd and to supplement existing stateful monitoring solutions.

### GUIs
- [tkmib](http://www.net-snmp.org/) - A perl/Tk interactive graphical MIB browser for SNMP.
- [agentpp/MIB Designer](https://www.agentpp.com/tools/mibdesigner.html) - Use MIB Designer to create, edit, manage, and explore SMI specifications (`Commercial`).
- [agentpp/MIB Explorer Pro](https://www.agentpp.com/tools/mibexplorer.html) - Use MIB Explorer to browse, configure, test&debug, monitor, and discover SNMPv1/2c/3 entities.
- [sharpsnmp/SNMP Pro](https://www.sharpsnmp.com/) - A family of .NET based SNMP products, including the commercial MIB Compiler, MIB Assembly, and the open source Library.
- [paessler/snmptester](https://www.paessler.com/tools/snmptester) - This tool enables you to debug SNMP activities to find communication and/or data issues in SNMP monitoring configurations. Windows.
- [ireasoning/MIB Browser](http://ireasoning.com/mibbrowser.shtml) - This tool allows users to load standard, proprietary MIBs, and even some mal-formed MIBs. It also allows them to issue SNMP requests to retrieve agent's data, or make changes to the agent. Free for personal use.

**[⬆ back to top](#contents)**


## Publications
_How-to's, tutorials, blog posts, documentation and books._

### Books
- [Mauro, D. and Schmidt, K., 2005. Essential SNMP: Help for System and Network Administrators. " O'Reilly Media, Inc.".](https://www.amazon.com/Essential-SNMP-System-Network-Administrators-ebook/dp/B0043EWUZ2) - Essential SNMP explores both commercial and open source packages, and elements like OIDs, MIBs, community strings, and traps are covered in depth. The book contains five new chapters and various updates throughout
- [Perkins, D. and McGinnis, E., 1997. Understanding SNMP MIBs (p. 528). Englewood Cliffs: Prentice Hall PTR.](https://www.amazon.com/Understanding-SNMP-MIBs-David-Perkins/dp/0134377087) - The first complete, practical insider's guide to writing SNMP MIBs.
- [The Networknomicon, or SNMP Mastery by Abdul Alhazred and Michael W. Lucas](https://mwl.io/nonfiction/networking#networknomicon) - The Simple Network Management Protocol, SNMP, empowers you to invoke ancient standards from the void. SNMP exposes the secrets of your network and servers, and--if you're careless--reconfigures them into unspeakable nightmares. It exposes your inadequate brain to the vast alien dimensions underlying modern computing.
- [SNMP Mastery by Michael W. Lucas](https://mwl.io/nonfiction/networking#snmp) - SNMP, Simple Network Management Protocol, Four lies in one acronym?

### RFCs
- [rfc1098](https://tools.ietf.org/rfc/rfc1098.txt) - A Simple Network Management Protocol (version 1).
- [rfc1155](https://tools.ietf.org/rfc/rfc1155.txt) - Structure and Identification of Management Information.
- [rfc2578](https://tools.ietf.org/rfc/rfc2578.txt) - Structure of Management Information Version 2 (SMIv2).
- [rfc2741](https://tools.ietf.org/rfc/rfc2741.txt) - Agent Extensibility (AgentX) Protocol Version 1.
- [rfc2742](https://tools.ietf.org/rfc/rfc2742.txt) - Definitions of Managed Objects for Extensible SNMP Agents.
- [rfc3410](https://tools.ietf.org/rfc/rfc3410.txt) - Introduction and Applicability Statements for Internet Standard Management Framework.
- [rfc3411](https://tools.ietf.org/rfc/rfc3411.txt) - An Architecture for Describing Simple Network Management Protocol (SNMP) Management Frameworks.
- [rfc3412](https://tools.ietf.org/rfc/rfc3412.txt) - Message Processing and Dispatching for the Simple Network Management Protocol (SNMP).
- [rfc3413](https://tools.ietf.org/rfc/rfc3413.txt) - Simple Network Management Protocol (SNMP) Applications.
- [rfc3414](https://tools.ietf.org/rfc/rfc3414.txt) - User-based Security Model (USM) for version 3 of the
 Simple Network Management Protocol (SNMPv3).
- [rfc3415](https://tools.ietf.org/rfc/rfc3415.txt) - View-based Access Control Model (VACM) for the Simple Network Management Protocol (SNMP).
- [rfc3416](https://tools.ietf.org/rfc/rfc3416.txt) - Version 2 of the Protocol Operations for the Simple
Network Management Protocol (SNMP).
- [rfc3417](https://tools.ietf.org/rfc/rfc3417.txt) - Transport Mappings for the Simple Network Management
Protocol (SNMP).
- [rfc3418](https://www.ietf.org/rfc/rfc3418.txt) - Management Information Base (MIB) for the Simple Network Management Protocol (SNMP).
- [rfc3584](https://tools.ietf.org/rfc/rfc3584.txt) - Coexistence between Version 1, Version 2, and Version 3 of the Internet-standard Network Management Framework.
- [rfc3826](https://tools.ietf.org/rfc/rfc3826.txt) - The Advanced Encryption Standard (AES) Cipher Algorithm
in the SNMP User-based Security Model.
- [rfc4088](https://tools.ietf.org/rfc/rfc4088.txt) - Uniform Resource Identifier (URI) Scheme for the Simple Network Management Protocol (SNMP).
- [rfc5343](https://www.rfc-editor.org/rfc/rfc5343.txt) - Simple Network Management Protocol (SNMP) Context EngineID Discovery.
- [rfc5590](https://www.rfc-editor.org/rfc/rfc5590.txt) - Transport Subsystem for the Simple Network Management Protocol (SNMP).
- [rfc5591](https://www.rfc-editor.org/rfc/rfc5591.txt) - Transport Subsystem for the Simple Network Management Protocol (SNMP).
- [rfc5592](https://www.rfc-editor.org/rfc/rfc5592.txt) - Secure Shell Transport Model for the Simple Network Management Protocol (SNMP).
- [rfc7630](https://www.rfc-editor.org/rfc/rfc7630.txt) - HMAC-SHA-2 Authentication Protocols in the User-based Security Model (USM) for SNMPv3.

### Tutorials
- [net-snmp tutorials](http://www.net-snmp.org/wiki/index.php/Tutorials) - This Wiki page contains various tutorials ranging from the basics of SNMP protocol to implementation of SNMP applications and agents using net-snmp library.

**[⬆ back to top](#contents)**

## Miscellaneous
_Items that belong on the list but difficult to classify._

- [Prometheus SNMP Exporter](https://github.com/prometheus/snmp_exporter) - This exporter is the recommended way to expose SNMP data in a format which Prometheus can ingest.
- [hsnodgrass/snmp_mib_archive](https://github.com/hsnodgrass/snmp_mib_archive) - An archive of over 3000 unique SNMP MIBs.
- [kcsinclair/mibs](https://github.com/kcsinclair/mibs) - Another collection of MIBS used for SNMP. Make sure to clone the repository to see the full list of MIBs.

**[⬆ back to top](#contents)**

## Contributing
Please take a quick look at the [contribution guidelines](contributing.md) first. Thank you to all contributors.

