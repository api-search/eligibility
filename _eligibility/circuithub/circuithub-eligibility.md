---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not a person barred from receiving the Services under the laws of the United States or other countries including the country in which you are resident or from which you use the Services
  entity_types:
  - text: In order for a natural born person to be eligible to become a user of the Services
    type: individual
  - text: If you are using the Services on behalf or at the direction of a corporation, limited liability company, partnership, trust or other legal entity
    type: business
  minimum_age:
    text: are no less than 18 years of age or are an emancipated minor
    value: '18'
  restricted_uses:
  - summary: Competitors barred
    text: are not a competitor of CircuitHub and/or are not using the Services for reasons that are adverse to, or can reasonably be expected to compete with, CircuitHub
  - summary: One account per user
    text: will only maintain one (1) Account at any given time
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
name: CircuitHub
provenance_date: '2026-11-09'
provider_name: CircuitHub
provider_slug: circuithub
slug: circuithub-eligibility
source_date: '2026-11-09'
source_filename: circuithub-eligibility.yml
source_heading: Eligibility
source_page: https://www.circuithub.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CircuitHub\naid: circuithub\nurl: https://www.circuithub.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not a person barred from receiving the Services under the laws of the United States or other countries\n    including the country in which you are resident or from which you use the Services\nentity_types:\n- type: individual\n  text: In order for a natural born person to be eligible to become a user of the Services\n- type: business\n  text: If you are using the Services on behalf or at the direction of a corporation, limited liability company,\n\
  \    partnership, trust or other legal entity\nrestricted_uses:\n- summary: Competitors barred\n  text: are not a competitor of CircuitHub and/or are not using the Services for reasons that are adverse to, or\n    can reasonably be expected to compete with, CircuitHub\n- summary: One account per user\n  text: will only maintain one (1) Account at any given time\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are no less than 18 years of age or are an emancipated minor\n"
source_yaml_url: https://artifacts.apis.io/circuithub/eligibility/circuithub-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from CircuitHub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Electronics Manufacturing
- PCB Assembly
- Hardware
- Robotics
- Manufacturing
- Prototyping
- Supply Chain
---
