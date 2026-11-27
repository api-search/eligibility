---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: being either an individual or organisation using our services (“Client”)
    type: individual
  - text: being either an individual or organisation using our services (“Client”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or immoral activity
    text: You must not use the Services or Platform of Intellithing if the work or project related to the use of the Platform relates to any illegal or immoral activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you are accepted by Intellithing as a Client, you will be entitled to use our Services and access our Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: INTELLITHING
provenance_date: '2026-11-09'
provider_name: INTELLITHING
provider_slug: intellithing
slug: intellithing-eligibility
source_date: '2026-11-09'
source_filename: intellithing-eligibility.yml
source_heading: Eligibility
source_page: https://intellithing.tech/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: INTELLITHING\naid: intellithing\nurl: https://intellithing.tech/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: being either an individual or organisation using our services (“Client”)\n- type: business\n  text: being either an individual or organisation using our services (“Client”)\nrestricted_uses:\n- summary: No illegal or immoral activity\n  text: You must not use the Services or Platform of Intellithing if the work or project related to the use of the\n    Platform relates to any illegal or immoral activity\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you are accepted by Intellithing as a Client, you will be entitled to use our Services and access our\n    Platform.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/intellithing/eligibility/intellithing-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from INTELLITHING's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- LLM
- Platform
---
