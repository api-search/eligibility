---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for developers and businesses, not for children.
    type: developer
  - text: The Service is intended for developers and businesses, not for children.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction, if higher) to create an account or use the Service.
    value: '18'
  restricted_uses:
  - summary: No deepfakes or sexual imagery of real people
    text: requests indicating child sexual content, deepfakes/face-swaps, or sexual imagery of real, identifiable people are refused with a content_policy error and logged.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address to register. Disposable/temporary email domains are rejected.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: archtools-dev
provenance_date: '2026-11-09'
provider_name: archtools-dev
provider_slug: archtools-dev
slug: archtools-dev-eligibility
source_date: '2026-11-09'
source_filename: archtools-dev-eligibility.yml
source_heading: Eligibility
source_page: https://archtools.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: archtools-dev\naid: archtools-dev\nurl: https://archtools.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: The Service is intended for developers and businesses, not for children.\n- type: business\n  text: The Service is intended for developers and businesses, not for children.\nrestricted_uses:\n- summary: No deepfakes or sexual imagery of real people\n  text: requests indicating child sexual content, deepfakes/face-swaps, or sexual imagery of real, identifiable\n    people are refused with a content_policy error and logged.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address to register. Disposable/temporary email domains are rejected.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction, if higher) to create an\n    account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/archtools-dev/eligibility/archtools-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from archtools-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Tools
- Automation
- MCP
---
