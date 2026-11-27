---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export: Customer agrees not to export ... to countries as to which the United States maintains an embargo'
  entity_types:
  - text: Customer represents that the individual executing the Order Form is entering into this Agreement on behalf of the entity identified on the Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No publication without approval
    text: All publications based on Customer’s use of the Data must be approved by the Company in writing in advance
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
name: Holmusk
provenance_date: '2026-11-09'
provider_name: Holmusk
provider_slug: holmusk
slug: holmusk-eligibility
source_date: '2026-11-09'
source_filename: holmusk-eligibility.yml
source_heading: Eligibility
source_page: https://www.neuroblu.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Holmusk\naid: holmusk\nurl: https://www.neuroblu.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export: Customer agrees not to export ... to countries as to which the United States maintains an embargo'\nentity_types:\n- type: business\n  text: Customer represents that the individual executing the Order Form is entering into this Agreement on behalf\n    of the entity identified on the Order Form\nrestricted_uses:\n- summary: No publication without approval\n  text: All publications based on Customer’s use of the Data must be approved by the Company in writing\
  \ in advance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/holmusk/eligibility/holmusk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Holmusk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Real-World Evidence
- Behavioral Health
- Mental Health
- Neuropsychiatry
- Clinical Data
- Data Analytics
- Life Sciences
- HIPAA
---
