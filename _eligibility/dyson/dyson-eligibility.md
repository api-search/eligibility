---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Information on this Site includes descriptions of products and services available in the United States only. Products and services ordered through this site will not be shipped or provided outside of the United States.
  entity_types:
  - text: “Buyer” means the entity that purchases Dyson Products from Dyson;
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No resale of purchased products
    text: You are prohibited from reselling any products purchased through this Site or by telephone without our separate written consent.
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
name: Dyson
provenance_date: '2026-11-09'
provider_name: Dyson
provider_slug: dyson
slug: dyson-eligibility
source_date: '2026-11-09'
source_filename: dyson-eligibility.yml
source_heading: Eligibility
source_page: https://www.dyson.com/inside-dyson/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dyson\naid: dyson\nurl: https://www.dyson.com/inside-dyson/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Information on this Site includes descriptions of products and services available in the United States only.\n    Products and services ordered through this site will not be shipped or provided outside of the United States.\nentity_types:\n- type: business\n  text: “Buyer” means the entity that purchases Dyson Products from Dyson;\nrestricted_uses:\n- summary: No resale of purchased products\n  text: You are prohibited from reselling any products\
  \ purchased through this Site or by telephone without our separate\n    written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dyson/eligibility/dyson-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Dyson's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Technology
- Appliances
- Innovation
- Consumer
---
