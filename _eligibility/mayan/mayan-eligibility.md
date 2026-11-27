---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled, operated and administered by Mayan from our offices within the USA and Canada.
  entity_types:
  - text: Be 18 years of age, or the age of majority in your province, territory or country, to become a Member.
    type: individual
  - text: You represent that you have full power, capacity and authority to accept these Terms on behalf of yourself or your employer.
    type: business
  minimum_age:
    text: Be 18 years of age, or the age of majority in your province, territory or country, to become a Member.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Provide your legal full name, valid email address, and any other information we request to complete your account-signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mayan
provenance_date: '2026-11-10'
provider_name: Mayan
provider_slug: mayan
slug: mayan-eligibility
source_date: '2026-11-10'
source_filename: mayan-eligibility.yml
source_heading: Eligibility
source_page: https://www.mayan.co/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mayan\naid: mayan\nurl: https://www.mayan.co/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled, operated and administered by Mayan from our offices within the USA and Canada.\nentity_types:\n- type: individual\n  text: Be 18 years of age, or the age of majority in your province, territory or country, to become a Member.\n- type: business\n  text: You represent that you have full power, capacity and authority to accept these Terms on behalf of yourself\n    or your employer.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Provide your legal full name, valid email address, and any other information we request to complete your\n    account-signup process.\nminimum_age:\n  value: '18'\n  text: Be 18 years of age, or the age of majority in your province, territory or country, to become a Member.\n"
source_yaml_url: https://artifacts.apis.io/mayan/eligibility/mayan-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Mayan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Amazon
- E-Commerce
- Advertising
- Retail Media
- Marketing Automation
- Inventory
- Analytics
- Software-as-a-Service
---
