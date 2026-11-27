---
api_specs:
- filename: google-docs-documents-api-openapi.yml
  format: yaml
  label: Google Docs Documents API
  slug: google-docs-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-docs/openapi/google-docs-documents-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs and may not accept the Terms if ... you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: if you are a business, you will defend and indemnify Google
    type: business
  - text: you are not of legal age to form a binding contract with Google
    type: individual
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: ITAR-regulated data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: HIPAA
    text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
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
name: Google Docs
provenance_date: '2026-11-09'
provider_name: Google Docs
provider_slug: google-docs
slug: google-docs-eligibility
source_date: '2026-11-09'
source_filename: google-docs-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Docs\naid: google-docs\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs and may not accept the Terms if ... you are a person barred from using or receiving\n    the APIs under the applicable laws of the United States or other countries including the country in which you\n    are resident or from which you use the APIs.\nentity_types:\n- type: business\n  text: if you are a business, you will defend and indemnify Google\n- type: individual\n  text: you are not of legal age to form a binding contract with Google\n\
  restricted_uses:\n- summary: High-risk activities\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: ITAR-regulated data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: HIPAA\n  text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information\n    to Google unless you have received prior written consent to such use from Google.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-docs/eligibility/google-docs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Google Docs's own page on 2026-11-09.
synthetic: false
tags:
- Collaboration
- Documents
- Google Workspace
- Productivity
- Word Processing
---
