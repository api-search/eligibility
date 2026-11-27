---
api_specs:
- filename: zelto-action-checks-api-openapi.yml
  format: yaml
  label: Zelto Action checks API
  slug: zelto-action-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-action-checks-api-openapi.yml
- filename: zelto-agents-api-openapi.yml
  format: yaml
  label: Zelto Agents API
  slug: zelto-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-agents-api-openapi.yml
- filename: zelto-buckets-api-openapi.yml
  format: yaml
  label: Zelto Buckets API
  slug: zelto-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-buckets-api-openapi.yml
- filename: zelto-companies-api-openapi.yml
  format: yaml
  label: Zelto Companies API
  slug: zelto-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-companies-api-openapi.yml
- filename: zelto-conversations-api-openapi.yml
  format: yaml
  label: Zelto Conversations API
  slug: zelto-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-conversations-api-openapi.yml
- filename: zelto-customer-metrics-api-openapi.yml
  format: yaml
  label: Zelto Customer Metrics API
  slug: zelto-customer-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-customer-metrics-api-openapi.yml
- filename: zelto-experiments-api-openapi.yml
  format: yaml
  label: Zelto Experiments API
  slug: zelto-experiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-experiments-api-openapi.yml
- filename: zelto-findings-api-openapi.yml
  format: yaml
  label: Zelto Findings API
  slug: zelto-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-findings-api-openapi.yml
- filename: zelto-organizations-api-openapi.yml
  format: yaml
  label: Zelto Organizations API
  slug: zelto-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-organizations-api-openapi.yml
- filename: zelto-reports-api-openapi.yml
  format: yaml
  label: Zelto Reports API
  slug: zelto-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-reports-api-openapi.yml
- filename: zelto-reviews-api-openapi.yml
  format: yaml
  label: Zelto Reviews API
  slug: zelto-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-reviews-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are for business use by users who are at least 18 years old.
    type: business
  minimum_age:
    text: The Services are for business use by users who are at least 18 years old.
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
name: Zelto
provenance_date: '2026-11-10'
provider_name: Zelto
provider_slug: zelto
slug: zelto-eligibility
source_date: '2026-11-10'
source_filename: zelto-eligibility.yml
source_heading: Eligibility
source_page: https://zelto.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zelto\naid: zelto\nurl: https://zelto.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are for business use by users who are at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are for business use by users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/zelto/eligibility/zelto-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Zelto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Voice AI
- QA
- Production
- Analytics
- Monitoring
---
