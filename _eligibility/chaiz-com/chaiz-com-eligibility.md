---
api_specs:
- filename: chaiz-com-openapi.yml
  format: yaml
  label: Chaiz Partner API
  slug: chaiz-partner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chaiz-com/openapi/chaiz-com-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Services are available only to individuals in the United States.
  entity_types:
  - text: Our Services are available only to individuals in the United States.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Website.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: The Website is for your personal use only.
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
name: Chaiz
provenance_date: '2026-11-09'
provider_name: Chaiz
provider_slug: chaiz-com
slug: chaiz-com-eligibility
source_date: '2026-11-09'
source_filename: chaiz-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.chaiz.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chaiz\naid: chaiz-com\nurl: https://www.chaiz.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Services are available only to individuals in the United States.\nentity_types:\n- type: individual\n  text: Our Services are available only to individuals in the United States.\nrestricted_uses:\n- summary: Personal use only\n  text: The Website is for your personal use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/chaiz-com/eligibility/chaiz-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Chaiz's own page on 2026-11-09.
synthetic: false
tags:
- Marketplace
- Automotive
- Extended Warranty
- Digital-First
---
