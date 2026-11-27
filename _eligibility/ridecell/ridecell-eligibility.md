---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only persons over 18 years of age may register for the Service.
    type: individual
  minimum_age:
    text: Only persons over 18 years of age may register for the Service.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Your use of the Service is for your personal, non-commercial use.
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
name: Ridecell
provenance_date: '2026-11-10'
provider_name: Ridecell
provider_slug: ridecell
slug: ridecell-eligibility
source_date: '2026-11-10'
source_filename: ridecell-eligibility.yml
source_heading: Eligibility
source_page: https://ridecell.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ridecell\naid: ridecell\nurl: https://ridecell.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only persons over 18 years of age may register for the Service.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: Your use of the Service is for your personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Only persons over 18 years of age may register for the Service.\n"
source_yaml_url: https://artifacts.apis.io/ridecell/eligibility/ridecell-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ridecell's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- Fleet Management
- Mobility
- Automotive
- Artificial Intelligence
- Asset Intelligence
- Automation
---
