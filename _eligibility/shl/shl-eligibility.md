---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither the services or products of SHL nor the underlying information or technology may be downloaded or otherwise provided or made available, either directly or indirectly, into any country subject to U.S. trade sanctions, available here
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
name: SHL
provenance_date: '2026-11-10'
provider_name: SHL
provider_slug: shl
slug: shl-eligibility
source_date: '2026-11-10'
source_filename: shl-eligibility.yml
source_heading: Eligibility
source_page: https://www.shl.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SHL\naid: shl\nurl: https://www.shl.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Neither the services or products of SHL nor the underlying information or technology may be downloaded or\n    otherwise provided or made available, either directly or indirectly, into any country subject to U.S. trade\n    sanctions, available here\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not access, download, use or export the Site, or the Content provided on or through the Site, in\n    violation of U.S. export laws or regulations\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: Persons who are not of the age of majority are not eligible to use the Site\n"
source_yaml_url: https://artifacts.apis.io/shl/eligibility/shl-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SHL's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Talent Assessment
- People Science
- HR Technology
- Workforce Analytics
---
