---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: If you are using the Services and are a resident of the United Kingdom or European Union, click here (as these Terms do not apply to you).
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use only
    text: Sword grants you a personal, non-exclusive, non-transferable, non-sublicensable, revocable, limited license to use the Services for your own personal use only and not for any business purpose or commercial activity.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Sword and the Professionals have the right to accept or reject any applicant for the Services, in their sole and complete discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sword
provenance_date: '2026-11-10'
provider_name: Sword
provider_slug: sword
slug: sword-eligibility
source_date: '2026-11-10'
source_filename: sword-eligibility.yml
source_heading: Eligibility
source_page: https://legal.swordhealth.com/members/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sword\naid: sword\nurl: https://legal.swordhealth.com/members/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: If you are using the Services and are a resident of the United Kingdom or European Union, click here (as\n    these Terms do not apply to you).\nentity_types: []\nrestricted_uses:\n- summary: Personal use only\n  text: Sword grants you a personal, non-exclusive, non-transferable, non-sublicensable, revocable, limited license\n    to use the Services for your own personal use only and not for any business purpose or commercial activity.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Sword and the Professionals have the right to accept or reject any applicant for the Services, in their\n    sole and complete discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sword/eligibility/sword-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Sword's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Healthcare
- Physical Therapy
- Musculoskeletal
- Telehealth
- Artificial Intelligence
- Remote Patient Monitoring
---
