![](https://raw.githubusercontent.com/mesquidar/ForensicsTools/master/FORENSICS%20TOOLS.png)

# Awesome Forensics Tools with stars

A list of free and open source forensics analysis tools and other resources.

* [Forensics Tools](#forensics-tools)
* [Collections](#collections)
* [Tools](#tools)
  * [Distributions](#distributions)
  * [Frameworks](#frameworks)
  * [Live forensics](#live-forensics)
  * [Acquisition](#acquisition)
  * [Imageing](#imageing)
  * [Carving](#carving)
  * [Memory Forensics](#memory-forensics)
  * [Network Forensics](#network-forensics)
  * [Windows Artifacts](#windows-artifacts)
    * [NTFS/MFT Processing](#ntfsmft-processing)
  * [OS X Forensics](#os-x-forensics)
  * [Mobile Forensics](#mobile-forensics)
  * [Docker Forensics](#docker-forensics)
  * [Browser Artifacts](#browser-artifacts)
  * [Timeline Analysis](#timeline-analysis)
  * [Disk image handling](#disk-image-handling)
  * [Decryption](#decryption)
  * [Management](#management)
  * [Picture Analysis](#picture-analysis)
  * [Steganography](#steganography)
  * [Metadata Forensics](#metadata-forensics)
  * [Website Forensics](#website-forensics)
* [Learn Forensics](#learn-forensics)
  * [CTFs](#challenges)
* [Resources](#resources)
  * [Books](#books)
  * [File System Corpora](#file-system-corpora)
  * [Twitter](#twitter)
  * [Blogs](#blogs)
  * [Other](#other)
* [Related Awesome Lists](#related-awesome-lists)

## Collections

* :star: [ForensicArtifacts.com Artifact Repository](https://github.com/ForensicArtifacts/artifacts) ⭐ 1,261 | 🐛 44 | 🌐 Python | 📅 2026-07-31 - Machine-readable knowledge base of forensic artifacts
* [DFIR-SQL-Query-Repo](https://github.com/abrignoni/DFIR-SQL-Query-Repo) ⭐ 118 | 🐛 1 | 📅 2021-04-17 - Collection of SQL queries templates for digital forensics use by platform and application.
* [DFIR – The definitive compendium project](https://aboutdfir.com) - Collection of forensic resources for learning and research. Offers lists of certifications, books, blogs, challenges and more
* [dfir.training](https://www.dfir.training/) - Database of forensic resources focused on events, tools and more

## Tools

* [Forensics tools on Wikipedia](https://en.wikipedia.org/wiki/List_of_digital_forensics_tools)
* [Eric Zimmerman's Tools](https://ericzimmerman.github.io/#!index.md)

## Challenges

* [Blue Team Labs Online](https://blueteamlabs.online/)

### Distributions

* :star:[SANS Investigative Forensics Toolkit (sift)](https://github.com/teamdfir/sift) ⭐ 550 | 🐛 19 | 📅 2024-02-14 - Linux distribution for forensic analysis
* [bitscout](https://github.com/vitaly-kamluk/bitscout) ⭐ 479 | 🐛 0 | 🌐 Shell | 📅 2025-03-21 - LiveCD/LiveUSB for remote forensic acquisition and analysis
* [CAINE](https://www.caine-live.net/)
* [GRML-Forensic](https://grml-forensic.org/)
* [Remnux](https://remnux.org/) - Distro for reverse-engineering and analyzing malicious software
* [Santoku Linux](https://santoku-linux.com/) - Santoku is dedicated to mobile forensics, analysis, and security, and packaged in an easy to use, Open Source platform.
* [Sumuri Paladin](https://sumuri.com/software/paladin/) - Linux distribution that simplifies various forensics tasks in a forensically sound manner via the PALADIN Toolbox
* [Tsurugi Linux](https://tsurugi-linux.org/) - Linux distribution for forensic analysis
* [WinFE](https://www.winfe.net/home) - Windows Forensics enviroment
* [Predator OS](http://predator-os.ir/) - Linux distribution for forensic analysis

### Frameworks

* :star: [The Sleuth Kit](https://github.com/sleuthkit/sleuthkit) ⭐ 3,129 | 🐛 475 | 🌐 C | 📅 2026-08-17 - Tools for low level forensic analysis
* [IPED - Indexador e Processador de Evidências Digitais](https://github.com/sepinf-inc/IPED) ⭐ 2,680 | 🐛 370 | 🌐 Java | 📅 2026-08-14 - Brazilian Federal Police Tool for Forensic Investigations
* [PowerForensics](https://github.com/Invoke-IR/PowerForensics) ⭐ 1,442 | 🐛 64 | 🌐 C# | 📅 2023-11-16 - PowerForensics is a framework for live disk forensic analysis
* [IntelMQ](https://github.com/certtools/intelmq) ⭐ 1,132 | 🐛 253 | 🌐 Python | 📅 2026-04-28 - IntelMQ collects and processes security feeds
* [Kuiper](https://github.com/DFIRKuiper/Kuiper) ⭐ 901 | 🐛 12 | 🌐 JavaScript | 📅 2024-10-12 - Digital Investigation Platform
* [turbinia](https://github.com/google/turbinia) ⭐ 792 | 🐛 103 | 🌐 Python | 📅 2026-08-09 - Turbinia is an open-source framework for deploying, managing, and running forensic workloads on cloud platforms
* [Laika BOSS](https://github.com/lmco/laikaboss) ⭐ 753 | 🐛 26 | 🌐 Python | 📅 2024-12-16 - Laika is an object scanner and intrusion detection system
* [dff](https://github.com/arxsys/dff) ⭐ 315 | 🐛 21 | 🌐 Python | 📅 2020-02-13 - Forensic framework
* [RegRippy](https://github.com/airbus-cert/regrippy) ⭐ 217 | 🐛 2 | 🌐 Python | 📅 2026-05-12 - is a framework for reading and extracting useful forensics data from Windows registry hives.
* [dexter](https://github.com/coinbase/dexter) ⭐ 127 | 🐛 9 | 🌐 Go | 📅 2019-06-21 - Dexter is a forensics acquisition framework designed to be extensible and secure
* :star:[Autopsy](http://www.sleuthkit.org/autopsy/) - SleuthKit GUI

### Live forensics

* [osquery](https://github.com/osquery/osquery) ⭐ 23,469 | 🐛 620 | 🌐 C++ | 📅 2026-08-13 - SQL powered operating system analytics
* [grr](https://github.com/google/grr) ⭐ 5,088 | 🐛 191 | 🌐 Python | 📅 2026-05-12 - GRR Rapid Response: remote live forensics for incident response
* [mig](https://github.com/mozilla/mig) ⚠️ Archived - Distributed & real time digital forensics at the speed of the cloud
* [Linux Expl0rer](https://github.com/intezer/linux-explorer) ⚠️ Archived - Easy-to-use live forensics toolbox for Linux endpoints written in Python & Flask

### Acquisition

* [Velociraptor](https://github.com/Velocidex/velociraptor) ⭐ 4,182 | 🐛 71 | 🌐 Go | 📅 2026-08-17 - Velociraptor is a tool for collecting host based state information using Velocidex Query Language (VQL) queries
* [LiME](https://github.com/504ensicsLabs/LiME) ⭐ 2,028 | 🐛 35 | 🌐 C | 📅 2026-04-05 - Loadable Kernel Module (LKM), which allows the acquisition of volatile memory from Linux and Linux-based devices, formerly called DMD
* [AVML](https://github.com/microsoft/avml) ⭐ 1,118 | 🐛 6 | 🌐 Rust | 📅 2026-08-17 - A portable volatile memory acquisition tool for Linux
* [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector) ⭐ 521 | 🐛 11 | 🌐 Python | 📅 2021-01-26 - Collect artifacts on windows
* [UFADE](https://github.com/prosch88/UFADE) ⭐ 507 | 🐛 3 | 🌐 Python | 📅 2026-07-29 - Extract files from Apple devices on Windows, Linux and MacOS. Mostly a wrapper for pymobiledevice3. Creates iTunes-style backups and "advanced logical backups"
* [artifactcollector](https://github.com/forensicanalysis/artifactcollector) ⚠️ Archived - A customizable agent to collect forensic artifacts on any Windows, macOS or Linux system
* [Fuji](https://github.com/Lazza/Fuji) ⭐ 295 | 🐛 6 | 🌐 Python | 📅 2026-06-02 - Graphical interface for the forensic logical acquisition of Mac computers
* [ArtifactExtractor](https://github.com/Silv3rHorn/ArtifactExtractor) ⭐ 65 | 🐛 1 | 🌐 Python | 📅 2021-05-10 - Extract common Windows artifacts from source images and VSCs
* [DFIR ORC](https://dfir-orc.github.io/) - Forensics artefact collection tool for systems running Microsoft Windows
* [DumpIt](https://www.comae.com/dumpit/) -
* [FireEye Memoryze](https://www.fireeye.com/services/freeware/memoryze.html)
* [Magnet RAM Capture](https://www.magnetforensics.com/resources/magnet-ram-capture/) - is a free imaging tool designed to capture the physical memory
* :star:[RAM Capturer](https://belkasoft.com/ram-capturer) - by Belkasoft is a free tool to dump the data from a computer’s volatile memory. It’s compatible with Windows OS.

### Imageing

* :star:[BelkaImager](https://belkasoft.com/es/bat) - by Belkasoft  allows you to create images of hard and removable disks, Android and iOS devices and download data from the cloud.
* [dc3dd](https://sourceforge.net/projects/dc3dd/) - Improved version of dd
* [dcfldd](http://dcfldd.sourceforge.net) - Different improved version of dd (this version has some bugs!, another version is on github [adulau/dcfldd](https://github.com/adulau/dcfldd) ⭐ 75 | 🐛 2 | 🌐 C | 📅 2018-06-17)
* [FTK Imager](https://accessdata.com/product-download/ftk-imager-version-3-4-3/) - Free imageing tool for windows
* :star:[Guymager](https://guymager.sourceforge.io/) - Open source version for disk imageing on linux systems

### Carving

* [floss](https://github.com/fireeye/flare-floss) ⭐ 4,122 | 🐛 118 | 🌐 Python | 📅 2026-08-17 - Static analysis tool to automatically deobfuscate strings from malware binaries
* [bulk\_extractor](https://github.com/simsong/bulk_extractor) ⭐ 1,407 | 🐛 76 | 🌐 C++ | 📅 2026-08-17 - Extracts informations like email adresses, creditscard numbers and histrograms of disk images
* [swap\_digger](https://github.com/sevagas/swap_digger) ⭐ 536 | 🐛 1 | 🌐 Shell | 📅 2021-06-26 - A bash script used to automate Linux swap analysis, automating swap extraction and searches for Linux user credentials, Web form credentials, Web form emails, etc.
* [bstrings](https://github.com/EricZimmerman/bstrings) ⭐ 151 | 🐛 0 | 🌐 C# | 📅 2026-04-26 - Improved strings utility
* :star: [photorec](https://www.cgsecurity.org/wiki/PhotoRec) - File carving tool

### Memory Forensics

* :star:[volatility](https://github.com/volatilityfoundation/volatility) ⚠️ Archived - The memory forensic framework
* [MemProcFS](https://github.com/ufrisk/MemProcFS) ⭐ 4,288 | 🐛 9 | 🌐 C | 📅 2026-08-17 - An easy and convenient way of accessing physical memory as files a virtual file system.
* [Rekall](https://github.com/google/rekall) ⚠️ Archived - Memory Forensic Framework
* [KeeFarce](https://github.com/denandz/KeeFarce) ⭐ 1,029 | 🐛 4 | 🌐 C++ | 📅 2015-11-17 - Extract KeePass passwords from memory
* [MemPrcFs Analyzer](https://github.com/LETHAL-FORENSICS/MemProcFS-Analyzer) ⭐ 729 | 🐛 0 | 🌐 PowerShell | 📅 2026-05-02 - PowerShell script utilized to simplify the usage of MemProcFS and to optimize your memory analysis workflow.
* [VolUtility](https://github.com/kevthehermit/VolUtility) ⭐ 387 | 🐛 40 | 🌐 Python | 📅 2026-01-13 - Web App for Volatility framework
* [inVtero.net](https://github.com/ShaneK2/inVtero.net) ⭐ 296 | 🐛 2 | 🌐 C# | 📅 2023-09-30 - High speed memory analysis framework
  developed in .NET supports all Windows x64, includes code integrity and write support
* [FireEye RedLine](https://www.fireeye.com/services/freeware/redline.html) - provides host investigative capabilities to users to find signs of malicious activity through memory and file analysis and the development of a threat assessment profile.

### Network Forensics

* [NetworkMiner](https://www.netresec.com/?page=Networkminer)
* [Xplico](https://www.xplico.org/)
* :star:[WireShark](https://www.wireshark.org/)

### Windows Artifacts

* [LogonTracer](https://github.com/JPCERTCC/LogonTracer) ⭐ 3,211 | 🐛 21 | 🌐 Python | 📅 2026-08-02 - Investigate malicious Windows logon by visualizing and analyzing Windows event log
* [Beagle](https://github.com/yampelo/beagle) ⭐ 1,350 | 🐛 44 | 🌐 Python | 📅 2022-12-13 -  Transform data sources and logs into graphs
* [RegRipper3.0](https://github.com/keydet89/RegRipper3.0) ⭐ 712 | 🐛 9 | 🌐 Perl | 📅 2026-05-27 - RegRipper is an open source Perl tool for parsing the Registry and presenting it for analysis.
* [python-evt](https://github.com/williballenthin/python-evt) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2023-06-30 - Pure Python parser for classic Windows Event Log files (.evt)
* [CrowdResponse](https://www.crowdstrike.com/resources/community-tools/crowdresponse/) - by CrowdStrike is a static host data collection tool
* [FRED](https://www.pinguin.lu/fred) - Cross-platform microsoft registry hive editor
* [LastActivityView](https://www.nirsoft.net/utils/computer_activity_view.html) - LastActivityView by Nirsoftis a tool for Windows operating system that collects information from various sources on a running system, and displays a log of actions made by the user and events occurred on this computer.

#### NTFS/MFT Processing

* [RecuperaBit](https://github.com/Lazza/RecuperaBit) ⭐ 622 | 🐛 35 | 🌐 Python | 📅 2026-07-26 - Reconstruct and recover NTFS data
* [NTFSTool](https://github.com/thewhiteninja/ntfstool) ⭐ 620 | 🐛 6 | 🌐 C++ | 📅 2026-06-26 - Complete NTFS forensics tool
* [NTFS USN Journal parser](https://github.com/PoorBillionaire/USN-Journal-Parser) ⭐ 119 | 🐛 4 | 🌐 Python | 📅 2022-07-15
* [python-ntfs](https://github.com/williballenthin/python-ntfs) ⭐ 86 | 🐛 4 | 🌐 Python | 📅 2017-12-22 - NTFS analysis
* [MFTExtractor](https://github.com/aarsakian/MFTExtractor) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2026-08-01 - MFT-Parser
* [MFT-Parsers](http://az4n6.blogspot.com/2015/09/whos-your-master-mft-parsers-reviewed.html) - Comparison of MFT-Parsers
* [NTFS journal parser](http://strozfriedberg.github.io/ntfs-linker/)

### Linux Forensics

-[FJTA - Forensic Journal Timeline Analyzer](https://github.com/mnrkbys/fjta) ⭐ 112 | 🐛 1 | 🌐 Python | 📅 2026-04-08 -  Tool that analyzes Linux filesystem (ext4, XFS) journals (not systemd-journald logs), generates timelines, and detects suspicious activities

### OS X Forensics

* [OSXAuditor](https://github.com/jipegit/OSXAuditor) ⭐ 3,135 | 🐛 8 | 🌐 JavaScript | 📅 2020-07-27
* [APFS Fuse](https://github.com/sgan81/apfs-fuse) ⭐ 2,135 | 🐛 124 | 🌐 C++ | 📅 2024-08-13 - is a read-only FUSE driver for the new Apple File System
* [OSX Collect](https://github.com/Yelp/osxcollector) ⚠️ Archived
* [mac\_apt (macOS Artifact Parsing Tool)](https://github.com/ydkhatri/mac_apt) ⭐ 1,075 | 🐛 8 | 🌐 Python | 📅 2026-07-23 - Extracts forensic artifacts from disk images or live machines
* [Disk-Arbitrator](https://github.com/aburgh/Disk-Arbitrator) ⭐ 714 | 🐛 30 | 🌐 Objective-C | 📅 2025-08-25 - is a Mac OS X forensic utility designed to help the user ensure correct forensic procedures are followed during imaging of a disk device
* [APOLLO](https://github.com/mac4n6/APOLLO) ⭐ 652 | 🐛 8 | 🌐 Python | 📅 2024-02-25
* [macMRUParser](https://github.com/mac4n6/macMRU-Parser) ⭐ 111 | 🐛 1 | 🌐 Python | 📅 2018-02-22 - Python script to parse the Most Recently Used (MRU) plist files on macOS into a more human friendly format.
* [MacLocationsScraper](https://github.com/mac4n6/Mac-Locations-Scraper) ⭐ 92 | 🐛 0 | 🌐 Python | 📅 2022-10-26 - Dump the contents of the location database files on iOS and macOS.
* [MacOs Collector](https://github.com/LETHAL-FORENSICS/macos-collector) ⭐ 49 | 🐛 0 | 🌐 Shell | 📅 2026-07-20 - Shell script utilized to collect macOS Forensic Artifacts from a compromised macOS endpoint
* [MacOs Analyzer Suite](https://github.com/LETHAL-FORENSICS/MacOS-Analyzer-Suite) ⭐ 34 | 🐛 0 | 🌐 PowerShell | 📅 2026-03-16 - A collection of PowerShell scripts for analyzing macOS Forensic Artifacts
* [MAC OSX Artifacts](https://docs.google.com/spreadsheets/d/1X2Hu0NE2ptdRj023OVWIGp5dqZOw-CfxHLOW_GNGpX8/edit#gid=1317205466) - locations artifacts by mac4n6 group

### Mobile Forensics

* [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) ⭐ 21,605 | 🐛 20 | 🌐 JavaScript | 📅 2026-08-17 - is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis.
* [Andriller](https://github.com/den4uk/andriller) ⭐ 1,596 | 🐛 11 | 🌐 Python | 📅 2022-06-27 - is software utility with a collection of forensic tools for smartphones. It performs read-only, forensically sound, non-destructive acquisition from Android devices
* [ALEAPP](https://github.com/abrignoni/ALEAPP) ⭐ 875 | 🐛 43 | 🌐 Python | 📅 2026-08-17 - An Android Logs Events and Protobuf Parser
* [OpenBackupExtractor](https://github.com/vgmoose/OpenBackupExtractor) ⭐ 191 | 🐛 7 | 🌐 Swift | 📅 2022-01-06 - is an app for extracting data from iPhone and iPad backups.
* [MEAT](https://github.com/jfarley248/MEAT) ⭐ 168 | 🐛 2 | 🌐 Python | 📅 2020-05-21 - Perform different kinds of acquisitions on iOS devices
* [iOS Frequent Locations Dumper](https://github.com/mac4n6/iOS-Frequent-Locations-Dumper) ⭐ 92 | 🐛 1 | 🌐 Python | 📅 2018-11-04 - Dump the contents of the StateModel#.archive files located in /private/var/mobile/Library/Caches/com.apple.routined/

### Docker Forensics

* [Docker Explorer](https://github.com/google/docker-explorer) ⚠️ Archived Extracts and interprets forensic artifacts from disk images of Docker Host systems
* [dof (Docker Forensics Toolkit)](https://github.com/docker-forensics-toolkit/toolkit) ⭐ 112 | 🐛 1 | 🌐 Python | 📅 2024-02-18 - Extracts and interprets forensic artifacts from disk images of Docker Host systems

### Browser Artifacts

* [hindsight](https://github.com/obsidianforensics/hindsight) ⭐ 1,486 | 🐛 7 | 🌐 Python | 📅 2026-08-09 - Internet history forensics for Google Chrome/Chromium
* [unfurl](https://github.com/obsidianforensics/unfurl) ⭐ 761 | 🐛 33 | 🌐 Python | 📅 2026-08-13 - Extract and visualize data from URLs
* [chrome-url-dumper](https://github.com/eLoopWoo/chrome-url-dumper) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2017-11-11 - Dump all local stored infromation collected by Chrome
* [mozdmp](https://github.com/asaix/mozdmp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - Offline profile decryption tool for Mozilla Firefox. Supports multi-core CPU-based cracking of the master password and the latest Firefox hash formats, including those not yet supported by Hashcat and JTR.
* [chrdmp](https://github.com/asaix/chrdmp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - Decrypt Chrome profile data offline using the Chrome Safe Storage keyring secret.
* [ChromeCacheView](https://www.nirsoft.net/utils/chrome_cache_view.html) - by Nirsoft is a small utility that reads the cache folder of Google Chrome Web browser, and displays the list of all files currently stored in the cache
* [Dumpzilla](http://www.dumpzilla.org/) - extract all forensic interesting information of Firefox, Iceweasel and Seamonkey browsers

### Timeline Analysis

* [timesketch](https://github.com/google/timesketch) ⭐ 3,391 | 🐛 217 | 🌐 Python | 📅 2026-08-09 - Collaborative forensic timeline analysis
* :star: [plaso](https://github.com/log2timeline/plaso) ⭐ 2,137 | 🐛 281 | 🌐 Python | 📅 2026-08-03 - Extract timestamps from various files and aggregate them
* [DFTimewolf](https://github.com/log2timeline/dftimewolf) ⭐ 352 | 🐛 6 | 🌐 Python | 📅 2026-08-17 - Framework for orchestrating forensic collection, processing and data export using GRR and Rekall
* [timeliner](https://github.com/airbus-cert/timeliner) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2024-08-05 - A rewrite of mactime, a bodyfile reader

### Disk image handling

* [Disk Arbitrator](https://github.com/aburgh/Disk-Arbitrator) ⭐ 714 | 🐛 30 | 🌐 Objective-C | 📅 2025-08-25 - A Mac OS X forensic utility designed to help the user ensure correct forensic procedures are followed during imaging of a disk device
* [libewf](https://github.com/libyal/libewf) ⭐ 312 | 🐛 13 | 🌐 C | 📅 2026-07-16 - Libewf is a library and some tools to access the Expert Witness Compression Format (EWF, E01)
* [imagemounter](https://github.com/ralphje/imagemounter) ⭐ 127 | 🐛 6 | 🌐 Python | 📅 2023-02-09 - Command line utility and Python package to ease the (un)mounting of forensic disk images
* [PancakeViewer](https://github.com/forensicmatt/PancakeViewer) ⭐ 42 | 🐛 13 | 🌐 Python | 📅 2020-04-13 - Disk image viewer based in dfvfs, similar to the FTK Imager viewer.
* [OSFMount](https://www.osforensics.com/tools/mount-disk-images.html) - allows you to mount local disk image files (bit-for-bit copies of an entire disk or disk partition) in Windows as a physical disk or a logical drive
* [xmount](https://www.pinguin.lu/xmount) - Convert between different disk image formats

### Decryption

* [hashcat](https://hashcat.net/hashcat/) - Fast password cracker with GPU support
* [John the Ripper](https://www.openwall.com/john/) - Password cracker

### Management

* [dfirtrack](https://github.com/stuhli/dfirtrack) ⭐ 538 | 🐛 7 | 🌐 Python | 📅 2026-01-13 - Digital Forensics and Incident Response Tracking application, track systems
* [Incidents](https://github.com/veeral-patel/incidents) ⭐ 70 | 🐛 13 | 🌐 Ruby | 📅 2023-01-19 - Web application for organizing non-trivial security investigations. Built on the idea that incidents are trees of tickets, where some tickets are leads

### Picture Analysis

* [Ghiro](http://www.getghiro.org/) - is a fully automated tool designed to run forensics analysis over a massive amount of images
* [sherloq](https://github.com/GuidoBartoli/sherloq) ⭐ 3,184 | 🐛 25 | 🌐 Perl | 📅 2026-07-16 - An open-source digital photographic image forensic toolset

### Steganography

* [Binwalk](https://github.com/ReFirmLabs/binwalk) ⭐ 14,232 | 🐛 92 | 🌐 Rust | 📅 2026-08-11 - Binwalk is a fast, easy to use tool for analyzing, reverse engineering, and extracting firmware images.
* [Zsteg](https://github.com/zed-0xff/zsteg) ⭐ 1,609 | 🐛 6 | 🌐 Ruby | 📅 2026-01-28 - A steganographic coder for WAV files
* [Steghide](https://github.com/StefanoDeVuono/steghide) ⭐ 770 | 🐛 4 | 🌐 C++ | 📅 2024-02-20 - is a steganography program that hides data in various kinds of image and audio files
* [Foremost](https://github.com/korczis/foremost) ⭐ 372 | 🐛 6 | 🌐 C | 📅 2023-05-26 - is a program to recover files based on their headers and footers
* [Wavsteg](https://github.com/samolds/wavsteg) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2017-12-14 - is a steganography program that hides data in various kinds of image and audio files
* [Sonicvisualizer](https://www.sonicvisualiser.org)
* [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar) - analyze images in different planes by taking off bits of the image
* [Audacity](https://www.audacityteam.org) - an easy-to-use, multi-track audio editor and recorder

### Metadata Forensics

* [ExifTool](https://exiftool.org/) by Phil Harvey
* [Exiv2](https://www.exiv2.org) - Exiv2 is a Cross-platform C++ library and a command line utility to manage image metadata
* [FOCA](https://github.com/ElevenPaths/FOCA) ⭐ 3,617 | 🐛 26 | 🌐 C# | 📅 2022-12-08 - FOCA is a tool used mainly to find metadata and hidden information in the documents

### Website Forensics

* [Freezing Internet Tool](https://github.com/fit-project/fit) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2026-03-06 - Python 3 application for forensic acquisition of online content, including web pages, emails, and social media.
* [ScanMalware](https://scanmalware.com) - Scan websites for malicious behaviours and fingerprint JavaScripts.

## Learn forensics

* [Forensic challenges](https://www.amanhardikar.com/mindmaps/ForensicChallenges.html) - Mindmap of forensic challenges
* [OpenLearn](https://www.open.edu/openlearn/science-maths-technology/digital-forensics/content-section-0?active-tab=description-tab) - Digital forensic course
* [Training material](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/technical-operational) - Online training material by European Union Agency for Network and Information Security for different topics (e.g. [Digital forensics](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/technical-operational/#digital_forensics), [Network forensics](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/technical-operational/#network_forensics))

### Challenges

* [Forensics CTFs](https://github.com/apsdehal/awesome-ctf/blob/master/README.md#forensics) ⭐ 11,762 | 🐛 64 | 🌐 JavaScript | 📅 2024-07-22
* [MemLabs](https://github.com/stuxnet999/MemLabs) ⭐ 1,884 | 🐛 0 | 🌐 Shell | 📅 2021-03-08
* [AnalystUnknown Cyber Range](https://aucr.io/auth/login?next=%2F)
* [Champlain College DFIR CTF](https://champdfa-ccsc-sp20.ctfd.io)
* [Corelight CTF](https://www3.corelight.com/l/420832/2020-03-31/lcxk2q)
* [CyberDefenders](https://cyberdefenders.org)
* [DefCon CTFs](https://archive.ooo) - archive of DEF CON CTF challenges.
* [IncidentResponse Challenge](https://incident-response-challenge.com)
* [MagnetForensics CTF Challenge](https://www.magnetforensics.com/blog/magnet-weekly-ctf-challenge)
* [MalwareTech Challenges](https://www.malwaretech.com/challenges)
* [MalwareTraffic Analysis](https://www.malware-traffic-analysis.net/training-exercises.html)
* [NW3C Chanllenges](https://nw3.ctfd.io)
* [PivotProject](https://pivotproject.org/challenges/digital-forensics-challenge)
* [Precision Widgets of North Dakota Intrusion](https://betweentwodfirns.blogspot.com/2017/11/dfir-ctf-precision-widgets-of-north.html)
* [ReverseEngineering Challenges](https://challenges.re)
* [SANS Forensics Challenges](https://digital-forensics.sans.org/community/challenges)

## Resources

### Webs

* [ForensicsFocus](https://www.forensicfocus.com/)
* [InsecInstitute Resources](https://resources.infosecinstitute.com/)
* [SANS Digital Forensics](https://digital-forensics.sans.org/)

### Blogs

* [Cyberforensics](https://cyberforensics.com/blog/)
* [Cyberforensicator](https://cyberforensicator.com/)
* [DigitalForensicsMagazine](https://digitalforensicsmagazine.com/blogs/)
* [FlashbackData](https://www.flashbackdata.com/blog/)
* [Netresec](https://www.netresec.com/index.ashx?page=Blog)
* [roDigitalForensics](https://prodigital4n6.com/blog/)
* [SANS Forensics Blog](https://www.sans.org/blog/?focus-area=digital-forensics)
* [SecurityAffairs](https://securityaffairs.co/wordpress/) - blog by Pierluigi Paganini
* [thisweekin4n6.wordpress.com](thisweekin4n6.wordpress.com) - Weekly updates for forensics
* [Zena Forensics](https://blog.digital-forensics.it/)

### Books

*more at [Recommended Readings](http://dfir.org/?q=node/8) by Andrew Case*

* [Network Forensics: Tracking Hackers through Cyberspace](https://www.pearson.com/us/higher-education/program/Davidoff-Network-Forensics-Tracking-Hackers-through-Cyberspace/PGM322390.html) - Learn to recognize hackers’ tracks and uncover network-based evidence
* [The Art of Memory Forensics](https://www.memoryanalysis.net/amf) - Detecting Malware and Threats in Windows, Linux, and Mac Memory
* [The Practice of Network Security Monitoring](https://nostarch.com/nsm) - Understanding Incident Detection and Response
* [Cell Phone Investigations: Search Warrants, Cell Sites and Evidence Recovery](https://cryptome.org/2015/11/Cell-Phone-Investigations.pdf) - Cell Phone Investigations is the most comprehensive book written on cell phones, cell sites, and cell related data.

### File System Corpora

* [Digital Forensic Challenge Images](https://www.ashemery.com/dfir.html) - Two DFIR challenges with images
* [Digital Forensics Tool Testing Images](http://dftt.sourceforge.net)
* [FAU Open Research Challenge Digital Forensics](https://openresearchchallenge.org/digitalForensics/appliedforensiccomputinggroup)
* [The CFReDS Project](https://www.cfreds.nist.gov)
  * [Hacking Case (4.5 GB NTFS Image)](https://www.cfreds.nist.gov/Hacking_Case.html)

### Twitter

* [@4n6ist](https://twitter.com/4n6ist)
* [@aheadless](https://twitter.com/aheadless)
* [@AppleExaminer](https://twitter.com/AppleExaminer) - Apple OS X & iOS Digital Forensics
* [@blackbagtech](https://twitter.com/blackbagtech)
* [@carrier4n6](https://twitter.com/carrier4n6) - Brian Carrier, author of Autopsy and the Sleuth Kit
* [@CindyMurph](https://twitter.com/CindyMurph) - Detective & Digital Forensic Examiner
* [@EricRZimmerman](https://twitter.com/EricRZimmerman) - Certified SANS Instructor
* [@forensikblog](https://twitter.com/forensikblog) - Computer forensic geek
* [@HECFBlog](https://twitter.com/HECFBlog) - SANS Certified Instructor
* [@Hexacorn](https://twitter.com/Hexacorn) - DFIR+Malware
* [@hiddenillusion](https://twitter.com/hiddenillusion)
* [@iamevltwin](https://twitter.com/iamevltwin) - Mac Nerd, Forensic Analyst, Author & Instructor of SANS FOR518
* [@jaredcatkinson](https://twitter.com/jaredcatkinson) - PowerShell Forensics
* [@maridegrazia](https://twitter.com/maridegrazia) - Computer Forensics Examiner
* [@sleuthkit](https://twitter.com/sleuthkit)
* [@williballenthin](https://twitter.com/williballenthin)
* [@XWaysGuide](https://twitter.com/XWaysGuide)

### Other

* [ForensicPosters](https://github.com/Invoke-IR/ForensicPosters) ⭐ 453 | 🐛 3 | 📅 2024-11-21 - Posters of file system structures
* [mac4n6 Presentations](https://github.com/mac4n6/Presentations) ⭐ 265 | 🐛 0 | 📅 2025-03-18 - Presentation Archives for OS X and iOS Related Research
* [HFS+ Resources](https://github.com/mac4n6/HFSPlus_Resources) ⭐ 38 | 🐛 0 | 📅 2015-11-15
* [/r/computerforensics/](https://www.reddit.com/r/computerforensics/) - Subreddit for computer forensics
* [ForensicControl](https://www.forensiccontrol.com/free-software) -
* [SANS Forensics CheatSheets](https://digital-forensics.sans.org/community/cheat-sheets) - Different CheatSheets from SANS
* [SANS Digital Forensics Posters](https://digital-forensics.sans.org/community/posters) - Digital Forensics Posters from SANS
* [SANS WhitePapers](https://digital-forensics.sans.org/community/whitepapers) - White Papers written by forensic practitioners seeking GCFA, GCFE, and GREM Gold

## Related Awesome Lists

* [OSINT](https://github.com/jivoi/awesome-osint) ⭐ 28,144 | 🐛 6 | 📅 2026-08-17
* [Pentesting](https://github.com/enaqx/awesome-pentest) ⭐ 26,922 | 🐛 99 | 📅 2026-07-25
* [Hacking](https://github.com/carpedm20/awesome-hacking) ⭐ 16,891 | 🐛 68 | 📅 2024-06-02
* [Security](https://github.com/sbilly/awesome-security) ⭐ 14,758 | 🐛 308 | 📅 2026-01-11
* [Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) ⭐ 14,129 | 🐛 25 | 📅 2024-06-07
* [CTFs](https://github.com/apsdehal/awesome-ctf) ⭐ 11,762 | 🐛 64 | 🌐 JavaScript | 📅 2024-07-22
* [Honeypots](https://github.com/paralax/awesome-honeypots) ⭐ 10,521 | 🐛 21 | 🌐 Python | 📅 2026-06-01
* [Android Security](https://github.com/ashishb/android-security-awesome) ⭐ 9,613 | 🐛 2 | 🌐 Makefile | 📅 2026-08-17
* [Incident-Response](https://github.com/meirwah/awesome-incident-response) ⭐ 9,333 | 🐛 74 | 📅 2026-07-15
* [AppSec](https://github.com/paragonie/awesome-appsec) ⭐ 7,031 | 🐛 40 | 🌐 PHP | 📅 2025-02-22
* [Infosec](https://github.com/onlurking/awesome-infosec) ⭐ 5,717 | 🐛 15 | 📅 2026-08-15
* [Awesome Forensics](https://github.com/cugu/awesome-forensics) ⭐ 5,160 | 🐛 6 | 📅 2026-05-14
* [YARA](https://github.com/InQuest/awesome-yara) ⭐ 4,256 | 🐛 1 | 📅 2026-06-15
* [Social Engineering](https://github.com/v2-dev/awesome-social-engineering) ⭐ 4,226 | 🐛 10 | 📅 2023-04-05

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
