---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Persons who are not of the age of majority are not eligible to use the Site
    value: age of majority
  restricted_uses:
  - summary: Export restrictions
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
name: PeopleSoft Financials
provenance_date: '2026-11-10'
provider_name: PeopleSoft Financials
provider_slug: peoplesoft-financials
slug: peoplesoft-financials-eligibility
source_date: '2026-11-10'
source_filename: peoplesoft-financials-eligibility.yml
source_heading: Eligibility
source_page: https://www.oracle.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PeopleSoft Financials\naid: peoplesoft-financials\nurl: https://www.oracle.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not access, download, use or export the Site, or the Content provided on or through the Site, in\n    violation of U.S. export laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: Persons who are not of the age of majority are not eligible to use the Site\n"
source_yaml_url: https://artifacts.apis.io/peoplesoft-financials/eligibility/peoplesoft-financials-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from PeopleSoft Financials's own page on 2026-11-10.
synthetic: false
tags:
- Enterprise
- ERP
- Finance
- Oracle
- PeopleSoft
---
