---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: Our products and services are offered to Alberta residents and businesses operating in Alberta.
  entity_types:
  - text: Our products and services are offered to Alberta residents
    type: individual
  - text: businesses operating in Alberta
    type: business
  minimum_age:
    text: null
    value: null
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
name: Servus Credit Union
provenance_date: '2026-11-10'
provider_name: Servus Credit Union
provider_slug: servus-credit-union
slug: servus-credit-union-eligibility
source_date: '2026-11-10'
source_filename: servus-credit-union-eligibility.yml
source_heading: Eligibility
source_page: https://servus.ca/legal-security/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Servus Credit Union\naid: servus-credit-union\nurl: https://servus.ca/legal-security/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: Our products and services are offered to Alberta residents and businesses operating in Alberta.\nentity_types:\n- type: individual\n  text: Our products and services are offered to Alberta residents\n- type: business\n  text: businesses operating in Alberta\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/servus-credit-union/eligibility/servus-credit-union-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from Servus Credit Union's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Credit Union
- Cooperative
- Alberta
- Open Banking
---
