---
api_specs:
- filename: affitor-com-tracking-api-openapi.yml
  format: yaml
  label: Affitor Tracking API
  slug: affitor-com-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affitor-com/openapi/affitor-com-tracking-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ Advertiser ” means a company that creates and manages an affiliate program through Affitor.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Partner fraud and attribution manipulation
    text: Attempting to manipulate or circumvent the attribution system.
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
name: Affitor
provenance_date: '2026-11-09'
provider_name: Affitor
provider_slug: affitor-com
slug: affitor-com-eligibility
source_date: '2026-11-09'
source_filename: affitor-com-eligibility.yml
source_heading: Eligibility
source_page: https://affitor.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Affitor\naid: affitor-com\nurl: https://affitor.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “ Advertiser ” means a company that creates and manages an affiliate program through Affitor.\nrestricted_uses:\n- summary: Partner fraud and attribution manipulation\n  text: Attempting to manipulate or circumvent the attribution system.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/affitor-com/eligibility/affitor-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Affitor's own page on 2026-11-09.
synthetic: false
tags:
- Affiliates
- Software-as-a-Service
- Artificial Intelligence
- Marketing
- Affiliate Network
---
