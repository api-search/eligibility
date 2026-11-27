---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are employed by or acting on behalf of a company or other organization, You represent and warrant that You have the authority to bind such company or organization
    type: business
  - text: If You are a Client, You represent and warrant that You have executed a Client Agreement and will fully comply with its terms.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-RIA evaluation only
    text: If You have not entered an Investment Adviser Agreement (whether or not You are an RIA), You may use the Service, including any Content and Results, solely (i) to test and evaluate the Service
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
name: Opto
provenance_date: '2026-11-10'
provider_name: Opto
provider_slug: opto
slug: opto-eligibility
source_date: '2026-11-10'
source_filename: opto-eligibility.yml
source_heading: Eligibility
source_page: https://www.optoinvest.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opto\naid: opto\nurl: https://www.optoinvest.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are employed by or acting on behalf of a company or other organization, You represent and warrant\n    that You have the authority to bind such company or organization\n- type: individual\n  text: If You are a Client, You represent and warrant that You have executed a Client Agreement and will fully\n    comply with its terms.\nrestricted_uses:\n- summary: Non-RIA evaluation only\n  text: If You have not entered an\
  \ Investment Adviser Agreement (whether or not You are an RIA), You may use the\n    Service, including any Content and Results, solely (i) to test and evaluate the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opto/eligibility/opto-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Opto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Private Markets
- Wealth Management
- Investment
- Fintech
- Alternative Investments
- Private Equity
- RIA
---
