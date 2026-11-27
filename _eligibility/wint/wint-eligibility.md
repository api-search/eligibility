---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer must not be a resident of a country embargoed by the U.S. government for use of Wint Materials.
  entity_types:
  - text: An individual entering into this Agreement on behalf of the Customer, represents that he/she has the right, authority and capacity to act on behalf of the Customer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data prohibited
    text: (a) shall ensure that no Customer Content includes or links to Sensitive Data
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
name: WINT
provenance_date: '2026-11-10'
provider_name: WINT
provider_slug: wint
slug: wint-eligibility
source_date: '2026-11-10'
source_filename: wint-eligibility.yml
source_heading: Eligibility
source_page: https://wint.ai/customer-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WINT\naid: wint\nurl: https://wint.ai/customer-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer must not be a resident of a country embargoed by the U.S. government for use of Wint Materials.\nentity_types:\n- type: business\n  text: An individual entering into this Agreement on behalf of the Customer, represents that he/she has the right,\n    authority and capacity to act on behalf of the Customer\nrestricted_uses:\n- summary: Sensitive data prohibited\n  text: (a) shall ensure that no Customer Content includes or links to Sensitive Data\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wint/eligibility/wint-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from WINT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Water Management
- Leak Detection
- Water Intelligence
- IoT
- Facilities Management
- Sustainability
- Anomaly Detection
---
