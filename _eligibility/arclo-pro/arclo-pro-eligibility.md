---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and using Arclo for a business, not personal or household purposes.
    type: business
  minimum_age:
    text: You must be at least 18 and using Arclo for a business, not personal or household purposes.
    value: '18'
  restricted_uses:
  - summary: Patient information
    text: you should not paste patient information into site content or change requests.
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
name: Arclo
provenance_date: '2026-11-09'
provider_name: Arclo
provider_slug: arclo-pro
slug: arclo-pro-eligibility
source_date: '2026-11-09'
source_filename: arclo-pro-eligibility.yml
source_heading: Eligibility
source_page: https://arclo.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arclo\naid: arclo-pro\nurl: https://arclo.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must be at least 18 and using Arclo for a business, not personal or household purposes.\nrestricted_uses:\n- summary: Patient information\n  text: you should not paste patient information into site content or change requests.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and using Arclo for a business, not personal or household purposes.\n"
source_yaml_url: https://artifacts.apis.io/arclo-pro/eligibility/arclo-pro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Arclo's own page on 2026-11-09.
synthetic: false
tags:
- Websites
- Growth
- Local Business
- SEO
- Artificial Intelligence
---
