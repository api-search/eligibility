---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Client is an individual that has signed up for the Services in an individual capacity with their employer email address
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No protected health or GDPR personal data without separate agreement
    text: Client shall not store, transmit or otherwise process any information via the Services that falls within the definition of “Protected Health Information” under the Health Insurance Portability and Accountability Act Privacy Rule
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
name: RecappED
provenance_date: '2026-11-10'
provider_name: RecappED
provider_slug: recapped
slug: recapped-eligibility
source_date: '2026-11-10'
source_filename: recapped-eligibility.yml
source_heading: Eligibility
source_page: https://www.recapped.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RecappED\naid: recapped\nurl: https://www.recapped.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If Client is an individual that has signed up for the Services in an individual capacity with their employer\n    email address\nrestricted_uses:\n- summary: No protected health or GDPR personal data without separate agreement\n  text: Client shall not store, transmit or otherwise process any information via the Services that falls within\n    the definition of “Protected Health Information” under the Health Insurance Portability\
  \ and Accountability Act\n    Privacy Rule\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/recapped/eligibility/recapped-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from RecappED's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- Sales Enablement
- Digital Sales Room
- Customer Onboarding
- CRM
- Revenue Operations
- Defunct
---
