---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country that is subject to the United States government embargo
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  - source: https://arcwise.app/terms-paid
    text: Terms apply only to Customers that have entered into a Contract with Arcwise.
    type: business
  minimum_age:
    text: You represent that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Under-18 users not permitted
    text: The Company does not permit those under 18 to use the Service.
  - source: https://arcwise.app/terms-paid
    summary: No unlawful use or sharing of login credentials
    text: (e) use the Service in any way that violates any applicable federal, state, local or international law or regulation, including but not limited to CANSPAM
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
name: Arcwise
provenance_date: '2026-11-09'
provider_name: Arcwise
provider_slug: arcwise
slug: arcwise-eligibility
source_date: '2026-11-09'
source_filename: arcwise-eligibility.yml
source_heading: Eligibility
source_page: https://arcwise.app/terms-free
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arcwise\naid: arcwise\nurl: https://arcwise.app/terms-free\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://arcwise.app/terms-free\n  - https://arcwise.app/terms-paid\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country that is subject to the United States government embargo\nentity_types:\n- type: business\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\n- type: business\n  text: Terms apply only to Customers that have entered into a Contract with\
  \ Arcwise.\n  source: https://arcwise.app/terms-paid\nrestricted_uses:\n- summary: Under-18 users not permitted\n  text: The Company does not permit those under 18 to use the Service.\n- summary: No unlawful use or sharing of login credentials\n  text: (e) use the Service in any way that violates any applicable federal, state, local or international law or\n    regulation, including but not limited to CANSPAM\n  source: https://arcwise.app/terms-paid\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/arcwise/eligibility/arcwise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Arcwise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Metrics
- Analytics
- Decision-Making
- Business Intelligence
- Root Cause Analysis
---
