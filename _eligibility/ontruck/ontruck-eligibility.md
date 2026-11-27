---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Natural person or legal entity that, within the framework of their professional activity, contracts the Carriage Service
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer use excluded
    text: The Shipper contracts the Carriage Service in the scope of performance of its commercial, professional or business activity and not as the end consumer for the purposes set out in the law.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Ontruck's authorisation is required for an Effective Shipper to register as a User and Ontruck reserves the right to reject the registration of any shipper
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ontruck
provenance_date: '2026-11-10'
provider_name: Ontruck
provider_slug: ontruck
slug: ontruck-eligibility
source_date: '2026-11-10'
source_filename: ontruck-eligibility.yml
source_heading: Eligibility
source_page: https://www.ontruck.com/en/shippers/terms-and-conditions-for-shippers
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ontruck\naid: ontruck\nurl: https://www.ontruck.com/en/shippers/terms-and-conditions-for-shippers\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Natural person or legal entity that, within the framework of their professional activity, contracts the\n    Carriage Service\nrestricted_uses:\n- summary: Consumer use excluded\n  text: The Shipper contracts the Carriage Service in the scope of performance of its commercial, professional or\n    business activity and not as the end consumer for the purposes set out in the law.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: Ontruck's authorisation is required for an Effective Shipper to register as a User and Ontruck reserves\n    the right to reject the registration of any shipper\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ontruck/eligibility/ontruck-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Ontruck's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Freight
- Road Transport
- Trucking
- Supply Chain
- Transport Management
- Artificial Intelligence
- Spain
- Europe
---
