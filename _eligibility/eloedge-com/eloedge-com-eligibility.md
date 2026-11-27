---
api_specs:
- filename: eloedge-com-openapi-generated.yml
  format: yaml
  label: eloedge-com API
  slug: eloedge-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eloedge-com/openapi/_ae-authored/eloedge-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in, or ordinarily resident in, a country or region subject to U.S. embargo, or if you appear on a U.S. government sanctions or restricted-party list.
  entity_types:
  - text: You must be at least 18 years old and able to make a binding contract.
    type: individual
  - text: If you are accepting for a company, you confirm you have authority to bind it, and "you" means the company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal wagering or market manipulation
    text: Don't use the Service to violate any law, including securities, commodities, gaming and sanctions law, to manipulate any market, or to facilitate illegal wagering.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a supported identity provider (Google or X).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: eloedge-com
provenance_date: '2026-11-09'
provider_name: eloedge-com
provider_slug: eloedge-com
slug: eloedge-com-eligibility
source_date: '2026-11-09'
source_filename: eloedge-com-eligibility.yml
source_heading: Eligibility
source_page: https://eloedge.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: eloedge-com\naid: eloedge-com\nurl: https://eloedge.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in, or ordinarily resident in, a country or region subject\n    to U.S. embargo, or if you appear on a U.S. government sanctions or restricted-party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to make a binding contract.\n- type: business\n  text: If you are accepting for a company, you confirm you have authority to bind it, and \"you\" means the company.\nrestricted_uses:\n- summary:\
  \ Illegal wagering or market manipulation\n  text: Don't use the Service to violate any law, including securities, commodities, gaming and sanctions law, to\n    manipulate any market, or to facilitate illegal wagering.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a supported identity provider (Google or X).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eloedge-com/eligibility/eloedge-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from eloedge-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Prediction-Market
- Trading-Agent
- MCP
- Data Feed
- Platform
---
