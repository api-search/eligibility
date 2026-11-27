---
api_specs:
- filename: phare-alert-rules-api-openapi.yml
  format: yaml
  label: Phare Alert Rules API
  slug: phare-alert-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-alert-rules-api-openapi.yml
- filename: phare-incidents-api-openapi.yml
  format: yaml
  label: Phare Incidents API
  slug: phare-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-incidents-api-openapi.yml
- filename: phare-integrations-api-openapi.yml
  format: yaml
  label: Phare Integrations API
  slug: phare-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-integrations-api-openapi.yml
- filename: phare-maintenance-windows-api-openapi.yml
  format: yaml
  label: Phare Maintenance Windows API
  slug: phare-maintenance-windows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-maintenance-windows-api-openapi.yml
- filename: phare-monitors-api-openapi.yml
  format: yaml
  label: Phare Monitors API
  slug: phare-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-monitors-api-openapi.yml
- filename: phare-platform-api-openapi.yml
  format: yaml
  label: Phare Platform API
  slug: phare-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-platform-api-openapi.yml
- filename: phare-projects-api-openapi.yml
  format: yaml
  label: Phare Projects API
  slug: phare-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-projects-api-openapi.yml
- filename: phare-reports-api-openapi.yml
  format: yaml
  label: Phare Reports API
  slug: phare-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-reports-api-openapi.yml
- filename: phare-status-pages-api-openapi.yml
  format: yaml
  label: Phare Status Pages API
  slug: phare-status-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-status-pages-api-openapi.yml
- filename: phare-users-api-openapi.yml
  format: yaml
  label: Phare Users API
  slug: phare-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: 'You agree not to use Service: In any way that violates any applicable national or international law or regulation.'
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
name: Phare
provenance_date: '2026-11-10'
provider_name: Phare
provider_slug: phare
slug: phare-eligibility
source_date: '2026-11-10'
source_filename: phare-eligibility.yml
source_heading: Eligibility
source_page: https://phare.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phare\naid: phare\nurl: https://phare.io/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: 'You agree not to use Service: In any way that violates any applicable national or international law or\n    regulation.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/phare/eligibility/phare-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Phare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Monitoring
- Incident Management
- Analytics
- European
---
