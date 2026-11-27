---
api_specs:
- filename: clearbounce-net-openapi-generated.yml
  format: yaml
  label: ClearBounce API
  slug: clearbounce-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbounce-net/openapi/_ae-authored/clearbounce-net-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old or have parental consent
    type: individual
  minimum_age:
    text: Be at least 18 years old or have parental consent
    value: '18'
  restricted_uses:
  - summary: Unlawful or IP-infringing use
    text: Violate any applicable laws or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Create an account with accurate information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClearBounce
provenance_date: '2026-11-09'
provider_name: ClearBounce
provider_slug: clearbounce-net
slug: clearbounce-net-eligibility
source_date: '2026-11-09'
source_filename: clearbounce-net-eligibility.yml
source_heading: Eligibility
source_page: https://clearbounce.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClearBounce\naid: clearbounce-net\nurl: https://clearbounce.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old or have parental consent\nrestricted_uses:\n- summary: Unlawful or IP-infringing use\n  text: Violate any applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Create an account with accurate information\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old or have parental consent\n"
source_yaml_url: https://artifacts.apis.io/clearbounce-net/eligibility/clearbounce-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from ClearBounce's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- List Cleaning
- Form Validation
- Deliverability
- Marketing Tools
---
