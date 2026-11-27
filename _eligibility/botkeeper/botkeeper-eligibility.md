---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for business use and are not directed to children under 13.
    type: business
  - text: You may use the Services only if you can form a binding contract with Xendoo and only in compliance with the Agreement and applicable law.
    type: individual
  minimum_age:
    text: The Services are intended for business use and are not directed to children under 13.
    value: null
  restricted_uses:
  - summary: Regulated health, education and child data
    text: Customer must not use the Services to process protected health information subject to HIPAA, student education records subject to FERPA, information collected from children in a manner subject to COPPA
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
name: Botkeeper
provenance_date: '2026-11-09'
provider_name: Botkeeper
provider_slug: botkeeper
slug: botkeeper-eligibility
source_date: '2026-11-09'
source_filename: botkeeper-eligibility.yml
source_heading: Eligibility
source_page: https://www.botkeeper.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Botkeeper\naid: botkeeper\nurl: https://www.botkeeper.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for business use and are not directed to children under 13.\n- type: individual\n  text: You may use the Services only if you can form a binding contract with Xendoo and only in compliance with\n    the Agreement and applicable law.\nrestricted_uses:\n- summary: Regulated health, education and child data\n  text: Customer must not use the Services to process protected health information subject to\
  \ HIPAA, student education\n    records subject to FERPA, information collected from children in a manner subject to COPPA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The Services are intended for business use and are not directed to children under 13.\n"
source_yaml_url: https://artifacts.apis.io/botkeeper/eligibility/botkeeper-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Botkeeper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Bookkeeping
- Financial Services
- Artificial Intelligence
- Automation
- Software-as-a-Service
- Banking Data
- Practice Management
- Small Business
---
