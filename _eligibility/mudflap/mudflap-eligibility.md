---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for users located within the United States. Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: a. use the Service for any illegal purpose or in violation of any local, state, national, or international law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Mudflap may seek pre-authorization of your payment method prior to your purchase to verify that the payment method is valid and has the necessary funds or credit available to cover your purchase.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mudflap
provenance_date: '2026-11-10'
provider_name: Mudflap
provider_slug: mudflap
slug: mudflap-eligibility
source_date: '2026-11-10'
source_filename: mudflap-eligibility.yml
source_heading: Eligibility
source_page: https://www.mudflapinc.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mudflap\naid: mudflap\nurl: https://www.mudflapinc.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for users located within the United States. Access to the Service from countries\n    or territories or by individuals where such access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority\
  \ to bind you to these Terms\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: a. use the Service for any illegal purpose or in violation of any local, state, national, or international\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Mudflap may seek pre-authorization of your payment method prior to your purchase to verify that the payment\n    method is valid and has the necessary funds or credit available to cover your purchase.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/mudflap/eligibility/mudflap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Mudflap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Fuel
- Trucking
- Payments
- Fleet Management
- Logistics
- Fuel Card
---
