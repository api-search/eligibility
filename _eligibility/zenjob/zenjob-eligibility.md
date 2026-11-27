---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Die Nutzung der Plattform ist kostenfrei und nur für volljährige natürliche Personen, die kein Gewerbe betreiben oder sonst gewerblich tätig sind gestattet.
    type: individual
  minimum_age:
    text: Die Nutzung der Plattform ist kostenfrei und nur für volljährige natürliche Personen, die kein Gewerbe betreiben oder sonst gewerblich tätig sind gestattet.
    value: volljährig
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
name: Zenjob
provenance_date: '2026-11-10'
provider_name: Zenjob
provider_slug: zenjob
slug: zenjob-eligibility
source_date: '2026-11-10'
source_filename: zenjob-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenjob.com/de/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zenjob\naid: zenjob\nurl: https://www.zenjob.com/de/agb/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Die Nutzung der Plattform ist kostenfrei und nur für volljährige natürliche Personen, die kein Gewerbe betreiben\n    oder sonst gewerblich tätig sind gestattet.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: volljährig\n  text: Die Nutzung der Plattform ist kostenfrei und nur für volljährige natürliche Personen, die kein Gewerbe betreiben\n    oder\
  \ sonst gewerblich tätig sind gestattet.\n"
source_yaml_url: https://artifacts.apis.io/zenjob/eligibility/zenjob-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Zenjob's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Staffing
- Workforce
- Human Resources
- Temporary Work
- Scheduling
- Time Tracking
- Integration
---
