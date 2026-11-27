---
api_specs:
- filename: gatiflow-intelligence-api-openapi.yml
  format: yaml
  label: GatiFlow Intelligence API
  slug: gatiflow-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-intelligence-api-openapi.yml
- filename: gatiflow-public-api-openapi.yml
  format: yaml
  label: GatiFlow Public API
  slug: gatiflow-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-public-api-openapi.yml
- filename: gatiflow-usage-api-openapi.yml
  format: yaml
  label: GatiFlow Usage API
  slug: gatiflow-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-usage-api-openapi.yml
- filename: gatiflow-webhooks-api-openapi.yml
  format: yaml
  label: GatiFlow Webhooks API
  slug: gatiflow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-webhooks-api-openapi.yml
- filename: gatiflow-agent-api-openapi.yml
  format: yaml
  label: GatiFlow Agent API
  slug: gatiflow-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-agent-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Where you are a natural person, you must be at least eighteen (18) years of age or the age of majority in your place of residence, whichever is higher.
    type: individual
  - text: If you accept these Terms on behalf of a legal entity, you represent that you have the authority to bind that entity.
    type: business
  minimum_age:
    text: you must be at least eighteen (18) years of age or the age of majority in your place of residence, whichever is higher.
    value: '18'
  restricted_uses:
  - summary: Sole basis for decisions about people
    text: You must not use any Output as the sole or primary basis for any decision producing legal effects concerning, or similarly significantly affecting, a natural person
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
name: GatiFlow
provenance_date: '2026-11-09'
provider_name: GatiFlow
provider_slug: gatiflow
slug: gatiflow-eligibility
source_date: '2026-11-09'
source_filename: gatiflow-eligibility.yml
source_heading: Eligibility
source_page: https://gatiflow.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GatiFlow\naid: gatiflow\nurl: https://gatiflow.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Where you are a natural person, you must be at least eighteen (18) years of age or the age of majority in\n    your place of residence, whichever is higher.\n- type: business\n  text: If you accept these Terms on behalf of a legal entity, you represent that you have the authority to bind\n    that entity.\nrestricted_uses:\n- summary: Sole basis for decisions about people\n  text: You must not use any Output as the sole or primary\
  \ basis for any decision producing legal effects concerning,\n    or similarly significantly affecting, a natural person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least eighteen (18) years of age or the age of majority in your place of residence, whichever\n    is higher.\n"
source_yaml_url: https://artifacts.apis.io/gatiflow/eligibility/gatiflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from GatiFlow's own page on 2026-11-09.
synthetic: false
tags:
- Market Intelligence
- Developer Signals
- Trends
- Hiring
- Open Source
- Research
- B2B SaaS
- Artificial Intelligence
---
