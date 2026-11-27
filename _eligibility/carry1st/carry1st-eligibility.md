---
api_specs:
- filename: carry1st-authentication-api-openapi.yml
  format: yaml
  label: Carry1st Authentication API
  slug: carry1st-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carry1st/openapi/carry1st-authentication-api-openapi.yml
- filename: carry1st-payment-methods-api-openapi.yml
  format: yaml
  label: Carry1st Payment Methods API
  slug: carry1st-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carry1st/openapi/carry1st-payment-methods-api-openapi.yml
- filename: carry1st-payments-api-openapi.yml
  format: yaml
  label: Carry1st Payments API
  slug: carry1st-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carry1st/openapi/carry1st-payments-api-openapi.yml
- filename: carry1st-refunds-api-openapi.yml
  format: yaml
  label: Carry1st Refunds API
  slug: carry1st-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carry1st/openapi/carry1st-refunds-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: By visiting, accessing, downloading, installing or otherwise using Carry1st Services, you acknowledge that you are not a national of, or resident within, any of the countries that are subject to trade embargo under these laws and regulations
  entity_types:
  - text: Carry1st Services are NOT intended for users under 13 years of age
    type: individual
  minimum_age:
    text: you are NOT authorized to use Carry1st Services if you are under 13 years of age. If you are between the ages of 13 and 17, or under the age of majority where you live, you represent that your legal guardian has reviewed and agreed to these Terms.
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited uses
    text: You understand and agree that Carry1st Services may be used only for lawful purposes consistent with their intended uses and in accordance with these Terms
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
name: Carry1st
provenance_date: '2026-11-09'
provider_name: Carry1st
provider_slug: carry1st
slug: carry1st-eligibility
source_date: '2026-11-09'
source_filename: carry1st-eligibility.yml
source_heading: Eligibility
source_page: https://www.carry1st.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carry1st\naid: carry1st\nurl: https://www.carry1st.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: By visiting, accessing, downloading, installing or otherwise using Carry1st Services, you acknowledge that\n    you are not a national of, or resident within, any of the countries that are subject to trade embargo under\n    these laws and regulations\nentity_types:\n- type: individual\n  text: Carry1st Services are NOT intended for users under 13 years of age\nrestricted_uses:\n- summary: Unlawful or prohibited uses\n  text: You understand and agree that Carry1st\
  \ Services may be used only for lawful purposes consistent with their\n    intended uses and in accordance with these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are NOT authorized to use Carry1st Services if you are under 13 years of age. If you are between the\n    ages of 13 and 17, or under the age of majority where you live, you represent that your legal guardian has reviewed\n    and agreed to these Terms.\n"
source_yaml_url: https://artifacts.apis.io/carry1st/eligibility/carry1st-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Carry1st's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Payment Gateway
- Fintech
- Gaming
- Mobile Games
- Africa
- Digital Commerce
- Merchant of Record
- Games Publishing
---
