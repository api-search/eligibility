---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: intended solely for use by Australian residents who are authorised users under separate contractual arrangements
  entity_types:
  - text: authorised users under separate contractual arrangements
    type: other
  minimum_age:
    text: null
    value: null
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
name: MedicalDirector
provenance_date: '2026-11-10'
provider_name: MedicalDirector
provider_slug: medical-director
slug: medical-director-eligibility
source_date: '2026-11-10'
source_filename: medical-director-eligibility.yml
source_heading: Eligibility
source_page: https://medicaldirector.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MedicalDirector\naid: medical-director\nurl: https://medicaldirector.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: intended solely for use by Australian residents who are authorised users under separate contractual arrangements\nentity_types:\n- type: other\n  text: authorised users under separate contractual arrangements\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/medical-director/eligibility/medical-director-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from MedicalDirector's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Australia
- Electronic Health Records
- FHIR
- Interoperability
- Practice Management
- Primary Care
- Clinical Software
- Digital Health
---
