---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Services and the Software are intended for business, commercial use only and not for personal use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal use
    text: These Services and the Software are intended for business, commercial use only and not for personal use.
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
name: Semble
provenance_date: '2026-11-10'
provider_name: Semble
provider_slug: semble
slug: semble-eligibility
source_date: '2026-11-10'
source_filename: semble-eligibility.yml
source_heading: Eligibility
source_page: https://www.semble.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Semble\naid: semble\nurl: https://www.semble.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Services and the Software are intended for business, commercial use only and not for personal use.\nrestricted_uses:\n- summary: No personal use\n  text: These Services and the Software are intended for business, commercial use only and not for personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/semble/eligibility/semble-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Semble's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United Kingdom
- Electronic Health Records
- Practice Management
- GraphQL
- Patient Records
- Scheduling
- e-Prescribing
- Interoperability
- Digital Health
---
