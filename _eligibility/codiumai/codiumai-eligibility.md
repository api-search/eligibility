---
api_specs:
- filename: codiumai-api-reference-api-openapi.yml
  format: yaml
  label: Codiumai API reference API
  slug: codiumai-api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codiumai/openapi/codiumai-api-reference-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Governing law differs for customers located outside North America versus in North America; no country list is stated.
  entity_types:
  - text: if you are an individual or an individual accepting these Terms on behalf of a legal entity, that you are at least 18 years old or of sufficient legal age to accept these Terms in accordance with the laws of your jurisdiction.
    type: individual
  - text: If You subscribed to Qodo under the Enterprise subscription plan and above or entered into an offline order form with Qodo, these Terms will not apply
    type: business
  minimum_age:
    text: if you are an individual or an individual accepting these Terms on behalf of a legal entity, that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No sharing of personal or health data as input
    text: You will not share Personal Data with the Platform as Input, nor will share with us any “protected health information” or Personal Data which constitutes “sensitive Personal Data” under applicable law without Our prior written consent
  - summary: No harvesting personal data
    text: harvest or collect Personal Data (as defined below) without their express consent or other legal basis
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must register and establish an account with Qodo in order to use the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Codiumai
provenance_date: '2026-11-09'
provider_name: Codiumai
provider_slug: codiumai
slug: codiumai-eligibility
source_date: '2026-11-09'
source_filename: codiumai-eligibility.yml
source_heading: Eligibility
source_page: https://www.qodo.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codiumai\naid: codiumai\nurl: https://www.qodo.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Governing law differs for customers located outside North America versus in North America; no country list\n    is stated.\nentity_types:\n- type: individual\n  text: if you are an individual or an individual accepting these Terms on behalf of a legal entity, that you are\n    at least 18 years old or of sufficient legal age to accept these Terms in accordance with the laws of your jurisdiction.\n- type: business\n  text: If You subscribed to Qodo under the Enterprise subscription\
  \ plan and above or entered into an offline order\n    form with Qodo, these Terms will not apply\nrestricted_uses:\n- summary: No sharing of personal or health data as input\n  text: You will not share Personal Data with the Platform as Input, nor will share with us any “protected health\n    information” or Personal Data which constitutes “sensitive Personal Data” under applicable law without Our prior\n    written consent\n- summary: No harvesting personal data\n  text: harvest or collect Personal Data (as defined below) without their express consent or other legal basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must register and establish an account with Qodo in order to use the Services\nminimum_age:\n  value: '18'\n  text: if you are an individual or an individual accepting these Terms on behalf of a legal entity, that you are\n    at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/codiumai/eligibility/codiumai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Codiumai's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
