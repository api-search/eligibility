---
api_specs:
- filename: nexbid-dev-agent-api-openapi.yml
  format: yaml
  label: nexbid-dev Agent API
  slug: nexbid-dev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexbid-dev/openapi/nexbid-dev-agent-api-openapi.yml
- filename: nexbid-dev-attribution-api-openapi.yml
  format: yaml
  label: nexbid-dev Attribution API
  slug: nexbid-dev-attribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexbid-dev/openapi/nexbid-dev-attribution-api-openapi.yml
- filename: nexbid-dev-discovery-api-openapi.yml
  format: yaml
  label: nexbid-dev Discovery API
  slug: nexbid-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexbid-dev/openapi/nexbid-dev-discovery-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of the Service requires legal capacity. Minors may only use the Service with the consent of a legal guardian.
    type: individual
  minimum_age:
    text: Minors may only use the Service with the consent of a legal guardian.
    value: null
  restricted_uses:
  - summary: Contextual URL analysis only
    text: The API may only be used for contextual URL analysis.
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
name: nexbid-dev
provenance_date: '2026-11-10'
provider_name: nexbid-dev
provider_slug: nexbid-dev
slug: nexbid-dev-eligibility
source_date: '2026-11-10'
source_filename: nexbid-dev-eligibility.yml
source_heading: Eligibility
source_page: https://nexbid.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: nexbid-dev\naid: nexbid-dev\nurl: https://nexbid.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of the Service requires legal capacity. Minors may only use the Service with the consent of a legal\n    guardian.\nrestricted_uses:\n- summary: Contextual URL analysis only\n  text: The API may only be used for contextual URL analysis.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Minors may only use the Service with the consent of a legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/nexbid-dev/eligibility/nexbid-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from nexbid-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Commerce
- Advertising
- Switzerland
- Open Source
---
