---
api_specs:
- filename: brain-tube-com-api-openapi.json
  format: json
  label: BrainTube REST API API
  slug: braintube-rest-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brain-tube-com/openapi/_original/brain-tube-com-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 13 years of age and have the legal capacity to enter into these Terms
    type: individual
  minimum_age:
    text: you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Unlawful use
    text: Violate any applicable laws or regulations
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
name: BrainTube
provenance_date: '2026-11-09'
provider_name: BrainTube
provider_slug: brain-tube-com
slug: brain-tube-com-eligibility
source_date: '2026-11-09'
source_filename: brain-tube-com-eligibility.yml
source_heading: Eligibility
source_page: https://brain-tube.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrainTube\naid: brain-tube-com\nurl: https://brain-tube.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 13 years of age and have the legal capacity to enter into these Terms\nrestricted_uses:\n- summary: Unlawful use\n  text: Violate any applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/brain-tube-com/eligibility/brain-tube-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BrainTube's own page on 2026-11-09.
synthetic: false
tags:
- AI Integration
- MCP
---
