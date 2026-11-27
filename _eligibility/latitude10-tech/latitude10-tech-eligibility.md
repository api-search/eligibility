---
api_specs:
- filename: latitude10-tech-agent-readiness-api-openapi.yml
  format: yaml
  label: latitude10-tech Agent readiness API
  slug: latitude10-tech-agent-readiness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latitude10-tech/openapi/latitude10-tech-agent-readiness-api-openapi.yml
- filename: latitude10-tech-design-packs-api-openapi.yml
  format: yaml
  label: latitude10-tech Design packs API
  slug: latitude10-tech-design-packs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latitude10-tech/openapi/latitude10-tech-design-packs-api-openapi.yml
- filename: latitude10-tech-developer-kits-api-openapi.yml
  format: yaml
  label: latitude10-tech Developer kits API
  slug: latitude10-tech-developer-kits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latitude10-tech/openapi/latitude10-tech-developer-kits-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We sell subscriptions to businesses in most countries, but not in countries under comprehensive United States sanctions or where local rules would make us charge a tax we don't collect, and to individuals in the United States and Canada.
  entity_types:
  - text: Our products and services are made for businesses and developers.
    type: business
  - text: Our products and services are made for businesses and developers.
    type: developer
  minimum_age:
    text: You must be at least 18, or the age of majority where you live if that is higher.
    value: '18'
  restricted_uses:
  - summary: Spam, malware, fraud, laundering, sanctions evasion
    text: use our services to send spam or malware, to defraud anyone, to launder money or to evade sanctions
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
name: latitude10-tech
provenance_date: '2026-11-09'
provider_name: latitude10-tech
provider_slug: latitude10-tech
slug: latitude10-tech-eligibility
source_date: '2026-11-09'
source_filename: latitude10-tech-eligibility.yml
source_heading: Eligibility
source_page: https://latitude10.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: latitude10-tech\naid: latitude10-tech\nurl: https://latitude10.tech/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We sell subscriptions to businesses in most countries, but not in countries under comprehensive United States\n    sanctions or where local rules would make us charge a tax we don't collect, and to individuals in the United\n    States and Canada.\nentity_types:\n- type: business\n  text: Our products and services are made for businesses and developers.\n- type: developer\n  text: Our products and services are made for businesses and developers.\nrestricted_uses:\n\
  - summary: Spam, malware, fraud, laundering, sanctions evasion\n  text: use our services to send spam or malware, to defraud anyone, to launder money or to evade sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live if that is higher.\n"
source_yaml_url: https://artifacts.apis.io/latitude10-tech/eligibility/latitude10-tech-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from latitude10-tech's own page on 2026-11-09.
synthetic: false
tags:
- API Platform
- MCP
- Developer Tools
- AI Agents
- OpenAPI
---
