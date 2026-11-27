---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use Voquill. If you are under 18, you represent that your parent or legal guardian has reviewed and agreed to these Terms on your behalf.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use Voquill.
    value: '13'
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
name: Voquill
provenance_date: '2026-11-10'
provider_name: Voquill
provider_slug: voquill
slug: voquill-eligibility
source_date: '2026-11-10'
source_filename: voquill-eligibility.yml
source_heading: Eligibility
source_page: https://voquill.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voquill\naid: voquill\nurl: https://voquill.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use Voquill. If you are under 18, you represent that your parent or\n    legal guardian has reviewed and agreed to these Terms on your behalf.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use Voquill.\n"
source_yaml_url: https://artifacts.apis.io/voquill/eligibility/voquill-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Voquill's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Voice
- Dictation
- Speech-to-Text
- Artificial Intelligence
- Open Source
- Healthcare
- Pathology
- Productivity
---
