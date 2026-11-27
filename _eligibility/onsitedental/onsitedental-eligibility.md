---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that you have the authority to bind such entity to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: you agree to use this for lawful purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If, in our judgment, your purchase constitutes a high-risk transaction, we will require you to provide us with a copy of your valid government-issued photo identification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Onsitedental
provenance_date: '2026-11-10'
provider_name: Onsitedental
provider_slug: onsitedental
slug: onsitedental-eligibility
source_date: '2026-11-10'
source_filename: onsitedental-eligibility.yml
source_heading: Eligibility
source_page: https://onsitedental.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onsitedental\naid: onsitedental\nurl: https://onsitedental.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that\n    you have the authority to bind such entity to this Agreement\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you agree to use this for lawful purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If, in our judgment, your purchase constitutes a high-risk transaction,\
  \ we will require you to provide us\n    with a copy of your valid government-issued photo identification\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onsitedental/eligibility/onsitedental-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Onsitedental's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Dental
- Healthcare
- Employee Benefits
- Corporate Wellness
- Oral Health
- Mobile Health
- Workplace Health
---
