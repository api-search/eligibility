---
api_specs:
- filename: blumira-health-api-openapi.yml
  format: yaml
  label: Blumira Health API
  slug: blumira-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blumira/openapi/blumira-health-api-openapi.yml
- filename: blumira-msp-api-openapi.yml
  format: yaml
  label: Blumira Msp API
  slug: blumira-msp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blumira/openapi/blumira-msp-api-openapi.yml
- filename: blumira-org-api-openapi.yml
  format: yaml
  label: Blumira Org API
  slug: blumira-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blumira/openapi/blumira-org-api-openapi.yml
- filename: blumira-resolutions-api-openapi.yml
  format: yaml
  label: Blumira Resolutions API
  slug: blumira-resolutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blumira/openapi/blumira-resolutions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for the internal business purposes of Customer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with laws
    text: shall use the Service in compliance with all applicable local, state, national and foreign laws, treaties and regulations
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
name: Blumira
provenance_date: '2026-11-09'
provider_name: Blumira
provider_slug: blumira
slug: blumira-eligibility
source_date: '2026-11-09'
source_filename: blumira-eligibility.yml
source_heading: Eligibility
source_page: https://www.blumira.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blumira\naid: blumira\nurl: https://www.blumira.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for the internal business purposes of Customer\nrestricted_uses:\n- summary: Compliance with laws\n  text: shall use the Service in compliance with all applicable local, state, national and foreign laws, treaties\n    and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blumira/eligibility/blumira-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Blumira's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Software-as-a-Service
- Cloud
- IT
---
