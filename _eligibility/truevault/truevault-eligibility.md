---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are entering into this TOU on behalf of your employer, or any other entity or person, you are duly authorized by your employer, such other entity or such other person to enter into this TOU
    type: business
  minimum_age:
    text: Unless expressly permitted by supplemental terms, our sites and services are intended for general audiences 18 years of age and older, and access or use by anyone younger is not authorized.
    value: '18'
  restricted_uses:
  - summary: High-risk uses such as life-safety systems
    text: (d) use the Services in any manner wherein the failure or defect in the Services could lead to death or serious bodily injury of any person, or to severe physical or environmental damage, as such use is strictly prohibited.
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
name: TrueVault
provenance_date: '2026-11-10'
provider_name: TrueVault
provider_slug: truevault
slug: truevault-eligibility
source_date: '2026-11-10'
source_filename: truevault-eligibility.yml
source_heading: Eligibility
source_page: https://www.truevault.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueVault\naid: truevault\nurl: https://www.truevault.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are entering into this TOU on behalf of your employer, or any other entity or person, you are duly\n    authorized by your employer, such other entity or such other person to enter into this TOU\nrestricted_uses:\n- summary: High-risk uses such as life-safety systems\n  text: (d) use the Services in any manner wherein the failure or defect in the Services could lead to death or\n    serious bodily injury of any\
  \ person, or to severe physical or environmental damage, as such use is strictly\n    prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Unless expressly permitted by supplemental terms, our sites and services are intended for general audiences\n    18 years of age and older, and access or use by anyone younger is not authorized.\n"
source_yaml_url: https://artifacts.apis.io/truevault/eligibility/truevault-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TrueVault's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Privacy
- Security
- Compliance
- HIPAA
- Data Storage
- Encryption
- Identity
- PII
---
