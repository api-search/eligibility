---
api_specs:
- filename: athenahq-ai-ai-access-api-openapi.yml
  format: yaml
  label: AthenaHQ AI Access API
  slug: athenahq-ai-ai-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-ai-access-api-openapi.yml
- filename: athenahq-ai-ai-search-value-api-openapi.yml
  format: yaml
  label: AthenaHQ AI Search Value API
  slug: athenahq-ai-ai-search-value-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-ai-search-value-api-openapi.yml
- filename: athenahq-ai-analytics-api-openapi.yml
  format: yaml
  label: AthenaHQ Analytics API
  slug: athenahq-ai-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-analytics-api-openapi.yml
- filename: athenahq-ai-attributes-api-openapi.yml
  format: yaml
  label: AthenaHQ Attributes API
  slug: athenahq-ai-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-attributes-api-openapi.yml
- filename: athenahq-ai-basics-api-openapi.yml
  format: yaml
  label: AthenaHQ Basics API
  slug: athenahq-ai-basics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-basics-api-openapi.yml
- filename: athenahq-ai-billing-api-openapi.yml
  format: yaml
  label: AthenaHQ Billing API
  slug: athenahq-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-billing-api-openapi.yml
- filename: athenahq-ai-content-api-openapi.yml
  format: yaml
  label: AthenaHQ Content API
  slug: athenahq-ai-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-content-api-openapi.yml
- filename: athenahq-ai-groups-api-openapi.yml
  format: yaml
  label: AthenaHQ Groups API
  slug: athenahq-ai-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-groups-api-openapi.yml
- filename: athenahq-ai-knowledge-base-api-openapi.yml
  format: yaml
  label: AthenaHQ Knowledge Base API
  slug: athenahq-ai-knowledge-base-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-knowledge-base-api-openapi.yml
- filename: athenahq-ai-metrics-api-openapi.yml
  format: yaml
  label: AthenaHQ Metrics API
  slug: athenahq-ai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-metrics-api-openapi.yml
- filename: athenahq-ai-pitch-workspace-api-openapi.yml
  format: yaml
  label: AthenaHQ Pitch Workspace API
  slug: athenahq-ai-pitch-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-pitch-workspace-api-openapi.yml
- filename: athenahq-ai-seo-recommendations-api-openapi.yml
  format: yaml
  label: AthenaHQ SEO Recommendations API
  slug: athenahq-ai-seo-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-seo-recommendations-api-openapi.yml
- filename: athenahq-ai-sources-api-openapi.yml
  format: yaml
  label: AthenaHQ Sources API
  slug: athenahq-ai-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-sources-api-openapi.yml
- filename: athenahq-ai-team-management-api-openapi.yml
  format: yaml
  label: AthenaHQ Team Management API
  slug: athenahq-ai-team-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-team-management-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into a binding agreement to use the Services.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into a binding agreement to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: You may not access or use the Services in violation of U.S. export-control or sanctions laws.
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
name: AthenaHQ
provenance_date: '2026-11-09'
provider_name: AthenaHQ
provider_slug: athenahq-ai
slug: athenahq-ai-eligibility
source_date: '2026-11-09'
source_filename: athenahq-ai-eligibility.yml
source_heading: Eligibility
source_page: https://athenahq.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AthenaHQ\naid: athenahq-ai\nurl: https://athenahq.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into a binding agreement to use the Services.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: You may not access or use the Services in violation of U.S. export-control or sanctions\
  \ laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into a binding agreement to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/athenahq-ai/eligibility/athenahq-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AthenaHQ's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Search
- Platform
- Enterprise
---
