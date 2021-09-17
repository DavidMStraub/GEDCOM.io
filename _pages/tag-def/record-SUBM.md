---
title: record-SUBM
permalink: /terms/v7/record-SUBM.html
layout: none
redirect-from:
  - /terms/v7/record-SUBM
...

```

%YAML 1.2
---
type: structure

uri: https://gedcom.io/terms/v7/record-SUBM

standard tag: SUBM

descriptions:
  - Submitter
  - A description of a contributor of information to the document. See
    SUBMITTER_RECORD for more.
  - The submitter record identifies an individual or organization that
    contributed information contained in the dataset. All records in the
    document are assumed to be contributed by the submitter referenced in the
    HEAD, unless a SUBM structure inside a specific record points at a
    different submitter record.

payload: null

substructures:
  "https://gedcom.io/terms/v7/ADDR": "{0:1}"
  "https://gedcom.io/terms/v7/CHAN": "{0:1}"
  "https://gedcom.io/terms/v7/CREA": "{0:1}"
  "https://gedcom.io/terms/v7/EMAIL": "{0:M}"
  "https://gedcom.io/terms/v7/EXID": "{0:M}"
  "https://gedcom.io/terms/v7/FAX": "{0:M}"
  "https://gedcom.io/terms/v7/NAME": "{1:1}"
  "https://gedcom.io/terms/v7/NOTE": "{0:M}"
  "https://gedcom.io/terms/v7/OBJE": "{0:M}"
  "https://gedcom.io/terms/v7/PHON": "{0:M}"
  "https://gedcom.io/terms/v7/REFN": "{0:M}"
  "https://gedcom.io/terms/v7/SNOTE": "{0:M}"
  "https://gedcom.io/terms/v7/SUBM-LANG": "{0:M}"
  "https://gedcom.io/terms/v7/UID": "{0:M}"
  "https://gedcom.io/terms/v7/WWW": "{0:M}"

superstructures: []
...

```