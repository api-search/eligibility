---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Platform is operated from within the United States.
  entity_types:
  - text: If you are using the Platform on behalf of a business, that business accepts this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You may use the Platform only for lawful, personal, non-commercial purposes
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
name: Pathai
provenance_date: '2026-11-10'
provider_name: Pathai
provider_slug: pathai
slug: pathai-eligibility
source_date: '2026-11-10'
source_filename: pathai-eligibility.yml
source_heading: Eligibility
source_page: https://www.pathai.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pathai\naid: pathai\nurl: https://www.pathai.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Platform is operated from within the United States.\nentity_types:\n- type: business\n  text: If you are using the Platform on behalf of a business, that business accepts this Agreement.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You may use the Platform only for lawful, personal, non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pathai/eligibility/pathai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pathai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Machine Learning
- Pathology
- Digital Diagnostics
- Life Sciences
- Medical Imaging
---
