---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: all purchases are intended for final delivery to locations within the United States
  entity_types:
  - text: You further certify that you are 18 years of age or older
    type: individual
  minimum_age:
    text: You further certify that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Resale or commercial quantities
    text: you are buying the products or services for your own personal or household use only, and not for resale or export
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
name: Allbirds
provenance_date: '2026-11-09'
provider_name: Allbirds
provider_slug: allbirds
slug: allbirds-eligibility
source_date: '2026-11-09'
source_filename: allbirds-eligibility.yml
source_heading: Eligibility
source_page: https://www.allbirds.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Allbirds\naid: allbirds\nurl: https://www.allbirds.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: all purchases are intended for final delivery to locations within the United States\nentity_types:\n- type: individual\n  text: You further certify that you are 18 years of age or older\nrestricted_uses:\n- summary: Resale or commercial quantities\n  text: you are buying the products or services for your own personal or household use only, and not for resale\n    or export\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You further certify that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/allbirds/eligibility/allbirds-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Allbirds's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Retail
- E-Commerce
- Footwear
- Apparel
- Sustainability
- Direct to Consumer
- Agentic Commerce
- Shopify
- Fashion
---
