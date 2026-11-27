---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: those employees, agents and independent contractors of the Subscriber who are authorized by the Subscriber to use the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful material
    text: 'The Subscriber shall not access, store, distribute or transmit any Viruses, or any material during the course of its use of the Services that: (a) is unlawful, harmful'
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
name: Complyance
provenance_date: '2026-11-09'
provider_name: Complyance
provider_slug: complyance
slug: complyance-eligibility
source_date: '2026-11-09'
source_filename: complyance-eligibility.yml
source_heading: Eligibility
source_page: https://www.complyance.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Complyance\naid: complyance\nurl: https://www.complyance.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: those employees, agents and independent contractors of the Subscriber who are authorized by the Subscriber\n    to use the Services\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: 'The Subscriber shall not access, store, distribute or transmit any Viruses, or any material during the\n    course of its use of the Services that: (a) is unlawful, harmful'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/complyance/eligibility/complyance-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Complyance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Governance Risk Compliance
- GRC
- Compliance
- Risk Management
- Security
- Vendor Management
- Audit
- Policy Management
---
