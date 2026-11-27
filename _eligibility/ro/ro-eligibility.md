---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use only by persons located in the United States.
  entity_types:
  - text: Our Services are intended for use by you only if you are 18 years of age or over.
    type: individual
  minimum_age:
    text: Our Services are intended for use by you only if you are 18 years of age or over.
    value: '18'
  restricted_uses:
  - summary: Not for emergency or crisis care
    text: DO NOT ACCESS THE SERVICES FOR EMERGENCY OR CRISIS CARE.
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
name: Ro
provenance_date: '2026-11-10'
provider_name: Ro
provider_slug: ro
slug: ro-eligibility
source_date: '2026-11-10'
source_filename: ro-eligibility.yml
source_heading: Eligibility
source_page: https://ro.co/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ro\naid: ro\nurl: https://ro.co/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: Our Services are intended for use by you only if you are 18 years of age or over.\nrestricted_uses:\n- summary: Not for emergency or crisis care\n  text: DO NOT ACCESS THE SERVICES FOR EMERGENCY OR CRISIS CARE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are\
  \ intended for use by you only if you are 18 years of age or over.\n"
source_yaml_url: https://artifacts.apis.io/ro/eligibility/ro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Telehealth
- Healthcare
- Digital Health
- Pharmacy
- Direct to Consumer
- Weight Management
- Fertility
---
