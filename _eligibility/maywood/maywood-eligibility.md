---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement
    type: business
  - text: if Customer is an agency of the US Government or any contractor therefor
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Sensitive Data
    text: the Platform is not designed to store Sensitive Data
  - summary: No life-critical uses
    text: including life support systems, emergency services, nuclear facilities, autonomous vehicles, or air traffic control;
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
name: Maywood
provenance_date: '2026-11-10'
provider_name: Maywood
provider_slug: maywood
slug: maywood-eligibility
source_date: '2026-11-10'
source_filename: maywood-eligibility.yml
source_heading: Eligibility
source_page: https://www.maywoodai.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maywood\naid: maywood\nurl: https://www.maywoodai.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement\n- type: government\n  text: if Customer is an agency of the US Government or any contractor therefor\nrestricted_uses:\n- summary: No Sensitive Data\n  text: the Platform is not designed to store Sensitive Data\n- summary: No life-critical uses\n  text: including life support systems, emergency services, nuclear facilities,\
  \ autonomous vehicles, or air traffic\n    control;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/maywood/eligibility/maywood-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Maywood's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Investment Banking
- Financial Services
- Fintech
- Mergers and Acquisitions
- Deal Execution
- Compliance
- Software-as-a-Service
- Y Combinator
---
