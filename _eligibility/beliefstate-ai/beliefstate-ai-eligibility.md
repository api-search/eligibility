---
api_specs:
- filename: beliefstate-ai-access-api-openapi.yml
  format: yaml
  label: BeliefState Access API
  slug: beliefstate-ai-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-access-api-openapi.yml
- filename: beliefstate-ai-beliefs-api-openapi.yml
  format: yaml
  label: BeliefState Beliefs API
  slug: beliefstate-ai-beliefs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-beliefs-api-openapi.yml
- filename: beliefstate-ai-brief-api-openapi.yml
  format: yaml
  label: BeliefState Brief API
  slug: beliefstate-ai-brief-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-brief-api-openapi.yml
- filename: beliefstate-ai-research-api-openapi.yml
  format: yaml
  label: BeliefState Research API
  slug: beliefstate-ai-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-research-api-openapi.yml
- filename: beliefstate-ai-research-payments-api-openapi.yml
  format: yaml
  label: BeliefState Research payments API
  slug: beliefstate-ai-research-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-research-payments-api-openapi.yml
- filename: beliefstate-ai-sources-api-openapi.yml
  format: yaml
  label: BeliefState Sources API
  slug: beliefstate-ai-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-sources-api-openapi.yml
- filename: beliefstate-ai-tickers-api-openapi.yml
  format: yaml
  label: BeliefState Tickers API
  slug: beliefstate-ai-tickers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-tickers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and legally able to enter a contract.
    type: individual
  - text: If you use BeliefState for an organization, you represent that you may bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: Investment decisions
    text: Nothing in the service is an offer, solicitation, recommendation, promise of performance, or instruction to buy, sell, or hold a security.
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
name: BeliefState
provenance_date: '2026-11-09'
provider_name: BeliefState
provider_slug: beliefstate-ai
slug: beliefstate-ai-eligibility
source_date: '2026-11-09'
source_filename: beliefstate-ai-eligibility.yml
source_heading: Eligibility
source_page: https://beliefstate.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeliefState\naid: beliefstate-ai\nurl: https://beliefstate.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally able to enter a contract.\n- type: business\n  text: If you use BeliefState for an organization, you represent that you may bind that organization.\nrestricted_uses:\n- summary: Investment decisions\n  text: Nothing in the service is an offer, solicitation, recommendation, promise of performance, or instruction\n    to buy, sell, or hold a security.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/beliefstate-ai/eligibility/beliefstate-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BeliefState's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Research
- Analytics
- Platform
---
