---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We control and operate the Site from our offices in the United States of America, and all information is processed within the United States.
  entity_types:
  - text: By submitting information through this Site you represent that you are over the age of 18 or the age of majority in your jurisdiction, if that is older.
    type: individual
  minimum_age:
    text: you are over the age of 18 or the age of majority in your jurisdiction, if that is older.
    value: '18'
  restricted_uses:
  - summary: Unlawful conduct
    text: Constituting or encouraging conduct that would constitute a criminal offense
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
name: Arrcus
provenance_date: '2026-11-09'
provider_name: Arrcus
provider_slug: arrcus
slug: arrcus-eligibility
source_date: '2026-11-09'
source_filename: arrcus-eligibility.yml
source_heading: Eligibility
source_page: https://arrcus.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arrcus\naid: arrcus\nurl: https://arrcus.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We control and operate the Site from our offices in the United States of America, and all information is\n    processed within the United States.\nentity_types:\n- type: individual\n  text: By submitting information through this Site you represent that you are over the age of 18 or the age of\n    majority in your jurisdiction, if that is older.\nrestricted_uses:\n- summary: Unlawful conduct\n  text: Constituting or encouraging conduct that would constitute a criminal offense\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over the age of 18 or the age of majority in your jurisdiction, if that is older.\n"
source_yaml_url: https://artifacts.apis.io/arrcus/eligibility/arrcus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arrcus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Networking
- Network Operating System
- Routing
- Switching
- Artificial Intelligence
- AI Infrastructure
- Edge Computing
- Cloud
---
