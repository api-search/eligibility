---
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
  - summary: Unlawful analytics on individuals
    text: collect analytics on individuals in violation of applicable law or without a lawful basis
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Signing up creates a tenant and its first API key with no card required.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: analyga
provenance_date: '2026-11-09'
provider_name: analyga
provider_slug: analyga-com
slug: analyga-com-eligibility
source_date: '2026-11-09'
source_filename: analyga-com-eligibility.yml
source_heading: Eligibility
source_page: https://analyga.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: analyga\naid: analyga-com\nurl: https://analyga.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful analytics on individuals\n  text: collect analytics on individuals in violation of applicable law or without a lawful basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Signing up creates a tenant and its first API key with no card required.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/analyga-com/eligibility/analyga-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from analyga's own page on 2026-11-09.
synthetic: false
tags:
- AI-native
- Software-as-a-Service
- Revenue Analytics
- Dashboards
- MCP
---
