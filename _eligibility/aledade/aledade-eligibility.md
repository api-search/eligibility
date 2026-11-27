---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACTING IN AN EMPLOYMENT OR BUSINESS CAPACITY, YOU FURTHER REPRESENT AND WARRANT THAT YOU HAVE THE LEGAL AUTHORITY TO BIND YOUR AFFILIATED ORGANIZATION, COMPANY OR OTHER ENTITY TO THESE TERMS.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating law or third-party contracts
    text: Use the Aledade App in any manner that would violate a contract with or other legal obligation owed to a third party.
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
name: Aledade
provenance_date: '2026-11-09'
provider_name: Aledade
provider_slug: aledade
slug: aledade-eligibility
source_date: '2026-11-09'
source_filename: aledade-eligibility.yml
source_heading: Eligibility
source_page: https://aledade.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aledade\naid: aledade\nurl: https://aledade.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACTING IN AN EMPLOYMENT OR BUSINESS CAPACITY, YOU FURTHER REPRESENT AND WARRANT THAT YOU HAVE\n    THE LEGAL AUTHORITY TO BIND YOUR AFFILIATED ORGANIZATION, COMPANY OR OTHER ENTITY TO THESE TERMS.\nrestricted_uses:\n- summary: Violating law or third-party contracts\n  text: Use the Aledade App in any manner that would violate a contract with or other legal obligation owed to a\n    third party.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aledade/eligibility/aledade-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Aledade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Value-Based Care
- Primary Care
- Accountable Care
- Population Health
- Health Data
---
