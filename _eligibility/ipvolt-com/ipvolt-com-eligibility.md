---
api_specs:
- filename: ipvolt-com-openapi-generated.yml
  format: yaml
  label: ipvolt-com API
  slug: ipvolt-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipvolt-com/openapi/_ae-authored/ipvolt-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use ipvolt if you, anyone who owns or controls you, or anyone you act for is listed under United Nations, European Union, United Kingdom or United States sanctions, or if you are located or ordinarily resident in a country or region subject to comprehensive sanctions under those regimes.
  entity_types:
  - text: ipvolt is for business and professional use only; we do not offer it to consumers.
    type: business
  minimum_age:
    text: By using it you confirm that you are at least 18
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties
    text: You may not use ipvolt if you, anyone who owns or controls you, or anyone you act for is listed under United Nations, European Union, United Kingdom or United States sanctions
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
name: ipvolt-com
provenance_date: '2026-11-09'
provider_name: ipvolt-com
provider_slug: ipvolt-com
slug: ipvolt-com-eligibility
source_date: '2026-11-09'
source_filename: ipvolt-com-eligibility.yml
source_heading: Eligibility
source_page: https://ipvolt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ipvolt-com\naid: ipvolt-com\nurl: https://ipvolt.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use ipvolt if you, anyone who owns or controls you, or anyone you act for is listed under United\n    Nations, European Union, United Kingdom or United States sanctions, or if you are located or ordinarily resident\n    in a country or region subject to comprehensive sanctions under those regimes.\nentity_types:\n- type: business\n  text: ipvolt is for business and professional use only; we do not offer it to consumers.\nrestricted_uses:\n- summary: Sanctioned parties\n\
  \  text: You may not use ipvolt if you, anyone who owns or controls you, or anyone you act for is listed under United\n    Nations, European Union, United Kingdom or United States sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using it you confirm that you are at least 18\n"
source_yaml_url: https://artifacts.apis.io/ipvolt-com/eligibility/ipvolt-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ipvolt-com's own page on 2026-11-09.
synthetic: false
tags:
- Proxy
- Developer Tools
- Infrastructure
- Networking
- Data
---
