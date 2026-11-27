---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Employees can access and view benefits
    type: individual
  minimum_age:
    text: You represent that you are (i) of legal age to form a binding contract
    value: legal age
  restricted_uses:
  - summary: No use by persons barred by law
    text: You represent that you are (i) of legal age to form a binding contract; and (ii) not a person barred from using the Application under the laws of the United States, your place of residence or any other applicable jurisdiction.
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
name: Sana Benefits
provenance_date: '2026-11-10'
provider_name: Sana Benefits
provider_slug: sana-benefits
slug: sana-benefits-eligibility
source_date: '2026-11-10'
source_filename: sana-benefits-eligibility.yml
source_heading: Eligibility
source_page: https://www.sanabenefits.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sana Benefits\naid: sana-benefits\nurl: https://www.sanabenefits.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Employees can access and view benefits\nrestricted_uses:\n- summary: No use by persons barred by law\n  text: You represent that you are (i) of legal age to form a binding contract; and (ii) not a person barred from\n    using the Application under the laws of the United States, your place of residence or any other applicable jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: legal age\n  text: You represent that you are (i) of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/sana-benefits/eligibility/sana-benefits-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sana Benefits's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- United States
- Health Insurance
- Employee Benefits
- Benefits Administration
- Small Business
- Level-Funded Plans
- Insurtech
- Brokerage
- Virtual Primary Care
---
