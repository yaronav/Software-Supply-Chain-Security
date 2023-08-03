# Software Supply Chain Security

## Introduction
A knowledge base comprising **Software Supply Chain Security** initiatives, standards, regulations, organizations, vendors, tooling, books, articles and a plethora of other learning resources from the web. The list was initially compiled to help me with my research for my upcoming book on Software Supply Chain Security. However, I have decided to make the list public for the benefit of everyone else working in this domain. I will endeavour to keep the list up to date as best as I can.

## Organizations, Foundations, Working Groups
### National Telecommunications and Information Administration ([NTIA](https://www.ntia.gov/))
* [NTIA SBOM Resources](https://www.ntia.gov/page/software-bill-materials)
* [SBOM FAQ](https://www.ntia.doc.gov/files/ntia/publications/sbom_faq_-_fork_for_october_22_meeting.pdf)
* [How-To Guide for SBOM Generation](https://www.ntia.gov/files/ntia/publications/howto_guide_for_sbom_generation_v1.pdf)
### Cybersecurity and Infrastructure Security Agency ([CISA](https://www.cisa.gov/))
* [CISA SBOM Resources](https://www.cisa.gov/sbom)
* [Software Bill of Materials (SBOM) Sharing Lifecycle Report](https://www.cisa.gov/sites/default/files/2023-04/sbom-sharing-lifecycle-report_508.pdf), April 2023
* [SBOM-a-rama 2023 Recordings](https://www.cisa.gov/news-events/events/sbom-rama)
* [SBOM-a-rama 2021 Recordings](https://www.cisa.gov/resources-tools/resources/cisa-sbom-rama)
### National Institute of Standards and Technology ([NIST](https://www.nist.gov/))
* [Improving the Nation's Cybersecurity: NIST’s Responsibilities Under the May 2021 Executive Order](https://www.nist.gov/itl/executive-order-14028-improving-nations-cybersecurity)
* [NIST SP 800-161 Rev.1 - Cybersecurity Supply Chain Risk Management Practices for Systems and Organizations](https://csrc.nist.gov/pubs/sp/800/161/r1/final), May 2022
* [Secure Software Development Framework (SSDF)](https://csrc.nist.gov/Projects/ssdf)
### Open Worldwide Application Security Project ([OWASP](https://owasp.org/))
* [OWASP Software Component Verification Standard](https://owasp.org/www-project-software-component-verification-standard/)
* [OWASP CycloneDX](https://owasp.org/www-project-cyclonedx/)
* [OWASP Top 10 CI/CD Security Risks](https://owasp.org/www-project-top-10-ci-cd-security-risks/)
* [Article on Component Analysis](https://owasp.org/www-community/Component_Analysis) by [Steve Springett](https://www.linkedin.com/in/stevespringett/)
### Open Source Security Foundation ([OpenSSF](https://openssf.org/))
* [The Open Source Software Security Mobilization Plan](https://openssf.org/oss-security-mobilization-plan/)
* [OpenSSF Working Groups](https://openssf.org/community/openssf-working-groups/)
* [Securing Your Software Supply Chain with Sigstore Course](https://openssf.org/training/securing-your-software-supply-chain-with-sigstore-course/)
* [OpenSSF Scorecard](https://securityscorecards.dev/)
### Cloud Native Computing Foundation ([CNCF](https://www.cncf.io/))
* [CNCF Software Supply Chain Best Practices](https://project.linuxfoundation.org/hubfs/CNCF_SSCP_v1.pdf), [[GitHub](https://github.com/cncf/tag-security/blob/main/supply-chain-security/supply-chain-security-paper/CNCF_SSCP_v1.pdf)]
* [Secure Software Factory Reference Architecture](https://github.com/cncf/tag-security/blob/main/supply-chain-security/secure-software-factory/Secure_Software_Factory_Whitepaper.pdf)
### [Software Transparency Foundation](https://st.foundation/)
* [OSSKB.org](https://osskb.org/)

## Regulations
* [EO-14028 - Executive Order on Improving the Nation’s Cybersecurity](https://www.whitehouse.gov/briefing-room/presidential-actions/2021/05/12/executive-order-on-improving-the-nations-cybersecurity/), May 12, 2021
* [The European Cyber Resilience Act (CRA)](https://www.european-cyber-resilience-act.com/), September 2022

## Standards, Frameworks, Best Practices
* [Supply-chain Levels for Software Artifacts (SLSA)](https://slsa.dev/), [[GitHub]](https://github.com/slsa-framework/slsa)
* [Introducing SLSA, an End-to-End Framework for Supply Chain Integrity](https://security.googleblog.com/2021/06/introducing-slsa-end-to-end-framework.html)
* [OWASP Software Component Verification Standard (SCVS)](https://owasp.org/www-project-software-component-verification-standard/)
* [OASIS Common Security Advisory Framework (CSAF)](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=csaf)
* [NIST Secure Software Development Framework (SSDF)](https://csrc.nist.gov/Projects/ssdf)
* [CIS Software Supply Chain Security Guide v1.0](https://www.cisecurity.org/insights/white-papers/cis-software-supply-chain-security-guide), June 2022
* [Securing the Software Supply Chain - Recommended Practices Guide for Developers](https://media.defense.gov/2022/Sep/01/2003068942/-1/-1/0/ESF_SECURING_THE_SOFTWARE_SUPPLY_CHAIN_DEVELOPERS.PDF), Enduring Security Framework (ESF) Software Supply Chain Working Panel, [Critical Infrastructure Partnership Advisory Council (CIPAC)](https://www.cisa.gov/resources-tools/groups/critical-infrastructure-partnership-advisory-council-cipac), August 2022
* [Microsoft Secure Supply Chain Consumption Framework (S2C2F)](https://www.microsoft.com/en-us/security/blog/2022/11/16/microsoft-contributes-s2c2f-to-openssf-to-improve-supply-chain-security/)[[GitHub]](https://github.com/ossf/s2c2f)

## Initiatives
* [OpenSSF sigstore](https://www.sigstore.dev/)

## Software Supply Chain Threats
* [Catalog of Supply Chain Compromises](https://github.com/cncf/tag-security/tree/main/supply-chain-security/compromises)
* [SLSA Threats & Mitigations](https://slsa.dev/spec/v1.0/threats)
* [Taxonomy of Attacks on Open-Source Software Supply Chains](https://arxiv.org/abs/2204.04008)
* [Open-Source Software Supply Chain Attack Vectors](https://sap.github.io/risk-explorer-for-software-supply-chains/#/attackvectors)
* [Software Supply Chain Compromises](https://github.com/IQTLabs/software-supply-chain-compromises)

## Vulnerability Management
##### EPSS
* [Exploit Prediction Scoring System (EPSS)](https://www.first.org/epss/)
##### VEX
* [Vulnerability Exploitability eXchange (VEX)](https://www.ntia.gov/files/ntia/publications/vex_one-page_summary.pdf)
* [OpenVEX Specification](https://github.com/openvex/spec)
* [VEX Use Cases](https://www.cisa.gov/sites/default/files/publications/VEX_Use_Cases_April2022.pdf)
* [VEX Status Justification](https://www.cisa.gov/sites/default/files/publications/VEX_Status_Justification_Jun22.pdf)
##### SSVC
* [CISA Stakeholder Specific Vulnerability Categorization (SSVC)](https://www.cisa.gov/stakeholder-specific-vulnerability-categorization-ssvc)
##### KEV
* [CISA Known Exploited Vulnerabilities Catalog (KEV)](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)

#### Vulnerability Databases
* [National Vulnerability Database (NVD)](https://nvd.nist.gov/)
* [Sonatype OSS Index](https://ossindex.sonatype.org/)
* [Open Source Vulnerability Database (OSV)](https://osv.dev/)
* [Global Security Database (GSD)](https://gsd.id/)

## Software Identification
* [Common Platform Enumeration (CPE)](https://csrc.nist.gov/pubs/ir/7697/final)
* [Software Identification (SWID)](https://csrc.nist.gov/projects/Software-Identification-SWID)
* [Package URL (purl)](https://github.com/package-url/purl-spec)

## Bill of Materials
* [Software Bill of Materials (SBOM)](https://cyclonedx.org/capabilities/sbom)
* [Software as a Service Bill of Materials (SaaSBOM)](https://cyclonedx.org/capabilities/saasbom)
* [Hardware Bill of Materials (HBOM)](https://cyclonedx.org/capabilities/hbom)
* [Machine Learning Bill of Materials (MLBOM)](https://cyclonedx.org/capabilities/mlbom)
* [Manufacturing Bill of Materials (MBOM)](https://cyclonedx.org/capabilities/mbom)
* [Operations Bill of Materials (OBOM)](https://cyclonedx.org/capabilities/obom)
* [Cryptography Bill of Materials (CBOM)](https://github.com/IBM/CBOM)

## SBOM
### Formats and Specifications
* [CycloneDX](https://cyclonedx.org/)
* [Software Package Data Exchange (SPDX)](https://spdx.dev/)
* [Software Identification (SWID)](https://csrc.nist.gov/projects/Software-Identification-SWID)
### SBOM Lifecycle / Implementation Practices
* [GitLab Software Supply Chain Security Direction](https://about.gitlab.com/direction/supply-chain/)

## Tooling
### Vendors
* [Anchore](https://anchore.com/)
* [Chainguard](https://www.chainguard.dev/)
* [Codenotary](https://codenotary.com/)
* [Cybeats](https://www.cybeats.com/)
* [Endor Labs](https://www.endorlabs.com/)
* [FOSSA](https://fossa.com/)
* [Rezilion](https://www.rezilion.com/)
* [TestifySec](https://www.testifysec.com/)

### SBOM Generation
#### Native
#### Open-Source
* [kubernetes bom tool](https://github.com/kubernetes-sigs/bom)
* [Microsoft’s SBOM Tool](https://github.com/microsoft/sbom-tool)
* [spdx-sbom-generator](https://github.com/opensbom-generator/spdx-sbom-generator)
* [syft](https://github.com/anchore/syft)
#### Commercial

### SBOM Scanning & Analysis
#### Native
#### Open-Source
* [OWASP Dependency-Track](https://dependencytrack.org/)
* [Graph for Understanding Artifact Composition (GUAC)](https://guac.sh/), [[GitHub](https://github.com/guacsec/guac)], [[Google Article](https://security.googleblog.com/2022/10/announcing-guac-great-pairing-with-slsa.html)]
#### Commercial

### SBOM Governance
#### Native
#### Open-Source
* [Aqua Chain-bench](https://github.com/aquasecurity/chain-bench/tree/main)
#### Commercial

### Other / Unsorted

## Software Supply Chain Security in Cloud Environments

## Books
* [Software Transparency - Supply Chain Security in an Era of Software-Driven Society](https://www.amazon.com/Software-Transparency-Security-Software-Driven-Society/dp/1394158483) by [Chris Huges](https://www.linkedin.com/in/resilientcyber/) & [Tony Turner](https://www.linkedin.com/in/tonyturnercissp/)
* [Software Supply Chain Security: Securing the End-to-End Supply Chain for Software, Firmware, and Hardware](https://www.amazon.com/Software-Supply-Chain-Security-End/dp/1098133706/) by [Cassie Crossley](https://www.linkedin.com/in/cassiecrossley/), Release date 31 January 2024

## Industry Reports
* [Synopsis Open Source Security and Risk Analysis Report](https://www.synopsys.com/software-integrity/resources/analyst-reports/open-source-security-risk-analysis.html), Synopsis, 2023
* [The State of Dependency Management](https://www.endorlabs.com/state-of-dependency-management), Endor Labs, 2023
* [Software Bill of Materials (SBOM) and Cybersecurity Readiness](https://8112310.fs1.hubspotusercontent-na1.net/hubfs/8112310/LF%20Research/State%20of%20Software%20Bill%20of%20Materials%20-%20Report.pdf), The Linux Foundation, January 2022

## Guides / Documentation
* [Authoritative Guide to SBOM](https://cyclonedx.org/guides/sbom/OWASP_CycloneDX-SBOM-Guide-en.pdf), OWASP CycloneDX, June 2023

## Articles / White Papers
* [Tragedy of the Digital Commons](https://ssrn.com/abstract=4245266), Sharma, Chinmayi, Written: August 2022, Last Revised: May 2023
* [Principles and Practices for Software Bill of Materials for Medical Device Cybersecurity](https://www.imdrf.org/sites/default/files/2023-04/Principles%20and%20Practices%20for%20Software%20Bill%20of%20Materials%20for%20Medical%20Device%20Cybersecurity%20%28N73%29.pdf),  Medical Device Cybersecurity Working Group, International Medical Device Regulators Forum, April 2023
* [An Empirical Study on Software Bill of Materials: Where We Stand and the Road Ahead](https://arxiv.org/pdf/2301.05362.pdf), February 2023
* [Taxonomy of Attacks on Open-Source Software Supply Chains](https://arxiv.org/pdf/2204.04008.pdf), April 2022
* [Using the Software Bill of Materials for Enhancing Cybersecurity](https://english.ncsc.nl/binaries/ncsc-en/documenten/publications/2021/february/4/using-the-software-bill-of-materials-for-enhancing-cybersecurity/Final+Report+SBoM+for+Cybersecurity+v1.0.pdf), Capgemini, January 2021
* [BREAKING TRUST: Shades of Crisis Across an Insecure Software Supply Chain](https://www.atlanticcouncil.org/wp-content/uploads/2020/07/Breaking-trust-Shades-of-crisis-across-an-insecure-software-supply-chain.pdf), July 2020
* [Software Supply Chain Attacks](https://www.dni.gov/files/NCSC/documents/supplychain/20190327-Software-Supply-Chain-Attacks02.pdf), Office of the Director of  National Intelligence (DNI), 2017

## Blogs
* [Resilient Cyber](https://resilientcyber.substack.com/) by Chris Huges
* [Tom Alrich's blog](http://tomalrichblog.blogspot.com/) by Tom Alrich
* [Endor Labs resources](https://www.endorlabs.com/resources-overview)
* [Chainguard blog](https://www.chainguard.dev/unchained)
* [snyk blog](https://snyk.io/blog/?tag=open-source-security)
* [TestifySec blog](https://www.testifysec.com/blog/)


## Webinars
* [Endor Labs webinars](https://www.endorlabs.com/resources-overview)

## Podcasts
* [daBOM](https://dabom.captivate.fm/)
## Events
* [OpenSSF Day Europe, Bilbao, Spain – 18 September 2023](https://openssf.org/event/openssf-day-europe-september-18-in-bilbao-spain/)

## From the Web
### Readings
* [Lessons Not Learned From Software Supply Chain Attacks](https://www.darkreading.com/attacks-breaches/lessons-not-learned-from-software-supply-chain-attacks)
* [“SBOM” should not exist! Long live the SBOM.](https://medium.com/@steve_springett/sbom-should-not-exist-long-live-the-sbom-4554d5c31ff9)
* [SLSA dip — At the Source of the problem!](https://medium.com/boostsecurity/slsa-dip-source-of-the-problem-a1dac46a976)
### Videos
* [Why you need an XBOM – the eXtended Software Bill of Materials](https://www.youtube.com/watch?v=KPa-v5KndIY)

## Related GitHub Repos
* [bureado / awesome-software-supply-chain-security](https://github.com/bureado/awesome-software-supply-chain-security)
* [meta-fun / awesome-software-supply-chain-security](https://github.com/meta-fun/awesome-software-supply-chain-security)
* [awesomeSBOM / awesome-sbom](https://github.com/awesomeSBOM/awesome-sbom)
* [AevaOnline / supply-chain-synthesis](https://github.com/AevaOnline/supply-chain-synthesis/)
* [IQTLabs / software-supply-chain-compromises](https://github.com/IQTLabs/software-supply-chain-compromises)

## Miscellaneous / Unsorted


