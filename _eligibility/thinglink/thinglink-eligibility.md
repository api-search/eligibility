---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Service is not intended for consumer or personal use, but for business or organizational use only
    type: business
  minimum_age:
    text: Any use or access to the Service by anyone under 13 without Consent is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Commercial solicitation
    text: using the Service for any commercial solicitation purposes
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
name: Thinglink
provenance_date: '2026-11-10'
provider_name: Thinglink
provider_slug: thinglink
slug: thinglink-eligibility
source_date: '2026-11-10'
source_filename: thinglink-eligibility.yml
source_heading: Eligibility
source_page: https://www.thinglink.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thinglink\naid: thinglink\nurl: https://www.thinglink.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the Service is not intended for consumer or personal use, but for business or organizational use only\nrestricted_uses:\n- summary: Commercial solicitation\n  text: using the Service for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under 13 without Consent is strictly\
  \ prohibited and in violation\n    of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/thinglink/eligibility/thinglink-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Thinglink's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Interactive Media
- Immersive Learning
- Virtual Reality
- 360 Video
- Corporate Training
- No-Code
---
