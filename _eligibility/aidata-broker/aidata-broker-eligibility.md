---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served:
    - US
    - GB
    - CA
    text: 'For now we take a mandate only from a holder based in the United States, the United Kingdom and Canada. A holder anywhere may value its data. Cuba, Iran, North Korea: we do not take holders from there'
  entity_types:
  - text: The Service is for businesses and for people acting in the course of their own trade or work
    type: business
  - text: people acting in the course of their own trade or work, including creators and developers who hold their own work
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Sensitive data categories not taken to market
    text: Health information, data about children, financial account data and clients' legal and tax files.
  - summary: Data whose value is who the people in it are
    text: Data whose value is who the people in it are.
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: the holder's register record or, for a person, their identity, who may sign for it and who is signing, its country, its brand, who owns it, the public record, and whose records they are (Verification)
excluded_countries:
- CU
- IR
- KP
- SY
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AIData.Broker open data API
provenance_date: '2026-11-09'
provider_name: AIData.Broker
provider_slug: aidata-broker
slug: aidata-broker-eligibility
source_date: '2026-11-09'
source_filename: aidata-broker-eligibility.yml
source_heading: Eligibility
source_page: https://aidata.broker/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIData.Broker open data API\naid: aidata-broker\nurl: https://aidata.broker/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  - CA\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: 'For now we take a mandate only from a holder based in the United States, the United Kingdom and Canada.\n    A holder anywhere may value its data. Cuba, Iran, North Korea: we do not take holders from there'\nentity_types:\n- type: business\n  text: The Service is for businesses and for people acting in the course of their own trade or work\n- type: individual\n  text: people acting\
  \ in the course of their own trade or work, including creators and developers who hold their\n    own work\nrestricted_uses:\n- summary: Sensitive data categories not taken to market\n  text: Health information, data about children, financial account data and clients' legal and tax files.\n- summary: Data whose value is who the people in it are\n  text: Data whose value is who the people in it are.\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: the holder's register record or, for a person, their identity, who may sign for it and who is signing, its\n    country, its brand, who owns it, the public record, and whose records they are (Verification)\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/aidata-broker/eligibility/aidata-broker-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from AIData.Broker open data API's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Marketplace
- AI Training
- Pricing
- Buyers
---
