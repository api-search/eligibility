---
api_specs:
- filename: anyhook-net-anyhook-api-api-openapi.yml
  format: yaml
  label: AnyHook AnyHook API
  slug: anyhook-net-anyhook-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-anyhook-api-api-openapi.yml
- filename: anyhook-net-api-keys-api-openapi.yml
  format: yaml
  label: AnyHook Api Keys API
  slug: anyhook-net-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-api-keys-api-openapi.yml
- filename: anyhook-net-apps-api-openapi.yml
  format: yaml
  label: AnyHook Apps API
  slug: anyhook-net-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-apps-api-openapi.yml
- filename: anyhook-net-claim-api-openapi.yml
  format: yaml
  label: AnyHook Claim API
  slug: anyhook-net-claim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-claim-api-openapi.yml
- filename: anyhook-net-connect-api-openapi.yml
  format: yaml
  label: AnyHook Connect API
  slug: anyhook-net-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-connect-api-openapi.yml
- filename: anyhook-net-events-api-openapi.yml
  format: yaml
  label: AnyHook Events API
  slug: anyhook-net-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-events-api-openapi.yml
- filename: anyhook-net-quickstart-api-openapi.yml
  format: yaml
  label: AnyHook Quickstart API
  slug: anyhook-net-quickstart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-quickstart-api-openapi.yml
- filename: anyhook-net-usage-api-openapi.yml
  format: yaml
  label: AnyHook Usage API
  slug: anyhook-net-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-usage-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you register on behalf of a company, you represent that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Process, relay, or store content that is unlawful, harmful, or violates third-party rights.
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
name: AnyHook
provenance_date: '2026-11-09'
provider_name: AnyHook
provider_slug: anyhook-net
slug: anyhook-net-eligibility
source_date: '2026-11-09'
source_filename: anyhook-net-eligibility.yml
source_heading: Eligibility
source_page: https://anyhook.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnyHook\naid: anyhook-net\nurl: https://anyhook.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you register on behalf of a company, you represent that you have authority to bind that entity to these\n    Terms.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Process, relay, or store content that is unlawful, harmful, or violates third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/anyhook-net/eligibility/anyhook-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AnyHook's own page on 2026-11-09.
synthetic: false
tags:
- Webhook
- Integration
- Reliability
- Developer Tools
- event-replay
---
