---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You are located in the United States.
  entity_types:
  - text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE
    type: individual
  - text: provides an online software-as-a-service platform to investment advisers, lawyers, RIAs, financial services companies
    type: business
  minimum_age:
    text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Commercial purpose
    text: Use the Services for a commercial purpose
  - summary: Sanctioned persons
    text: you are not a Sanctioned Person under U.S. law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may from time to time ask you for additional identification information as may be required for regulatory or other reasons.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vanilla
provenance_date: '2026-11-10'
provider_name: Vanilla
provider_slug: vanilla
slug: vanilla-eligibility
source_date: '2026-11-10'
source_filename: vanilla-eligibility.yml
source_heading: Eligibility
source_page: https://www.justvanilla.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vanilla\naid: vanilla\nurl: https://www.justvanilla.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You are located in the United States.\nentity_types:\n- type: individual\n  text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE\n- type: business\n  text: provides an online software-as-a-service platform to investment advisers, lawyers, RIAs, financial services\n    companies\nrestricted_uses:\n- summary: Commercial purpose\n  text: Use the Services for a commercial purpose\n- summary: Sanctioned persons\n  text:\
  \ you are not a Sanctioned Person under U.S. law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may from time to time ask you for additional identification information as may be required for regulatory\n    or other reasons.\nminimum_age:\n  value: '18'\n  text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/vanilla/eligibility/vanilla-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Vanilla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Estate Planning
- Wealth Management
- Financial Advisors
- Fintech
- Artificial Intelligence
- Software-as-a-Service
---
