---
api_specs:
- filename: arkova-ai-agents-api-openapi.yml
  format: yaml
  label: Arkova Agents API
  slug: arkova-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-agents-api-openapi.yml
- filename: arkova-ai-ai-intelligence-api-openapi.yml
  format: yaml
  label: Arkova AI Intelligence API
  slug: arkova-ai-ai-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-ai-intelligence-api-openapi.yml
- filename: arkova-ai-anchoring-api-openapi.yml
  format: yaml
  label: Arkova Anchoring API
  slug: arkova-ai-anchoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-anchoring-api-openapi.yml
- filename: arkova-ai-attestations-api-openapi.yml
  format: yaml
  label: Arkova Attestations API
  slug: arkova-ai-attestations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-attestations-api-openapi.yml
- filename: arkova-ai-compliance-api-openapi.yml
  format: yaml
  label: Arkova Compliance API
  slug: arkova-ai-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-compliance-api-openapi.yml
- filename: arkova-ai-folders-api-openapi.yml
  format: yaml
  label: Arkova Folders API
  slug: arkova-ai-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-folders-api-openapi.yml
- filename: arkova-ai-integrations-api-openapi.yml
  format: yaml
  label: Arkova Integrations API
  slug: arkova-ai-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-integrations-api-openapi.yml
- filename: arkova-ai-jobs-api-openapi.yml
  format: yaml
  label: Arkova Jobs API
  slug: arkova-ai-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-jobs-api-openapi.yml
- filename: arkova-ai-key-management-api-openapi.yml
  format: yaml
  label: Arkova Key Management API
  slug: arkova-ai-key-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-key-management-api-openapi.yml
- filename: arkova-ai-organizations-api-openapi.yml
  format: yaml
  label: Arkova Organizations API
  slug: arkova-ai-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-organizations-api-openapi.yml
- filename: arkova-ai-search-api-openapi.yml
  format: yaml
  label: Arkova Search API
  slug: arkova-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-search-api-openapi.yml
- filename: arkova-ai-usage-api-openapi.yml
  format: yaml
  label: Arkova Usage API
  slug: arkova-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-usage-api-openapi.yml
- filename: arkova-ai-verification-api-openapi.yml
  format: yaml
  label: Arkova Verification API
  slug: arkova-ai-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-verification-api-openapi.yml
- filename: arkova-ai-webhooks-api-openapi.yml
  format: yaml
  label: Arkova Webhooks API
  slug: arkova-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkova-ai/openapi/arkova-ai-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you are authorized to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use the Service.
    value: '18'
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
name: Arkova
provenance_date: '2026-11-09'
provider_name: Arkova
provider_slug: arkova-ai
slug: arkova-ai-eligibility
source_date: '2026-11-09'
source_filename: arkova-ai-eligibility.yml
source_heading: Eligibility
source_page: https://arkova.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arkova\naid: arkova-ai\nurl: https://arkova.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you are authorized to bind\n    that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form\
  \ a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/arkova-ai/eligibility/arkova-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Arkova's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Trust
- Auditing
- Verification
- Records
- Agents
---
