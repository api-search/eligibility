---
api_specs:
- filename: amzscout-net-discovery-api-openapi.yml
  format: yaml
  label: AMZScout Discovery API
  slug: amzscout-net-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amzscout-net/openapi/amzscout-net-discovery-api-openapi.yml
- filename: amzscout-net-dispatch-api-openapi.yml
  format: yaml
  label: AMZScout Dispatch API
  slug: amzscout-net-dispatch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amzscout-net/openapi/amzscout-net-dispatch-api-openapi.yml
- filename: amzscout-net-tools-api-openapi.yml
  format: yaml
  label: AMZScout Tools API
  slug: amzscout-net-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amzscout-net/openapi/amzscout-net-tools-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You agree not to access or use the Services if you are located in, or are a national or resident of, a country subject to U.S. trade sanctions
  entity_types:
  - text: Be a human natural person
    type: individual
  - text: you confirm that you have authority to bind that organization
    type: business
  minimum_age:
    text: Be at least 18 years old (or the age of majority where you reside), or have verifiable parental or legal guardian consent
    value: '18'
  restricted_uses:
  - summary: Internal business purposes only
    text: Company grants you a limited, revocable, non-exclusive, non-transferable license to access and use the Services for your internal business purposes
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
name: AMZScout
provenance_date: '2026-11-09'
provider_name: AMZScout
provider_slug: amzscout-net
slug: amzscout-net-eligibility
source_date: '2026-11-09'
source_filename: amzscout-net-eligibility.yml
source_heading: Eligibility
source_page: https://amzscout.net/terms-of-use/?r=footer
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AMZScout\naid: amzscout-net\nurl: https://amzscout.net/terms-of-use/?r=footer\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You agree not to access or use the Services if you are located in, or are a national or resident of, a country\n    subject to U.S. trade sanctions\nentity_types:\n- type: individual\n  text: Be a human natural person\n- type: business\n  text: you confirm that you have authority to bind that organization\nrestricted_uses:\n- summary: Internal business purposes only\n  text: Company grants you a limited, revocable, non-exclusive, non-transferable license to\
  \ access and use the Services\n    for your internal business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old (or the age of majority where you reside), or have verifiable parental or legal\n    guardian consent\n"
source_yaml_url: https://artifacts.apis.io/amzscout-net/eligibility/amzscout-net-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AMZScout's own page on 2026-11-09.
synthetic: false
tags:
- Amazon
- FBA
- Product Research
- Software-as-a-Service
- E-Commerce
- Company
---
