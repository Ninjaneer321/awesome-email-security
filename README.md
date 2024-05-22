# Awesome Email Security
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome resources related to enhancing your enterprise Email Security. Contributions are welcome!

## Table of Contents

- [Resources](#resources)
  - [Email Authentication](#email-authentication)
  - [Email Filtering](#email-filtering)
  - [Email Encryption](#email-encryption)
  - [Phishing Protection](#phishing-protection)
  - [Security Awareness Training](#security-awareness-training)
  - [Tools](#Tools)
- [Contributing](#contributing)
- [License](#license)
- [Code of Conduct](#code-of-conduct)

## Resources

### Email Authentication

#### SPF (Sender Policy Framework)
- **[SPF Introduction ](https://powerdmarc.com/what-is-spf/)** - SPF Explanation by PowerDMARC.
- **[SPF Introduction ](https://dmarcian.com/what-is-spf/)**   - SPF Explanation by Dmarcian
- **[SPF Record Setup](https://powerdmarc.com/how-to-setup-spf/)** - SPF Record Setup by PowerDMARC.

#### DKIM (DomainKeys Identified Mail)
- **[Resource Name](https://example.com)** - Brief description of the resource.
- **[DKIM Technical Details](https://easydmarc.com/blog/what-is-a-dkim-signature/)** - Technical Deep Dive on DKIM.

#### DMARC (Domain-based Message Authentication, Reporting, and Conformance)
- **[DMARC Introduction](https://www.techfry.com/webmaster-tips/domain-based-message-authentication-reporting-conformance-dmarc)** -  an introductory explanation of DMARC and how it works
- **[DMARC Explanation](https://www.mailmodo.com/guides/dmarc/)** - Good DMARC alignment explanation .

#### BIMI (Brand Indicators for Message Identification)
- **[BIMI Compete Guide](https://powerdmarc.com/your-complete-guide-to-bimi/)** - BIMI Introduction and Compelete guide.
- **[BIMI Implementation Guide](https://bimigroup.org/implementation-guide/)** -  BIMI Group Implementation guide

#### MTA-STS (Mail Transfer Agent Strict Transport Security)
- **[MTA-STS Introduction and Implemenation](https://powerdmarc.com/what-is-mta-sts-and-why-do-you-need-it/)** -  A guide on MTA-STS by PowerDMARC

### Email Filtering

#### Anti-Spam Solutions
- **[Email Filtering concepts](https://abnormalsecurity.com/glossary/email-filters)** - Introduction To email Filtering concepts and different types of spam filtering.
- **[Resource Name](https://example.com)** - Brief description of the resource.
- **[Exchange Online Email Filtering](https://learn.microsoft.com/en-us/defender-office-365/eop-about)** - Exchange Online Email Filtering Details.

#### File Extensions Filtering
- **[At minimum the following file extensions should be blocked]** 
.jnlp,.pyo,.pyzw,.ps1,.ps1xml,.psc1,.psc2,.psd1,.psdm1,.cdxml,.pssc,.cer,.crt,.der,.appref-ms,.udl,.wsb,.appcontent-ms,.settingcontentms,.cnt,.hpj,.website,.webpnp,.mcf,.printerexport,.pl,.theme,.vbp,.xbap,.xll,.xnk,.msu,.diagcab,.grp,.ins,.isp,.lib,.mde,.msix,.msixbundle,.mst,.nsh,.sys,.vxd,.jar,.exe,.xap,.shs,.lnk,.dll,.air,.msi,.fmx,.odex,.wiz,.dex,.bas,.tcp,.js,.scr,.appx,.accde,.elf,.bats,.deb,.ndr,.app,.fxp,.applications,.sxx,.mexw32,.axf,.oat,.pif,.gambas,.hta,.cpl,.osx,.pyd,.cmd,.irx,.vbs,.bpp,.msp,.vbe,.widget,.arj,.py,.prx,.fox,.rtl,.stx,.apk,.r,.jse,.g3a,.rpm,.azw2,.rxe,.self,.wgt,.msc,.trs,.pyz,.qpkg,.wsf,.cac,.vb,.acx,.dol,.nt,.wwe,.pva,.pe,.dm,.xex,.nexe,.rbtx,.prc,.prg,.frm,.agt,.kmd,.windowslivegroup,.int,.wince,.btm,.pwz,.xip,.8xp,.le,.shb,.jax,.zpkg,.ngage,.dsp,.wsh,.nxe,.fpx,.cfxxe,.ime,.aex,.mex,.gpe,.pgm,.exp,.lit,.dbr,.a6p,.cpp,.run,.dexe,.cas,.abs,.qpx,.acc,.s2a,.sko,.iconfig,.x,.tgz,.xlnk,.ppp9,.lku,.appxbundle,.fqy,.gtp,.ctl,.ppz9,.tzx,.ryb,.chm,.z,.r[0-9{2},.xz,.uue,.lzh,.mcl,.ace,.wsc,.bz,.bz2,.cab,.gz,.iso,.lha,.tar,.taz,.tbz,.tbz2,.txz,.uu,.xxe,.rev,.url,.001,.hlp,.ipa,.dmg,.sct,.reg,.inf,.gadget,.bzip2,.cpio,.fat,.swm,.tpz,.vhd,.wim,.xar,.squashfs,.zipx,.vmdk,.tz,.mim,.b64,.wzmul,.pyc,.vhdx,.pln,.sap,.alz,.xlam,.slk,.wbk,.dwg,.com,.one,.bat,.rdp
- **[ChatGPT Generated List]** 

  Below as a list of extensions to blocked generated by chatgpt.
 .exe, .bat, .cmd, .com, .scr, .pif, .msi, .msp, .jar, .vbs, .vbe, .js, .jse, .wsf, .wsh, .ps1, .ps2, .psc1, .psc2, .reg, .docm, .xlsm, .pptm, .xltm, .dotm, .ppsm, .sldm, .pdf, .sh, .csh, .ksh, .tcl, .php, .py, .rb, .pl, .zip, .rar, .7z, .tar, .gz, .bz2, .sys, .dll, .drv, .cpl, .ocx, .inf, .ini, .admx, .adml, .asp, .aspx, .cer, .csr, .crt, .der, .xsl, .dmg, .dmp, .iso, .img, .udf, .tmp, .sql, .bak, .bkp, .cfg, .conf, .dat, .ini, .log, .bak, .old, .backup, .swf, .eml, .msg, .pst, .ost, .oft, .shtml, .phtml, .htm, .html, .xhtml, .xml, .svc, .ashx, .asmx, .axd, .vsdisco, .config, .xslt, .resx, .manifest, .resources, .rc, .res, .dll.config, .exe.config, .cdx, .cs, .cpp, .c, .h, .hpp, .java, .class, .pyc, .pyo, .plc, .pld, .pm, .t, .ph, .xs, .cpl, .inf, .adp, .app, .bas, .bpl, .chm, .cmd, .cpl, .crt, .csh, .fxp, .hlp, .hta, .ins, .isp, .key, .lib, .mda, .mdb, .mde, .mdt, .mdw, .mpa, .msg, .msu, .nls, .ocx, .ops, .pcd, .pif, .prf, .prg, .pst, .rar, .scf, .scr, .sct, .shb, .shs, .sys, .url, .vb, .vbe, .vbs, .vxd, .wsc, .wsf, .wsh, .xll

- **[Resource Name](https://example.com)** - Brief description of the resource.

### Email Encryption

#### Transport Layer Security (TLS) for Email Transport
- **[STARTTLS](https://emaillabs.io/en/what-is-starttls/)** - An Explainer for STARTTLS and Opportunistic TLS vs Forced TLS
- **[Email Transport Encryption Protocols](https://certified-senders.org/wp-content/uploads/2020/02/Email-Transport-Encryption-STARTTLS-vs.-DANE-vs.-MTA-STS_updated.pdf)** - Explains the difference between STARTLS,DANE,MTA-STS.
- 

### Phishing Protection

#### Email Content Analysis for Phishing Detection
- **[Resource Name](https://example.com)** - Brief description of the resource.
- **[Resource Name](https://example.com)** - Brief description of the resource.

#### User Education and Awareness Programs
- **[Resource Name](https://example.com)** - Brief description of the resource.
- **[Resource Name](https://example.com)** - Brief description of the resource.
### Security Awareness Training

#### Phishing Simulation Platforms
- **[Resource Name](https://example.com)** - Brief description of the resource.
- **[Resource Name](https://example.com)** - Brief description of the resource.

#### Employee Training Modules and Courses
- **[Resource Name](https://example.com)** - Brief description of the resource.
- **[Resource Name](https://example.com)** - Brief description of the resource.

### Tools
#### Email Header Analysis
- **[Microsoft MHA](https://mha.azurewebsites.net/)** - Microsoft Email Header Analysis.
- **[Mxtoolbox MHA](https://mxtoolbox.com/EmailHeaders.aspx)** - MxToolBox Email Header Analyzer
- **[CyberDefenders MHA](https://github.com/cyberdefenders/email-header-analyzer)** - Excellent Email Header Analyzer that can be deployed locally

#### DMARC Reports Analysis
- **[Mxtoolbox DMARC Report Analyzer](https://mxtoolbox.com/DmarcReportAnalyzer.aspx)** - MxToolBox DMARC Report Analyzer
- **[OpenSource DMARC Report Analyzer](https://github.com/userjack6880/Open-DMARC-Analyzer)** - Open Source DMARC Report Analyzer 

#### Commercial Email Security Tools
#### Open Source Email Security Tools

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

Please make sure to update tests as appropriate.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to make participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment include:

- Using welcoming and inclusive language.
- Being respectful of differing viewpoints and experiences.
- Gracefully accepting constructive criticism.
- Focusing on what is best for the community.
- Showing empathy towards other community members.

Examples of unacceptable behavior by participants include:

- The use of sexualized language or imagery and unwelcome sexual attention or advances.
- Trolling, insulting/derogatory comments, and personal or political attacks.
- Public or private harassment.
- Publishing others' private information, such as a physical or electronic address, without explicit permission.
- Other conduct which could reasonably be considered inappropriate in a professional setting.

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this Code of Conduct, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces when an individual is representing the project or its community. Examples of representing a project or community include using an official project e-mail address, posting via an official social media account, or acting as an appointed representative at an online or offline event. Representation of a project may be further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team at [your-email@example.com]. All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances. The project team is obligated to maintain confidentiality with regard to the reporter of an incident. Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good faith may face temporary or permanent repercussions as determined by other members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1
