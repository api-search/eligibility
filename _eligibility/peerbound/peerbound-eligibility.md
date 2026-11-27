---
api_specs:
- filename: peerbound-activities-api-openapi.yml
  format: yaml
  label: Peerbound Activities API
  slug: peerbound-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peerbound/openapi/peerbound-activities-api-openapi.yml
- filename: peerbound-moments-api-openapi.yml
  format: yaml
  label: Peerbound Moments API
  slug: peerbound-moments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peerbound/openapi/peerbound-moments-api-openapi.yml
- filename: peerbound-notes-api-openapi.yml
  format: yaml
  label: Peerbound Notes API
  slug: peerbound-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peerbound/openapi/peerbound-notes-api-openapi.yml
- filename: peerbound-reviews-api-openapi.yml
  format: yaml
  label: Peerbound Reviews API
  slug: peerbound-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peerbound/openapi/peerbound-reviews-api-openapi.yml
- filename: peerbound-stories-api-openapi.yml
  format: yaml
  label: Peerbound Stories API
  slug: peerbound-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peerbound/openapi/peerbound-stories-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are authorized to enter into these ToS on behalf of the company you represent and that your use of the Service complies with all applicable laws and regulations.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: Use the Service for any illegal or unauthorized purpose.
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
name: Peerbound
provenance_date: '2026-11-10'
provider_name: Peerbound
provider_slug: peerbound
slug: peerbound-eligibility
source_date: '2026-11-10'
source_filename: peerbound-eligibility.yml
source_heading: Eligibility
source_page: https://www.peerbound.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peerbound\naid: peerbound\nurl: https://www.peerbound.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You represent and warrant that you are authorized to enter into these ToS on behalf of the company you represent\n    and that your use of the Service complies with all applicable laws and regulations.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: Use the Service for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/peerbound/eligibility/peerbound-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Peerbound's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Sales Enablement
- Customer Proof
- Analytics
---
