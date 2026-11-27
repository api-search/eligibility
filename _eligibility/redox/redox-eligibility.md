---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
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
name: Redox
provenance_date: '2026-11-10'
provider_name: Redox
provider_slug: redox
slug: redox-eligibility
source_date: '2026-11-10'
source_filename: redox-eligibility.yml
source_heading: Eligibility
source_page: https://redoxengine.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Redox\naid: redox\nurl: https://redoxengine.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/redox/eligibility/redox-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Redox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Interoperability
- FHIR
- Electronic Health Records
- Health Data
- Integration
- HL7
- Digital Health
- Healthcare API
---
