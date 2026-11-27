---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is currently available only in the United States.
  minimum_age:
    text: You must be at least 18 years old to create an account, sell, or transact on the Service.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: You represent that you are not subject to U.S. economic sanctions, are not located in a country subject to comprehensive U.S. sanctions, and are not on any U.S. government restricted-party list.
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
name: Teespring
provenance_date: '2026-11-10'
provider_name: Teespring
provider_slug: teespring
slug: teespring-eligibility
source_date: '2026-11-10'
source_filename: teespring-eligibility.yml
source_heading: Eligibility
source_page: https://www.amaze.co/policies/commerce/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Teespring\naid: teespring\nurl: https://www.amaze.co/policies/commerce/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is currently available only in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned persons\n  text: You represent that you are not subject to U.S. economic sanctions, are not located in a country subject\n    to comprehensive U.S. sanctions, and are not on any U.S. government restricted-party list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years old to create an account, sell, or transact on the Service.\n"
source_yaml_url: https://artifacts.apis.io/teespring/eligibility/teespring-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Teespring's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Print on Demand
- Creator Economy
- Merchandise
- Retail
- Apparel
---
