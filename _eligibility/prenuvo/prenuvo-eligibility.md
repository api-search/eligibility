---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that the Services or Content are appropriate or available for use in locations outside of the United States.
  entity_types:
  - text: By participating in the Text Service, you acknowledge and agree that you are eighteen (18) years of age or older.
    type: individual
  minimum_age:
    text: you acknowledge and agree that you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Platform only for lawful purposes and in accordance with these Terms.
  - summary: No commercial use of Platform
    text: You may not access or use for any commercial purposes any part of the Platform or Services Content.
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
name: Prenuvo
provenance_date: '2026-11-10'
provider_name: Prenuvo
provider_slug: prenuvo
slug: prenuvo-eligibility
source_date: '2026-11-10'
source_filename: prenuvo-eligibility.yml
source_heading: Eligibility
source_page: https://prenuvo.com/terms-and-privacy?section=terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prenuvo\naid: prenuvo\nurl: https://prenuvo.com/terms-and-privacy?section=terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that the Services or Content are appropriate or available for use in locations\n    outside of the United States.\nentity_types:\n- type: individual\n  text: By participating in the Text Service, you acknowledge and agree that you are eighteen (18) years of age\n    or older.\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Platform only for lawful purposes and in accordance with\
  \ these Terms.\n- summary: No commercial use of Platform\n  text: You may not access or use for any commercial purposes any part of the Platform or Services Content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you acknowledge and agree that you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/prenuvo/eligibility/prenuvo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Prenuvo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Medical Imaging
- MRI
- Preventive Health
- Diagnostics
- Biomarkers
- Wellness
---
