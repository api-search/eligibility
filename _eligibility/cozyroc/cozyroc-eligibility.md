---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are a person barred from receiving the Services under the laws of the United States or other countries including the country in which you are resident or from which you use the Services.
  minimum_age:
    text: you are not of legal age to form a binding contract with CozyRoc.com
    value: null
  restricted_uses:
  - summary: Export and legal compliance
    text: any laws regarding the export of data or software to and from the United States or other relevant countries
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
name: COZYROC
provenance_date: '2026-11-09'
provider_name: COZYROC
provider_slug: cozyroc
slug: cozyroc-eligibility
source_date: '2026-11-09'
source_filename: cozyroc-eligibility.yml
source_heading: Eligibility
source_page: https://cozyroc.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: COZYROC\naid: cozyroc\nurl: https://cozyroc.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are a person barred from receiving the Services under the laws of the United States or other countries\n    including the country in which you are resident or from which you use the Services.\nentity_types: []\nrestricted_uses:\n- summary: Export and legal compliance\n  text: any laws regarding the export of data or software to and from the United States or other relevant countries\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: you are not of legal age to form a binding contract with CozyRoc.com\n"
source_yaml_url: https://artifacts.apis.io/cozyroc/eligibility/cozyroc-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from COZYROC's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- ETL
- SSIS
- Cloud Integration
---
