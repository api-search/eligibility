---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: While the Service does not have specific age restrictions, Customer represents that all Authorized Users are of legal age to enter into binding contracts
    value: null
  restricted_uses:
  - summary: No illegal or harmful content
    text: 'process, access, store, distribute, or transmit any viruses, or any data or material during the course of its use of the Service that: (a) is illegal, unlawful, harmful'
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
name: Icite
provenance_date: '2026-11-09'
provider_name: Icite
provider_slug: icite
slug: icite-eligibility
source_date: '2026-11-09'
source_filename: icite-eligibility.yml
source_heading: Eligibility
source_page: https://www.icite.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Icite\naid: icite\nurl: https://www.icite.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No illegal or harmful content\n  text: 'process, access, store, distribute, or transmit any viruses, or any data or material during the course\n    of its use of the Service that: (a) is illegal, unlawful, harmful'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: While the Service does not have specific age restrictions, Customer represents that all\
  \ Authorized Users\n    are of legal age to enter into binding contracts\n"
source_yaml_url: https://artifacts.apis.io/icite/eligibility/icite-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Icite's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Identity
- ITDR
- Platform
- Software-as-a-Service
- Company
---
