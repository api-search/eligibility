---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Such use is limited to Customer’s internal business use
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer shall not, directly or indirectly, export, re-export, or release the Services or the underlying software or technology to, or make the Services or the underlying software or technology accessible from, any jurisdiction or country to which export, re-export, or release is prohibited by law, rule, or regulation.
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
name: Con.doit
provenance_date: '2026-11-09'
provider_name: Con.doit
provider_slug: condoit
slug: condoit-eligibility
source_date: '2026-11-09'
source_filename: condoit-eligibility.yml
source_heading: Eligibility
source_page: https://www.condoit.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Con.doit\naid: condoit\nurl: https://www.condoit.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Such use is limited to Customer’s internal business use\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer shall not, directly or indirectly, export, re-export, or release the Services or the underlying\n    software or technology to, or make the Services or the underlying software or technology accessible from, any\n    jurisdiction or country to which export, re-export, or release is prohibited by law,\
  \ rule, or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/condoit/eligibility/condoit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Con.doit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Electrical
- Contractors
- Field Service Management
- Facility Management
- Thermography
- NFPA 70B
- Asset Management
- Compliance
---
