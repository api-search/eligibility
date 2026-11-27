---
api_specs:
- filename: brandpilot-dev-openapi-generated.yml
  format: yaml
  label: BrandPilot API
  slug: brandpilot-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandpilot-dev/openapi/_ae-authored/brandpilot-dev-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be 18 years or older to use this service.
    value: '18'
  restricted_uses:
  - summary: Unlawful, harmful or infringing content
    text: Submit briefs designed to generate harmful, deceptive, or infringing content
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
name: BrandPilot
provenance_date: '2026-11-09'
provider_name: BrandPilot
provider_slug: brandpilot-dev
slug: brandpilot-dev-eligibility
source_date: '2026-11-09'
source_filename: brandpilot-dev-eligibility.yml
source_heading: Eligibility
source_page: https://brandpilot.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrandPilot\naid: brandpilot-dev\nurl: https://brandpilot.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, harmful or infringing content\n  text: Submit briefs designed to generate harmful, deceptive, or infringing content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to use this service.\n"
source_yaml_url: https://artifacts.apis.io/brandpilot-dev/eligibility/brandpilot-dev-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from BrandPilot's own page on 2026-11-09.
synthetic: false
tags:
- Branding
- Design
- Software-as-a-Service
- Marketing
---
