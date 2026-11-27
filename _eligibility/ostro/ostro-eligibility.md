---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You cannot access or use the Services if you are barred from receiving the Services under applicable law or have previously been suspended or removed from the Services.
    type: individual
  - text: If you are agreeing to these Terms of Use on behalf of an organization or entity, you represent and warrant that you are authorized to do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not medical advice
    text: Ostro is not a medical group. We do not provide medical advice or care.
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
name: Ostro
provenance_date: '2026-11-10'
provider_name: Ostro
provider_slug: ostro
slug: ostro-eligibility
source_date: '2026-11-10'
source_filename: ostro-eligibility.yml
source_heading: Eligibility
source_page: https://ostro.veeva.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ostro\naid: ostro\nurl: https://ostro.veeva.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You cannot access or use the Services if you are barred from receiving the Services under applicable law\n    or have previously been suspended or removed from the Services.\n- type: business\n  text: If you are agreeing to these Terms of Use on behalf of an organization or entity, you represent and warrant\n    that you are authorized to do so.\nrestricted_uses:\n- summary: Not medical advice\n  text: Ostro is not a medical\
  \ group. We do not provide medical advice or care.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ostro/eligibility/ostro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ostro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Pharmaceuticals
- Healthcare
- Artificial Intelligence
- Conversational AI
- Patient Engagement
- Marketing
- Software-as-a-Service
---
