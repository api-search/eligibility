---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: By using the Platform or the Services represent and warrant that you are 1) a legal resident of the United States, 2) of legal age to form a binding contract with Klover
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You agree to use the Platform and Services only for lawful purposes.
  verification:
    approval_required: false
    kyb: null
    kyc: true
    text: In order to use certain Services, Klover may be required to verify your identity. You authorize us to make any inquiries we consider necessary to validate your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Klover
provenance_date: '2026-11-09'
provider_name: Klover
provider_slug: klover
slug: klover-eligibility
source_date: '2026-11-09'
source_filename: klover-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinklover.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klover\naid: klover\nurl: https://www.joinklover.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: By using the Platform or the Services represent and warrant that you are 1) a legal resident of the United\n    States, 2) of legal age to form a binding contract with Klover\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Lawful use only\n  text: You agree to use the Platform and Services only for lawful purposes.\nverification:\n\
  \  kyc: true\n  kyb: null\n  approval_required: false\n  text: In order to use certain Services, Klover may be required to verify your identity. You authorize us to make\n    any inquiries we consider necessary to validate your identity.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/klover/eligibility/klover-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Klover's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Cash Advance
- Budgeting
- Mobile App
---
