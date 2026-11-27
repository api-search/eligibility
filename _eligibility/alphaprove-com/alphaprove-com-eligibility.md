---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of legal majority in your jurisdiction if higher, to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an organisation, you represent that you have authority to bind that organisation
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction if higher, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or sanctioned use
    text: use the Service for any unlawful purpose or in violation of any applicable law, regulation, or sanctions regime
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
name: AlphaProve
provenance_date: '2026-11-09'
provider_name: AlphaProve
provider_slug: alphaprove-com
slug: alphaprove-com-eligibility
source_date: '2026-11-09'
source_filename: alphaprove-com-eligibility.yml
source_heading: Eligibility
source_page: https://alphaprove.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlphaProve\naid: alphaprove-com\nurl: https://alphaprove.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction if higher, to use the\n    Service.\n- type: business\n  text: If you are using the Service on behalf of an organisation, you represent that you have authority to bind\n    that organisation\nrestricted_uses:\n- summary: Unlawful or sanctioned use\n  text: use the Service for any unlawful purpose or in violation of any applicable\
  \ law, regulation, or sanctions\n    regime\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction if higher, to use the\n    Service.\n"
source_yaml_url: https://artifacts.apis.io/alphaprove-com/eligibility/alphaprove-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AlphaProve's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Backtesting
- Trading
- Artificial Intelligence
- Finance
---
