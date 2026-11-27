---
api_specs:
- filename: ciwregistration-co-uk-enquiry-api-openapi.yml
  format: yaml
  label: CIW Registration Enquiry API
  slug: ciwregistration-co-uk-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciwregistration-co-uk/openapi/ciwregistration-co-uk-enquiry-api-openapi.yml
- filename: ciwregistration-co-uk-mcp-api-openapi.yml
  format: yaml
  label: CIW Registration MCP API
  slug: ciwregistration-co-uk-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciwregistration-co-uk/openapi/ciwregistration-co-uk-mcp-api-openapi.yml
claim_count: 1
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
  - summary: Not professional advice
    text: Nothing here is financial, legal, tax, medical or other regulated advice
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
name: CIW Registration
provenance_date: '2026-11-09'
provider_name: CIW Registration
provider_slug: ciwregistration-co-uk
slug: ciwregistration-co-uk-eligibility
source_date: '2026-11-09'
source_filename: ciwregistration-co-uk-eligibility.yml
source_heading: Eligibility
source_page: https://ciwregistration.co.uk/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CIW Registration\naid: ciwregistration-co-uk\nurl: https://ciwregistration.co.uk/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not professional advice\n  text: Nothing here is financial, legal, tax, medical or other regulated advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ciwregistration-co-uk/eligibility/ciwregistration-co-uk-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CIW Registration's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Wales
- Registration
- Social Care
- Information Services
---
