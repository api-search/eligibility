---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are accessing or using the Site on behalf of any entity, You represent and warrant that You are authorized to accept these Terms of Use on such entity's behalf
    type: business
  minimum_age:
    text: You are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Patient care use of Vumedi AI
    text: You are not permitted to use Vumedi AI for direct patient care.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Upon Our acceptance of Your registration form, in Our sole discretion, We will provide You with log-in identification and a unique password
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VuMedi
provenance_date: '2026-11-10'
provider_name: VuMedi
provider_slug: vumedi
slug: vumedi-eligibility
source_date: '2026-11-10'
source_filename: vumedi-eligibility.yml
source_heading: Eligibility
source_page: https://www.vumedi.com/public/pages/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VuMedi\naid: vumedi\nurl: https://www.vumedi.com/public/pages/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are accessing or using the Site on behalf of any entity, You represent and warrant that You are authorized\n    to accept these Terms of Use on such entity's behalf\nrestricted_uses:\n- summary: Patient care use of Vumedi AI\n  text: You are not permitted to use Vumedi AI for direct patient care.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Upon Our acceptance of Your registration form,\
  \ in Our sole discretion, We will provide You with log-in identification\n    and a unique password\nminimum_age:\n  value: '18'\n  text: You are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/vumedi/eligibility/vumedi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from VuMedi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Education
- Continuing Medical Education
- Video
- Physicians
- Life Sciences
- Content Platform
---
