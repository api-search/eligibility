---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is controlled and operated from facilities in the United States. Company makes no representations that the Site is appropriate or available for use in other locations.
  entity_types:
  - text: If you open a Company account on behalf of a company, organization, or other entity, then (a) “you” includes you and that entity
    type: business
  - text: You may use the Site only if you can form a binding contract with Company
    type: individual
  minimum_age:
    text: Any use or access to the Site by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Embargoed countries and blocked persons
    text: You may not use the Site if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
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
name: DataVisor
provenance_date: '2026-11-09'
provider_name: DataVisor
provider_slug: datavisor
slug: datavisor-eligibility
source_date: '2026-11-09'
source_filename: datavisor-eligibility.yml
source_heading: Eligibility
source_page: https://www.datavisor.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DataVisor\naid: datavisor\nurl: https://www.datavisor.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is controlled and operated from facilities in the United States. Company makes no representations\n    that the Site is appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: If you open a Company account on behalf of a company, organization, or other entity, then (a) “you” includes\n    you and that entity\n- type: individual\n  text: You may use the Site only if you can form a binding contract with Company\n\
  restricted_uses:\n- summary: Embargoed countries and blocked persons\n  text: You may not use the Site if you are a resident of a country embargoed by the United States, or are a foreign\n    person or entity blocked or denied by the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Site by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/datavisor/eligibility/datavisor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from DataVisor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fraud Prevention
- AML
- Financial Crime
- Risk Management
- Machine Learning
- Artificial Intelligence
- Device Intelligence
- Banking
- Payments
- Compliance
---
