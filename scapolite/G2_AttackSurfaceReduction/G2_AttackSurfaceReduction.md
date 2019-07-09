---
scapolite:
    class: group
    version: '0.51'
id: G2
id_namespace: org.cisecurity.CIS-Google-Chrome
title: Attack Surface Reduction
description: <see below>
contents:
  - class: rule_ref
    idref: R2.1
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Default Flash Setting' is set to 'Enabled' (Cl ...
  - class: rule_ref
    idref: R2.2
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L2) Ensure 'Default notification setting' is set to 'Enabl ...
  - class: rule_ref
    idref: R2.3
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L2) Ensure 'Control use of the Web Bluetooth API' is set t ...
  - class: rule_ref
    idref: R2.4
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L2) Ensure 'Control use of the WebUSB API' is set to 'Enab ...
  - class: rule_ref
    idref: R2.5
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Configure extension installation blacklist' is ...
  - class: rule_ref
    idref: R2.6
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Configure allowed app/extension types' is set  ...
  - class: rule_ref
    idref: R2.7
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L2) Ensure 'Configure native messaging blacklist' is set t ...
  - class: rule_ref
    idref: R2.8
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable saving passwords to the password manage ...
  - class: rule_ref
    idref: R2.9
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Supported authentication schemes' is set to 'E ...
  - class: rule_ref
    idref: R2.10
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Choose how to specify proxy server settings' i ...
  - class: rule_ref
    idref: R2.11
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Allow running plugins that are outdated' is se ...
  - class: rule_ref
    idref: R2.12
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable Google Cloud Print Proxy' is set to 'Di ...
  - class: rule_ref
    idref: R2.13
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable Site Isolation for every site' is set t ...
  - class: rule_ref
    idref: R2.14
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Allow download restrictions' is set to 'Enable ...
  - class: rule_ref
    idref: R2.15
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Disable proceeding from the Safe Browsing warn ...
  - class: rule_ref
    idref: R2.16
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Notify a user that a browser relaunch or devic ...
  - class: rule_ref
    idref: R2.17
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Set the time period for update notifications'  ...
  - class: rule_ref
    idref: R2.18
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L2) Ensure 'Whether online OCSP/CRL checks are required fo ...
  - class: rule_ref
    idref: R2.19
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Enable Chrome Cleanup on Windows' is Configure ...
  - class: rule_ref
    idref: R2.20
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L2) Ensure 'Use built-in DNS client' is set to 'Disabled'
  - class: rule_ref
    idref: R2.21
    idref_namespace: org.cisecurity.CIS-Google-Chrome
    ref_comment: (L1) Ensure 'Update policy override' is set to 'Enabled' wi ...
---


## /description

This section contains recommendations that help reduce the overall
attack surface. Organizations should review these settings and any
potential impacts to ensure they make sense within the environment since
they restrict some browser functionality.
