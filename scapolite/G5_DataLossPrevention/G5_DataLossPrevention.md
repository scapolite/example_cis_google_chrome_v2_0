---
scapolite:
    class: group
    version: '0.51'
id: G5
id_namespace: org.cisecurity.CIS-Google-Chrome
title: Data Loss Prevention
description: <see below>
contents:
  - class: rule_ref
    idref: R5.1
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable submission of documents to Google Cloud ...
  - class: rule_ref
    idref: R5.2
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Import saved passwords from default browser on ...
  - class: rule_ref
    idref: R5.3
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable AutoFill for credit cards' is set to 'D ...
  - class: rule_ref
    idref: R5.4
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable AutoFill for addresses' is set to 'Disa ...
---


## /description

This section contains recommendations to help prevent and protect
against unwanted loss of data. Organizations should review these
settings and any potential impacts to ensure they makes sense within the
environment since they so restrict some browser functionality.
