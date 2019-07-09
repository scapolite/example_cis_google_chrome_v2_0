## Scapolite Example: CIS Security Benchmark for Google Chrome v2.0


### Background

From April 30th to May 2nd 2019, NIST conducted a workshop on the
future of [SCAP](https://csrc.nist.gov/Projects/Security-Content-Automation-Protocol-v2).

During the workshop, the participants in the break-out sessions on the
future of XCCDF decided on founding a [work
group](https://groups.google.com/a/list.nist.gov/forum/#!forum/scap-dev-authoring)
on improving authoring and maintenance of SCAP content as manageable
text files under version control such as practiced by RedHat's
[Compliance-as-Code project](https://github.com/ComplianceAsCode/content) and Siemens'
[Scapolite
format](https://github.com/scapolite/docs/raw/master/201905_scap_v2_workshop/grobauer_siemens_scap_v2_experiences_scapolite.pdf)

The participants agreed that Siemens' Scapolite format looked like a promising candidate to be used as basis for a standard format and that it should be further evaluated. As first step in this evaluation, a complete example of
SCAP content maintained in Scapolite rather than XCCDF+OVAL should be published.

This repository contains such an example.


### Contents of this repository


This content has been produced from an import of the *CIS Security Benchmark for Google Chrome (v2.0)*
SCAP datastream into the Scapolite format:

- Folder `scapolite` contains the Scapolite representation of the STIG:

  - the design of Scapolite allows the maintenance of each rule
    as a single file rather than maintaining the complete
    baseline within one huge XML file
  - the combination of a YAML preamble and a Markdown body
    allows authors to leverage the preview capabilities of
    modern editors and web sites such as github.com
  - rules can be augmented with machine-readable information
    either within the rule file (e.g., the machine-readable
    information on Windows GPO settings and their underlying
    implementation mechanisms) as well as outside the file
    (as practiced in this example with the OVAL checks; those
    could be included also within the rule file, but the
    very verbose XML syntax of OVAL makes this a bit cumbersome).
   

- The following files are exports of the content which have been carried
  out with proof-of-concept tooling for working with `Scapolite`:

  - `iase_win_server_2016_v1r7_scapolite_export.xlsx`

    An Excel-representation of all rules of the STIG
  - `iase_win_server_2016_v1r7_scapolite_export.pdf`

    A PDF representation of the STIG


Please refer to the [slide set about Scapolite](https://github.com/scapolite/docs/raw/master/201905_scap_v2_workshop/grobauer_siemens_scap_v2_experiences_scapolite.pdf)
that has been presented at NIST's SCAP v2 workshop for more information about Scapolite.

The machine-readable information on how to implement the settings
is *not* part of the original CIS Benchmark; the information
has been added using the mechanisms described in the
[slide set about automating implementation](https://github.com/scapolite/docs/raw/master/201905_scap_v2_workshop/stoeckle_tum_scap_v2_scapolite_automated_implementation.pdf)
that has been presented at NIST's SCAP v2 workshop.


**ATTENTION**

Copyright holder for the contents of the CIS Google Chrome Baseline (v2.0), is CIS,
please refer to the [CIS Website](https://www.cisecurity.org/cis-benchmarks/) for
information about CIS Benchmarks and access to the authoritative versions of the benchmarks.

This project merely uses the CIS Benchmark as an example of how SCAP content can be expressed
and enriched in Scapolite. 

*We are grateful to CIS for allowing us to publish this transformed version of their content!*

### Questions and Feedback

For feedback/questions/discussion please use the mailing list:

https://list.nist.gov/scap-dev-authoring 


