---
api_specs:
- filename: anchord-ai-dupes-api-openapi.yml
  format: yaml
  label: Anchord AI Dupes API
  slug: anchord-ai-dupes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-dupes-api-openapi.yml
- filename: anchord-ai-entities-api-openapi.yml
  format: yaml
  label: Anchord AI Entities API
  slug: anchord-ai-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-entities-api-openapi.yml
- filename: anchord-ai-guard-api-openapi.yml
  format: yaml
  label: Anchord AI Guard API
  slug: anchord-ai-guard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-guard-api-openapi.yml
- filename: anchord-ai-health-api-openapi.yml
  format: yaml
  label: Anchord AI Health API
  slug: anchord-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-health-api-openapi.yml
- filename: anchord-ai-ingest-api-openapi.yml
  format: yaml
  label: Anchord AI Ingest API
  slug: anchord-ai-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-ingest-api-openapi.yml
- filename: anchord-ai-links-api-openapi.yml
  format: yaml
  label: Anchord AI Links API
  slug: anchord-ai-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-links-api-openapi.yml
- filename: anchord-ai-resolve-api-openapi.yml
  format: yaml
  label: Anchord AI Resolve API
  slug: anchord-ai-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-resolve-api-openapi.yml
- filename: anchord-ai-sources-api-openapi.yml
  format: yaml
  label: Anchord AI Sources API
  slug: anchord-ai-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-sources-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with applicable laws
    text: You agree to use the Service in compliance with all applicable laws.
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
name: Anchord AI
provenance_date: '2026-11-09'
provider_name: Anchord AI
provider_slug: anchord-ai
slug: anchord-ai-eligibility
source_date: '2026-11-09'
source_filename: anchord-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.anchord.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anchord AI\naid: anchord-ai\nurl: https://www.anchord.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization.\nrestricted_uses:\n- summary: Compliance with applicable laws\n  text: You agree to use the Service in compliance with all applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anchord-ai/eligibility/anchord-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Anchord AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Identity
- Trust
- Write-Guard
- Integration
---
