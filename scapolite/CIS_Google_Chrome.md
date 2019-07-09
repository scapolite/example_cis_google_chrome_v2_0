---
scapolite:
    class: collection
    version: '0.51'
    lang: en
    format: md
id: CIS_Google_Chrome
id_namespace: org.cisecurity
version: 2.0.0
status: accepted
title: CIS Google Chrome Benchmark
notice: <see below>
objectives: <see below>
applicability:
  - system: https://scap.nist.gov/schema/cpe/2.3
    cpes:
      - cpe:/a:google:chrome
contents:
  - class: group_ref
    idref: G1
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: Enforced Defaults
  - class: group_ref
    idref: G2
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: Attack Surface Reduction
  - class: group_ref
    idref: G3
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: Privacy
  - class: group_ref
    idref: G4
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: Management/visibility/performance
  - class: group_ref
    idref: G5
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: Data Loss Prevention
profiles:
  - class: profile_ref
    idref: Level_1_L1_-_CorporateEnterprise_Environment_general_use
    idref_namespace: org.cisecurity.CIS-Google-Chrome
  - class: profile_ref
    idref: Level_2_L2_-_High_SecuritySensitive_Data_Environment_limited_functionality
    idref_namespace: org.cisecurity.CIS-Google-Chrome
history:
  - version: 2.0.0
    date: '2019-05-17'
    action: created
    short_description: accepted
    internal_comment: ''
---


## /notice

BACKGROUND. The Center for Internet Security ("CIS") provides
benchmarks, scoring tools, software, data, information, suggestions,
ideas, and other services and materials from the CIS website or
elsewhere ("Products") as a public service to Internet users
worldwide. Recommendations contained in the Products
("Recommendations") result from a consensus-building process that
involves many security experts and are generally generic in nature. The
Recommendations are intended to provide helpful information to
organizations attempting to evaluate or improve the security of their
networks, systems, and devices. Proper use of the Recommendations
requires careful analysis and adaptation to specific user requirements.
The Recommendations are not in any way intended to be a "quick fix"
for anyone's information security needs. NO REPRESENTATIONS,
WARRANTIES, OR COVENANTS. CIS makes no representations, warranties, or
covenants whatsoever as to (i) the positive or negative effect of the
Products or the Recommendations on the operation or the security of any
particular network, computer system, network device, software, hardware,
or any component of any of the foregoing or (ii) the accuracy,
reliability, timeliness, or completeness of the Products or the
Recommendations. CIS is providing the Products and the Recommendations
"as is" and "as available" without representations, warranties, or
covenants of any kind. USER AGREEMENTS. By using the Products and/or the
Recommendations, I and/or my organization ("We") agree and acknowledge
that: 1. No network, system, device, hardware, software, or component
can be made fully secure; 2. We are using the Products and the
Recommendations solely at our own risk; 3. We are not compensating CIS
to assume any liabilities associated with our use of the Products or the
Recommendations, even risks that result from CIS's negligence or
failure to perform; 4. We have the sole responsibility to evaluate the
risks and benefits of the Products and Recommendations to us and to
adapt the Products and the Recommendations to our particular
circumstances and requirements; 5. Neither CIS, nor any CIS Party
(defined below) has any responsibility to make any corrections, updates,
upgrades, or bug fixes; or to notify us of the need for any such
corrections, updates, upgrades, or bug fixes; and 6. Neither CIS nor any
CIS Party has or will have any liability to us whatsoever (whether based
in contract, tort, strict liability or otherwise) for any direct,
indirect, incidental, consequential, or special damages (including
without limitation loss of profits, loss of sales, loss of or damage to
reputation,loss of customers, loss of software, data, information or
emails, loss of privacy, loss of use of any computer or other equipment,
business interruption, wasted management or other staff resources or
claims of any kind against us from third parties) arising out of or in
any way Connected with our use of or our inability to use any of the
Products or Recommendations (even if CIS has been advised of the
possibility of such damages), including without limitation any liability
associated with infringement of intellectual property, defects, bugs,
errors, omissions, viruses, worms, backdoors, Trojan horses or other
harmful items. GRANT OF LIMITED RIGHTS. CIS hereby grants each user the
following rights, but only so long as the user complies with all of the
terms of these Agreed Terms of Use: 1. Except to the extent that we may
have received additional authorization pursuant to a written agreement
with CIS, each user may download, install and use each of the Products
on a single computer; 2. Each user may print one or more copies of any
Product or any component of a Product that is in a .txt, .pdf, .doc,
.mcw, or .rtf format, provided that all such copies are printed in full
and are kept intact, including without limitation the text of this
Agreed Terms of Use in its entirety. RETENTION OF INTELLECTUAL PROPERTY
RIGHTS; LIMITATIONS ON DISTRIBUTION. The Products are protected by
copyright and other intellectual property laws and by international
treaties. We acknowledge and agree that we are not acquiring title to
any intellectual property rights in the Products and that full title and
all ownership rights to the Products will remain the exclusive property
of CIS or CIS Parties. CIS reserves all rights not expressly granted to
users in the preceding section entitled "Grant of limited rights."
Subject to the paragraph entitled "Special Rules" (which includes a
waiver, granted to some classes of CIS Members, of certain limitations
in this paragraph), and except as we may have otherwise agreed in a
written agreement with CIS, we agree that we will not (i) decompile,
disassemble, reverse engineer, or otherwise attempt to derive the source
code for any software Product that is not already in the form of source
code; (ii) distribute, redistribute, encumber, sell, rent, lease, lend,
sublicense, or otherwise transfer or exploit rights to any Product or
any component of a Product; (iii) post any Product or any component of a
Product on any website, bulletin board, ftp server, newsgroup, or other
similar mechanism or device, without regard to whether such mechanism or
device is internal or external, (iv) remove or alter trademark, logo,
copyright or other proprietary notices, legends, symbols or labels in
any Product or any component of a Product; (v) remove these Agreed Terms
of Use from, or alter these Agreed Terms of Use as they appear in, any
Product or any component of a Product; (vi) use any Product or any
component of a Product with any derivative works based directly on a
Product or any component of a Product; (vii) use any Product or any
component of a Product with other products or applications that are
directly and specifically dependent on such Product or any component for
any part of their functionality, or (viii) represent or claim a
particular level of compliance with a CIS Benchmark, scoring tool or
other Product. We will not facilitate or otherwise aid other individuals
or entities in any of the activities listed in this paragraph. We hereby
agree to indemnify, defend, and hold CIS and all of its officers,
directors, members, contributors, employees, authors, developers,
agents, affiliates, licensors, information and service providers,
software suppliers, hardware suppliers, and all other persons who aided
CIS in the creation, development, or maintenance of the Products or
Recommendations ("CIS Parties") harmless from and against any and all
liability, losses, costs, and expenses (including attorneys' fees and
court costs) incurred by CIS or any CIS Party in connection with any
claim arising out of any violation by us of the preceding paragraph,
including without limitation CIS's right, at our expense, to assume the
exclusive defense and control of any matter subject to this
indemnification, and in such case, we agree to cooperate with CIS in its
defense of such claim. We further agree that all CIS Parties are
third-party beneficiaries of our undertakings in these Agreed Terms of
Use. SPECIAL RULES. CIS has created and will from time to time create,
special rules for its members and for other persons and organizations
with which CIS has a written contractual relationship. Those special
rules will override and supersede these Agreed Terms of Use with respect
to the users who are covered by the special rules. CIS hereby grants
each CIS Security Consulting or Software Vendor Member and each CIS
Organizational User Member, but only so long as such Member remains in
good standing with CIS and complies with all of the terms of these
Agreed Terms of Use, the right to distribute the Products and
Recommendations within such Member's own organization, whether by
manual or electronic means. Each such Member acknowledges and agrees
that the foregoing grant is subject to the terms of such Member's
membership arrangement with CIS and may, therefore, be modified or
terminated by CIS at any time. CHOICE OF LAW; JURISDICTION; VENUE. We
acknowledge and agree that these Agreed Terms of Use will be governed by
and construed in accordance with the laws of the State of Maryland, that
any action at law or in equity arising out of or relating to these
Agreed Terms of Use shall be filed only in the courts located in the
State of Maryland, that we hereby consent and submit to the personal
jurisdiction of such courts for the purposes of litigating any such
action. If any of these Agreed Terms of Use shall be determined to be
unlawful, void, or for any reason unenforceable, then such terms shall
be deemed severable and shall not affect the validity and enforceability
of any remaining provisions. BY USING THE PRODUCTS I(WE) ACKNOWLEDGE
THAT WE HAVE READ THESE AGREED TERMS OF USE IN THEIR ENTIRETY,
UNDERSTAND THEM, AND I(WE) AGREE TO BE BOUND BY THEM IN ALL RESPECTS.

## /objectives

This document provides prescriptive guidance for establishing a secure
configuration posture for Google Chrome Browser. This guide was tested
against Google Chrome v75. To obtain the latest version of this guide,
please visit
[http://benchmarks.cisecurity.org](http://benchmarks.cisecurity.org/).
If you have questions, comments, or have identified ways to improve this
guide, please write us at <feedback@cisecurity.org>.
