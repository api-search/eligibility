---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access and use may not be made in violation of U.S. export laws, and the Content may not be provided into any country subject to U.S. trade sanctions.
  entity_types:
  - text: Persons who are not of the age of majority are not eligible to use the Site
    type: individual
  minimum_age:
    text: Persons who are not of the age of majority are not eligible to use the Site
    value: null
  restricted_uses:
  - summary: Noncommercial use only
    text: the Software may be used solely for your personal, informational, noncommercial purposes
  - summary: Export and sanctions restrictions
    text: You may not access, download, use or export the Site, or the Content provided on or through the Site, in violation of U.S. export laws or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Java
provenance_date: '2026-11-09'
provider_name: Java
provider_slug: java
slug: java-eligibility
source_date: '2026-11-09'
source_filename: java-eligibility.yml
source_heading: Eligibility
source_page: https://www.oracle.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Java\naid: java\nurl: https://www.oracle.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access and use may not be made in violation of U.S. export laws, and the Content may not be provided into\n    any country subject to U.S. trade sanctions.\nentity_types:\n- type: individual\n  text: Persons who are not of the age of majority are not eligible to use the Site\nrestricted_uses:\n- summary: Noncommercial use only\n  text: the Software may be used solely for your personal, informational, noncommercial purposes\n- summary: Export and sanctions restrictions\n  text:\
  \ You may not access, download, use or export the Site, or the Content provided on or through the Site, in\n    violation of U.S. export laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Persons who are not of the age of majority are not eligible to use the Site\n"
source_yaml_url: https://artifacts.apis.io/java/eligibility/java-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Java's own page on 2026-11-09.
synthetic: false
tags:
- Enterprise
- Java
- JVM
- Object-Oriented
- Oracle
- Programming Language
---
