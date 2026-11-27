---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you agree that you are not (b) a citizen or resident of, or located in, a country or region that is subject to U.S. or other sovereign country sanctions or embargoes
  entity_types:
  - text: A “Member” is an individual that has registered with us to use our Service.
    type: individual
  minimum_age:
    text: Our Website is not intended for use by children under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Sanctioned or prohibited jurisdictions
    text: you agree that you are not (a) a citizen or resident of a country in which use or participation is prohibited by law, decree, regulation, treaty or administrative act
  - summary: Restricted parties
    text: an individual or an individual employed by or associated with an entity identified on the U.S. Department of Commerce’s Denied Persons or Entity List
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
name: Conductor AI
provenance_date: '2026-11-09'
provider_name: Conductor AI
provider_slug: conductor-ai
slug: conductor-ai-eligibility
source_date: '2026-11-09'
source_filename: conductor-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.conductorai.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conductor AI\naid: conductor-ai\nurl: https://www.conductorai.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you agree that you are not (b) a citizen or resident of, or located in, a country or region that is subject\n    to U.S. or other sovereign country sanctions or embargoes\nentity_types:\n- type: individual\n  text: A “Member” is an individual that has registered with us to use our Service.\nrestricted_uses:\n- summary: Sanctioned or prohibited jurisdictions\n  text: you agree that you are not (a) a citizen or resident of a country in which use or participation\
  \ is prohibited\n    by law, decree, regulation, treaty or administrative act\n- summary: Restricted parties\n  text: an individual or an individual employed by or associated with an entity identified on the U.S. Department\n    of Commerce’s Denied Persons or Entity List\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Website is not intended for use by children under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/conductor-ai/eligibility/conductor-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Conductor AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gov Ai
- Artificial Intelligence
- Defense
- Government
- National Security
- Compliance
- Workflow Automation
- Document Review
- AI Agents
---
