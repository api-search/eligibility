---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age and legally capable of entering into a binding contract under the Indian Contract Act, 1872 to use the Platform.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Banned or counterfeit listings
    text: may not list banned, illegal, counterfeit or restricted items.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: The Company is not responsible for verifying the authenticity of information provided by Users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dukaan
provenance_date: '2026-11-09'
provider_name: Dukaan
provider_slug: dukaan
slug: dukaan-eligibility
source_date: '2026-11-09'
source_filename: dukaan-eligibility.yml
source_heading: Eligibility
source_page: https://mydukaan.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dukaan\naid: dukaan\nurl: https://mydukaan.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age and legally capable of entering into a binding contract under the Indian\n    Contract Act, 1872 to use the Platform.\nrestricted_uses:\n- summary: Banned or counterfeit listings\n  text: may not list banned, illegal, counterfeit or restricted items.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: The Company is not responsible for verifying the authenticity of information\
  \ provided by Users\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/dukaan/eligibility/dukaan-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Dukaan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Online Store
- Store Builder
- Retail
- Themes
- Templating
- Plugins
- Logistics
- India
---
