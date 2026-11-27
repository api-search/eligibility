---
api_specs:
- filename: topxea-com-anthropic-compatible-api-openapi.yml
  format: yaml
  label: topxea-com Anthropic Compatible API
  slug: topxea-com-anthropic-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topxea-com/openapi/topxea-com-anthropic-compatible-api-openapi.yml
- filename: topxea-com-openai-compatible-api-openapi.yml
  format: yaml
  label: topxea-com Open AI Compatible API
  slug: topxea-com-openai-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topxea-com/openapi/topxea-com-openai-compatible-api-openapi.yml
- filename: topxea-com-public-api-openapi.yml
  format: yaml
  label: topxea-com Public API
  slug: topxea-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topxea-com/openapi/topxea-com-public-api-openapi.yml
- filename: topxea-com-typesafe-api-openapi.yml
  format: yaml
  label: topxea-com Type Safe API
  slug: topxea-com-typesafe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topxea-com/openapi/topxea-com-typesafe-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some jurisdictions restrict forex/derivatives trading or cryptocurrency (USDT) payments; you are responsible for confirming the legality of using this service and related trading where you live.
  entity_types:
  - text: This service is for adults (18+) with full legal capacity.
    type: individual
  minimum_age:
    text: This service is for adults aged 18 or over.
    value: '18'
  restricted_uses:
  - summary: Trading or payments restricted by local law
    text: Some jurisdictions restrict forex/derivatives trading or cryptocurrency (USDT) payments; you are responsible for confirming the legality of using this service and related trading where you live.
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
name: topxea-com
provenance_date: '2026-11-10'
provider_name: topxea-com
provider_slug: topxea-com
slug: topxea-com-eligibility
source_date: '2026-11-10'
source_filename: topxea-com-eligibility.yml
source_heading: Eligibility
source_page: https://topxea.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: topxea-com\naid: topxea-com\nurl: https://topxea.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Some jurisdictions restrict forex/derivatives trading or cryptocurrency (USDT) payments; you are responsible\n    for confirming the legality of using this service and related trading where you live.\nentity_types:\n- type: individual\n  text: This service is for adults (18+) with full legal capacity.\nrestricted_uses:\n- summary: Trading or payments restricted by local law\n  text: Some jurisdictions restrict forex/derivatives trading or cryptocurrency (USDT) payments; you\
  \ are responsible\n    for confirming the legality of using this service and related trading where you live.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This service is for adults aged 18 or over.\n"
source_yaml_url: https://artifacts.apis.io/topxea-com/eligibility/topxea-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from topxea-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data
- Finance
- Research
---
