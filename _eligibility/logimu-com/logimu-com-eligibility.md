---
api_specs:
- filename: logimu-com-coding-agents-json-api-openapi.yml
  format: yaml
  label: logimu-com Coding Agents.json API
  slug: logimu-com-coding-agents-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logimu-com/openapi/logimu-com-coding-agents-json-api-openapi.yml
- filename: logimu-com-deprecations-json-api-openapi.yml
  format: yaml
  label: logimu-com Deprecations.json API
  slug: logimu-com-deprecations-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logimu-com/openapi/logimu-com-deprecations-json-api-openapi.yml
- filename: logimu-com-rankings-json-api-openapi.yml
  format: yaml
  label: logimu-com Rankings.json API
  slug: logimu-com-rankings-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logimu-com/openapi/logimu-com-rankings-json-api-openapi.yml
- filename: logimu-com-subscribe-api-openapi.yml
  format: yaml
  label: logimu-com Subscribe API
  slug: logimu-com-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logimu-com/openapi/logimu-com-subscribe-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for professional and business use. If you accept these terms on behalf of a company or other legal entity, you represent that you have authority to bind that entity.
    type: business
  - text: If you are an individual, you represent that you are at least 18 years old.
    type: individual
  minimum_age:
    text: If you are an individual, you represent that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Service for lawful purposes only.
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
name: logimu-com
provenance_date: '2026-11-09'
provider_name: logimu-com
provider_slug: logimu-com
slug: logimu-com-eligibility
source_date: '2026-11-09'
source_filename: logimu-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.logimu.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: logimu-com\naid: logimu-com\nurl: https://www.logimu.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for professional and business use. If you accept these terms on behalf of a company\n    or other legal entity, you represent that you have authority to bind that entity.\n- type: individual\n  text: If you are an individual, you represent that you are at least 18 years old.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Service for lawful purposes only.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are an individual, you represent that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/logimu-com/eligibility/logimu-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from logimu-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Data API
- Amazon
- Walmart
---
