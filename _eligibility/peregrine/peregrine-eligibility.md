---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  - text: You will only use the Website for your own personal or business use
    type: business
  minimum_age:
    text: The Website is only intended for use by those 18 and over.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: If your use of the Website is prohibited by applicable laws, then you aren’t authorized to use the Website.
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
name: Peregrine
provenance_date: '2026-11-10'
provider_name: Peregrine
provider_slug: peregrine
slug: peregrine-eligibility
source_date: '2026-11-10'
source_filename: peregrine-eligibility.yml
source_heading: Eligibility
source_page: https://peregrine.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peregrine\naid: peregrine\nurl: https://peregrine.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n- type: business\n  text: You will only use the Website for your own personal or business use\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: If your use of the Website is prohibited by applicable laws, then you aren’t authorized to use the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is only intended for use by those 18 and over.\n"
source_yaml_url: https://artifacts.apis.io/peregrine/eligibility/peregrine-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Peregrine's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infrastructure
- Public Safety
- Law Enforcement
- Government
- Data Integration
- Artificial Intelligence
- Situational Awareness
- Emergency Response
---
