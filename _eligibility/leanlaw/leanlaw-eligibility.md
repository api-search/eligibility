---
api_specs:
- filename: leanlaw-client-api-openapi.yml
  format: yaml
  label: LeanLaw Client API
  slug: leanlaw-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-client-api-openapi.yml
- filename: leanlaw-codes-api-openapi.yml
  format: yaml
  label: LeanLaw Codes API
  slug: leanlaw-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-codes-api-openapi.yml
- filename: leanlaw-expense-api-openapi.yml
  format: yaml
  label: LeanLaw Expense API
  slug: leanlaw-expense-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-expense-api-openapi.yml
- filename: leanlaw-fixedfee-api-openapi.yml
  format: yaml
  label: LeanLaw Fixed Fee API
  slug: leanlaw-fixedfee-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-fixedfee-api-openapi.yml
- filename: leanlaw-invoice-api-openapi.yml
  format: yaml
  label: LeanLaw Invoice API
  slug: leanlaw-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-invoice-api-openapi.yml
- filename: leanlaw-matter-api-openapi.yml
  format: yaml
  label: LeanLaw Matter API
  slug: leanlaw-matter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-matter-api-openapi.yml
- filename: leanlaw-practicearea-api-openapi.yml
  format: yaml
  label: LeanLaw Practice Area API
  slug: leanlaw-practicearea-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-practicearea-api-openapi.yml
- filename: leanlaw-user-api-openapi.yml
  format: yaml
  label: LeanLaw User API
  slug: leanlaw-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-user-api-openapi.yml
- filename: leanlaw-custom-field-api-openapi.yml
  format: yaml
  label: LeanLaw Custom Field API
  slug: leanlaw-custom-field-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-custom-field-api-openapi.yml
- filename: leanlaw-time-entry-api-openapi.yml
  format: yaml
  label: LeanLaw Time entry API
  slug: leanlaw-time-entry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leanlaw/openapi/leanlaw-time-entry-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if entering into this Agreement for an organization, that Customer has the legal authority to bind that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Obscene materials
    text: store, distribute, or access obscene materials or activities
  - summary: Infringing or unlawful use
    text: use the Services or Documentation in any manner or for any purpose that infringes, misappropriates, or otherwise violates any intellectual property right
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
name: LeanLaw
provenance_date: '2026-11-09'
provider_name: LeanLaw
provider_slug: leanlaw
slug: leanlaw-eligibility
source_date: '2026-11-09'
source_filename: leanlaw-eligibility.yml
source_heading: Eligibility
source_page: https://www.leanlaw.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LeanLaw\naid: leanlaw\nurl: https://www.leanlaw.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if entering into this Agreement for an organization, that Customer has the legal authority to bind that\n    organization\nrestricted_uses:\n- summary: Obscene materials\n  text: store, distribute, or access obscene materials or activities\n- summary: Infringing or unlawful use\n  text: use the Services or Documentation in any manner or for any purpose that infringes, misappropriates, or otherwise\n    violates any intellectual property\
  \ right\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/leanlaw/eligibility/leanlaw-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from LeanLaw's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Legal Billing
- Law Firms
- Time Tracking
- Billing
- Invoicing
- Accounting
- Trust Accounting
- Practice Management
- QuickBooks
- Payments
- Legal Tech
- Software-as-a-Service
---
