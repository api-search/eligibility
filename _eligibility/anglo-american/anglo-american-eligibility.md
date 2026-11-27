---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer user, please note that we only provide our site for domestic and private use.
    type: individual
  - text: 'If you are a business user, please note that in particular, we also will not be liable for: loss of profits, sales, business, or revenue'
    type: business
  minimum_age:
    text: The use of any of our interactive services by a minor is subject to the consent of their parent or guardian.
    value: null
  restricted_uses:
  - summary: No commercial use by consumers
    text: You agree not to use our Site for any commercial or business purposes
  - summary: Lawful purposes only
    text: You may use the Site only for lawful purposes.
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
name: Anglo American
provenance_date: '2026-11-09'
provider_name: Anglo American
provider_slug: anglo-american
slug: anglo-american-eligibility
source_date: '2026-11-09'
source_filename: anglo-american-eligibility.yml
source_heading: Eligibility
source_page: https://www.angloamerican.com/site-services/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anglo American\naid: anglo-american\nurl: https://www.angloamerican.com/site-services/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer user, please note that we only provide our site for domestic and private use.\n- type: business\n  text: 'If you are a business user, please note that in particular, we also will not be liable for: loss of profits,\n    sales, business, or revenue'\nrestricted_uses:\n- summary: No commercial use by consumers\n  text: You agree not to use our Site for any commercial\
  \ or business purposes\n- summary: Lawful purposes only\n  text: You may use the Site only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The use of any of our interactive services by a minor is subject to the consent of their parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/anglo-american/eligibility/anglo-american-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Anglo American's own page on 2026-11-09.
synthetic: false
tags:
- Mining
- Metals
- Sustainability
- Global
- Resources
---
