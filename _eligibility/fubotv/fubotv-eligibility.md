---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years of age or older or have the permission of a parent or guardian who is over the age of 18
    type: individual
  - text: If you access or use the Services or register an Account on behalf of a company, principal, or other entity, you represent that you have authority to bind such entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older or have the permission of a parent or guardian who is over the age of 18
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: solely for your own lawful, personal, non-commercial uses
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Approval of Your request to establish and maintain any Account will be at the sole discretion of Fubo.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: fuboTV
provenance_date: '2026-11-09'
provider_name: fuboTV
provider_slug: fubotv
slug: fubotv-eligibility
source_date: '2026-11-09'
source_filename: fubotv-eligibility.yml
source_heading: Eligibility
source_page: https://legal.fubo.tv/policies/en-US/?name=terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fuboTV\naid: fubotv\nurl: https://legal.fubo.tv/policies/en-US/?name=terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older or have the permission of a parent or guardian who is over the age\n    of 18\n- type: business\n  text: If you access or use the Services or register an Account on behalf of a company, principal, or other entity,\n    you represent that you have authority to bind such entity\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text:\
  \ solely for your own lawful, personal, non-commercial uses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Approval of Your request to establish and maintain any Account will be at the sole discretion of Fubo.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older or have the permission of a parent or guardian who is over the age\n    of 18\n"
source_yaml_url: https://artifacts.apis.io/fubotv/eligibility/fubotv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from fuboTV's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Streaming
- Live TV
- Sports
- Media
- Entertainment
- OTT
- Video
---
