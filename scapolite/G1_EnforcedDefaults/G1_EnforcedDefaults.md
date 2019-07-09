---
scapolite:
    class: group
    version: '0.51'
id: G1
id_namespace: org.cisecurity.CIS-Google-Chrome
title: Enforced Defaults
description: <see below>
contents:
  - class: group_ref
    idref: G1.1
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: Remote access
  - class: rule_ref
    idref: R1.2
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Continue running background apps when Google C ...
  - class: rule_ref
    idref: R1.3
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Ask where to save each file before downloading ...
  - class: rule_ref
    idref: R1.4
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Disable saving browser history' is set to 'Dis ...
  - class: rule_ref
    idref: R1.5
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable HTTP/0.9 support on non-default ports'  ...
  - class: rule_ref
    idref: R1.6
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable component updates in Google Chrome' is  ...
  - class: rule_ref
    idref: R1.7
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable deprecated web platform features for a  ...
  - class: rule_ref
    idref: R1.8
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable third party software injection blocking ...
  - class: rule_ref
    idref: R1.9
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Extend Flash content setting to all content' i ...
  - class: rule_ref
    idref: R1.10
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Suppress the unsupported OS warning' is set to ...
  - class: rule_ref
    idref: R1.11
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Whether online OCSP/CRL checks are performed'  ...
  - class: rule_ref
    idref: R1.12
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Allow WebDriver to Override Incompatible Polic ...
  - class: rule_ref
    idref: R1.13
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Control SafeSites adult content filtering' is  ...
  - class: rule_ref
    idref: R1.14
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Origins or hostname patterns for which restric ...
  - class: rule_ref
    idref: R1.15
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Disable Certificate Transparency enforcement f ...
  - class: rule_ref
    idref: R1.16
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Disable Certificate Transparency enforcement f ...
  - class: rule_ref
    idref: R1.17
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Disable Certificate Transparency enforcement f ...
---


## /description

This section contains recommendations that are configured by default
when you install Google Chrome. Enforcing these settings at an
enterprise level can prevent these settings from changing to a less
secure option.
