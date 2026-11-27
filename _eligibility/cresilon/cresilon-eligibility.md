---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Purchases of products are only available to licensed healthcare providers through our authorized distributors.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No impersonation or cloaking identity
    text: You may not impersonate or attempt to impersonate us, any employee, another user, or any other person or entity
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
name: Cresilon
provenance_date: '2026-11-09'
provider_name: Cresilon
provider_slug: cresilon
slug: cresilon-eligibility
source_date: '2026-11-09'
source_filename: cresilon-eligibility.yml
source_heading: Eligibility
source_page: https://cresilon.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cresilon\naid: cresilon\nurl: https://cresilon.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Purchases of products are only available to licensed healthcare providers through our authorized distributors.\nrestricted_uses:\n- summary: No impersonation or cloaking identity\n  text: You may not impersonate or attempt to impersonate us, any employee, another user, or any other person or\n    entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cresilon/eligibility/cresilon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Cresilon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Medical Devices
- Health
- Hemostasis
- Wound Care
- Trauma Care
- Veterinary
- Life Sciences
- Manufacturing
---
