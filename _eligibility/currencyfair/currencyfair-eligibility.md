---
api_specs:
- filename: currencyfair-currencyfair-api-openapi.yml
  format: yaml
  label: Currencyfair Currency Fair API
  slug: currencyfair-currencyfair-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/currencyfair/openapi/currencyfair-currencyfair-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If your account is a consumer account, the error resolution provisions of the federal Electronic Fund Transfer Act (“Regulation E”) apply.
    type: individual
  - text: If you are accessing the Services on behalf of an entity (for example, a company, non-profit entity, university, or other business or organization), you represent to us that you have authority to bind that entity to these terms
    type: business
  - text: If you are accessing the Services on behalf of an entity (for example, a company, non-profit entity, university, or other business or organization)
    type: nonprofit
  minimum_age:
    text: your age is at least 18 years
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties
    text: CurrencyFair prohibits transactions involving parties subject to U.S. economic sanctions, including those listed by the Office of Foreign Assets Control (OFAC).
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
name: Currencyfair
provenance_date: '2026-11-09'
provider_name: Currencyfair
provider_slug: currencyfair
slug: currencyfair-eligibility
source_date: '2026-11-09'
source_filename: currencyfair-eligibility.yml
source_heading: Eligibility
source_page: https://www.currencyfair.com/en-us/trust/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Currencyfair\naid: currencyfair\nurl: https://www.currencyfair.com/en-us/trust/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If your account is a consumer account, the error resolution provisions of the federal Electronic Fund Transfer\n    Act (“Regulation E”) apply.\n- type: business\n  text: If you are accessing the Services on behalf of an entity (for example, a company, non-profit entity, university,\n    or other business or organization), you represent to us that you have authority to\
  \ bind that entity to these\n    terms\n- type: nonprofit\n  text: If you are accessing the Services on behalf of an entity (for example, a company, non-profit entity, university,\n    or other business or organization)\nrestricted_uses:\n- summary: Sanctioned parties\n  text: CurrencyFair prohibits transactions involving parties subject to U.S. economic sanctions, including those\n    listed by the Office of Foreign Assets Control (OFAC).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: your age is at least 18 years\n"
source_yaml_url: https://artifacts.apis.io/currencyfair/eligibility/currencyfair-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Currencyfair's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Money Transfer
- International Payments
- Foreign Exchange
---
