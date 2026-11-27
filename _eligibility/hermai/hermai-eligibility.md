---
api_specs:
- filename: hermai-api-openapi.json
  format: json
  label: Hermai Agent-Native API API
  slug: hermai-agent-native-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hermai/openapi/_original/hermai-api-openapi.json
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
  - summary: Fetching personal data
    text: Don't use Hermai to fetch personal data of others without lawful basis
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may sign up with a verified email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hermai Brand API
provenance_date: '2026-11-09'
provider_name: Hermai Brand API
provider_slug: hermai
slug: hermai-eligibility
source_date: '2026-11-09'
source_filename: hermai-eligibility.yml
source_heading: Eligibility
source_page: https://hermai.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hermai Brand API\naid: hermai\nurl: https://hermai.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fetching personal data\n  text: Don't use Hermai to fetch personal data of others without lawful basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may sign up with a verified email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hermai/eligibility/hermai-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Hermai Brand API's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Branding
- Marketing
- Software-as-a-Service
---
