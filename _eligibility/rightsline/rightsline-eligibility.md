---
api_specs:
- filename: overview
  format: yaml
  label: Rightsline Rights API
  slug: rights-api
  spec_type: Postman
  url: https://www.postman.com/kinlaneapi/rightsline/overview
- filename: postman.yaml
  format: yaml
  label: Rightsline Royalties API
  slug: royalties-api
  spec_type: Postman
  url: https://postman.rightsline.com/
- filename: rightsline-availability-api-openapi.yml
  format: yaml
  label: Rightsline Availability API
  slug: rightsline-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-availability-api-openapi.yml
- filename: rightsline-catalog-api-openapi.yml
  format: yaml
  label: Rightsline Catalog API
  slug: rightsline-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-catalog-api-openapi.yml
- filename: rightsline-contacts-api-openapi.yml
  format: yaml
  label: Rightsline Contacts API
  slug: rightsline-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-contacts-api-openapi.yml
- filename: rightsline-lists-api-openapi.yml
  format: yaml
  label: Rightsline Lists API
  slug: rightsline-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-lists-api-openapi.yml
- filename: rightsline-rights-api-openapi.yml
  format: yaml
  label: Rightsline Rights API
  slug: rightsline-rights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-rights-api-openapi.yml
- filename: rightsline-royalties-api-openapi.yml
  format: yaml
  label: Rightsline Royalties API
  slug: rightsline-royalties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-royalties-api-openapi.yml
- filename: rightsline-templates-api-openapi.yml
  format: yaml
  label: Rightsline Templates API
  slug: rightsline-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-templates-api-openapi.yml
- filename: rightsline-workflows-api-openapi.yml
  format: yaml
  label: Rightsline Workflows API
  slug: rightsline-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-workflows-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk or prohibited AI practices
    text: 'The AI Features are not intended for, and must not be used for: any “prohibited” artificial intelligence practice or “high-risk” use'
  - summary: Significant decisions about individuals
    text: making decisions that produce legal or similarly significant effects on individuals without appropriate human review and compliance with applicable law.
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
name: Rightsline
provenance_date: '2026-11-10'
provider_name: Rightsline
provider_slug: rightsline
slug: rightsline-eligibility
source_date: '2026-11-10'
source_filename: rightsline-eligibility.yml
source_heading: Eligibility
source_page: https://www.rightsline.com/ai-addendum/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rightsline\naid: rightsline\nurl: https://www.rightsline.com/ai-addendum/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk or prohibited AI practices\n  text: 'The AI Features are not intended for, and must not be used for: any “prohibited” artificial intelligence\n    practice or “high-risk” use'\n- summary: Significant decisions about individuals\n  text: making decisions that produce legal or similarly significant effects on individuals without appropriate\n    human review and compliance with applicable law.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rightsline/eligibility/rightsline-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Rightsline's own page on 2026-11-10.
synthetic: false
tags:
- Content Management
- Entertainment
- Media
- Rights Management
- Royalties
---
