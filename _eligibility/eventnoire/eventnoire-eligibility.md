---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the legal age of majority in your jurisdiction) to use Eventnoire independently.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the legal age of majority in your jurisdiction) to use Eventnoire independently.
    value: '18'
  restricted_uses:
  - summary: Automated bots/AI agents buying or reselling tickets
    text: Use of automated scripts, bots, or AI agents to create, purchase, or resell tickets is prohibited unless expressly authorized by Eventnoire.
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
name: Eventnoire
provenance_date: '2026-11-09'
provider_name: Eventnoire
provider_slug: eventnoire
slug: eventnoire-eligibility
source_date: '2026-11-09'
source_filename: eventnoire-eligibility.yml
source_heading: Eligibility
source_page: https://info.eventnoire.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eventnoire\naid: eventnoire\nurl: https://info.eventnoire.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the legal age of majority in your jurisdiction) to use Eventnoire\n    independently.\nrestricted_uses:\n- summary: Automated bots/AI agents buying or reselling tickets\n  text: Use of automated scripts, bots, or AI agents to create, purchase, or resell tickets is prohibited unless\n    expressly authorized by Eventnoire.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the legal age of majority in your jurisdiction) to use Eventnoire\n    independently.\n"
source_yaml_url: https://artifacts.apis.io/eventnoire/eligibility/eventnoire-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Eventnoire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Event
- Ticketing
- Event Discovery
- Event Management
- Culture
- Consumer
---
