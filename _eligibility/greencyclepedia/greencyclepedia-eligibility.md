---
api_specs:
- filename: greencyclepedia-openapi-generated.yml
  format: yaml
  label: GreenCycle Compound Atlas API
  slug: greencyclepedia-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencyclepedia/openapi/_ae-authored/greencyclepedia-openapi-generated.yml
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
  - summary: Not medical advice
    text: Educational reference, not medical advice. No doses are given.
  verification:
    approval_required: false
    kyb: null
    kyc: false
    text: The files under /api/ and the MCP server at https://greencyclepedia.com/mcp are free, read only and need no key or account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GreenCycle Compound Atlas
provenance_date: '2026-11-09'
provider_name: GreenCycle Compound Atlas
provider_slug: greencyclepedia
slug: greencyclepedia-eligibility
source_date: '2026-11-09'
source_filename: greencyclepedia-eligibility.yml
source_heading: Eligibility
source_page: https://greencyclepedia.com/about/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GreenCycle Compound Atlas\naid: greencyclepedia\nurl: https://greencyclepedia.com/about/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice\n  text: Educational reference, not medical advice. No doses are given.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: false\n  text: The files under /api/ and the MCP server at https://greencyclepedia.com/mcp are free, read only and need\n    no key or account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/greencyclepedia/eligibility/greencyclepedia-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from GreenCycle Compound Atlas's own page on 2026-11-09.
synthetic: false
tags:
- Cannabis
- Anatomy Atlas
- Educational Reference
---
