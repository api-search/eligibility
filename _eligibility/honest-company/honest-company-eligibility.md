---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: All Canadian sales occur in the US.
  entity_types:
  - text: You agree that by using this Site or registering for membership, You are at least 18 years of age
    type: individual
  - text: all products purchased from and orders submitted through the Site are for your personal or household use and not for resale or any other commercial use
    type: business
  minimum_age:
    text: You are at least 18 years of age if You are a resident of the United States or otherwise the age of majority in your jurisdiction of residence, or in the case of the Alt12 Services, at least 13 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Use of the Site for any illegal or unauthorized purpose is strictly prohibited.
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
name: Honest Company
provenance_date: '2026-11-09'
provider_name: Honest Company
provider_slug: honest-company
slug: honest-company-eligibility
source_date: '2026-11-09'
source_filename: honest-company-eligibility.yml
source_heading: Eligibility
source_page: https://honest.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Honest Company\naid: honest-company\nurl: https://honest.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: All Canadian sales occur in the US.\nentity_types:\n- type: individual\n  text: You agree that by using this Site or registering for membership, You are at least 18 years of age\n- type: business\n  text: all products purchased from and orders submitted through the Site are for your personal or household use\n    and not for resale or any other commercial use\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Use of the Site\
  \ for any illegal or unauthorized purpose is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age if You are a resident of the United States or otherwise the age of majority\n    in your jurisdiction of residence, or in the case of the Alt12 Services, at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/honest-company/eligibility/honest-company-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Honest Company's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Goods
- E-Commerce
- Retail
- Baby Care
- Personal Care
- Beauty
- Shopify
- Agentic Commerce
- MCP
- Universal Commerce Protocol
---
