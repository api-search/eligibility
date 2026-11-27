---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer shall not permit access or use any Platform Services in a U.S. embargoed country or in violation of any U.S. export law or regulation.
  entity_types:
  - text: if you are an individual acting on behalf of an entity, you represent and warrant that you have the authority to enter into this Terms of Service on behalf of that entity and to legally bind that entity.
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least 18 years of age or otherwise have the power to enter into a binding contract in your country of residence
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: Customer shall not permit access or use any Platform Services in a U.S. embargoed country or in violation of any U.S. export law or regulation.
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
name: Monograph
provenance_date: '2026-11-10'
provider_name: Monograph
provider_slug: monograph
slug: monograph-eligibility
source_date: '2026-11-10'
source_filename: monograph-eligibility.yml
source_heading: Eligibility
source_page: https://monograph.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Monograph\naid: monograph\nurl: https://monograph.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer shall not permit access or use any Platform Services in a U.S. embargoed country or in violation\n    of any U.S. export law or regulation.\nentity_types:\n- type: individual\n  text: if you are an individual acting on behalf of an entity, you represent and warrant that you have the authority\n    to enter into this Terms of Service on behalf of that entity and to legally bind that entity.\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer\
  \ shall not permit access or use any Platform Services in a U.S. embargoed country or in violation\n    of any U.S. export law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years of age or otherwise have the power to enter into\n    a binding contract in your country of residence\n"
source_yaml_url: https://artifacts.apis.io/monograph/eligibility/monograph-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Monograph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Architecture
- Engineering
- AEC
- Firm Management
- Project Management
- Time Tracking
- Invoicing
- Software-as-a-Service
---
