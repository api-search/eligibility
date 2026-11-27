---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We are granting you, as an individual user, the right to use the Software and the Services as set out above.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to accept these Terms and use the Software.
    value: '18'
  restricted_uses:
  - summary: Not medical advice or treatment
    text: the Company does not provide medical advice, diagnosis, or treatment through the Software or any of its functionalities.
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
name: Limbic
provenance_date: '2026-11-09'
provider_name: Limbic
provider_slug: limbic
slug: limbic-eligibility
source_date: '2026-11-09'
source_filename: limbic-eligibility.yml
source_heading: Eligibility
source_page: https://www.limbic.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Limbic\naid: limbic\nurl: https://www.limbic.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We are granting you, as an individual user, the right to use the Software and the Services as set out above.\nrestricted_uses:\n- summary: Not medical advice or treatment\n  text: the Company does not provide medical advice, diagnosis, or treatment through the Software or any of its\n    functionalities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You\
  \ must be at least 18 years of age to accept these Terms and use the Software.\n"
source_yaml_url: https://artifacts.apis.io/limbic/eligibility/limbic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Limbic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Artificial Intelligence
- Clinical Decision Support
- Digital Health
- Medical Devices
- Behavioral Health
- NHS
---
