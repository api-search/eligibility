---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Website only if you are at least 13 years old.
    type: individual
  minimum_age:
    text: You may use the Website only if you are at least 13 years old. If you are under the age of 18 (or the age of legal majority where you live), you may use the Website only with the consent of your parent or legal guardian.
    value: '13'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You must not access or use for any commercial purposes any part of the Website or any services or materials available through the Website.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you register for an account, you must provide accurate account information and promptly update this information if it changes.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TYB
provenance_date: '2026-11-10'
provider_name: TYB
provider_slug: tyb
slug: tyb-eligibility
source_date: '2026-11-10'
source_filename: tyb-eligibility.yml
source_heading: Eligibility
source_page: https://www.tyb.xyz/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TYB\naid: tyb\nurl: https://www.tyb.xyz/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Website only if you are at least 13 years old.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: You must not access or use for any commercial purposes any part of the Website or any services or materials\n    available through the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you register for an account, you must provide accurate account information and promptly\
  \ update this information\n    if it changes.\nminimum_age:\n  value: '13'\n  text: You may use the Website only if you are at least 13 years old. If you are under the age of 18 (or the age\n    of legal majority where you live), you may use the Website only with the consent of your parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/tyb/eligibility/tyb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from TYB's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Rewards
- Community
- Engagement
- Platform
---
