---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Vor allem für Online-Händler, Amazon-FBA-Seller, Shopbetreiber, Influencer und Creator.
    type: business
  - text: 'Daneben für alle anderen Selbständigen ohne eigene Rechtsabteilung: Freelancer, Agenturen, Coaches und Berater'
    type: individual
  minimum_age:
    text: null
    value: null
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
name: AnwaltX
provenance_date: '2026-11-09'
provider_name: AnwaltX
provider_slug: anwaltx-de
slug: anwaltx-de-eligibility
source_date: '2026-11-09'
source_filename: anwaltx-de-eligibility.yml
source_heading: Eligibility
source_page: https://anwaltx.de/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnwaltX\naid: anwaltx-de\nurl: https://anwaltx.de/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Vor allem für Online-Händler, Amazon-FBA-Seller, Shopbetreiber, Influencer und Creator.\n- type: individual\n  text: 'Daneben für alle anderen Selbständigen ohne eigene Rechtsabteilung: Freelancer, Agenturen, Coaches und\n    Berater'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anwaltx-de/eligibility/anwaltx-de-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from AnwaltX's own page on 2026-11-09.
synthetic: false
tags:
- Legal Tech
- Artificial Intelligence
- E-Commerce
- Compliance
- Germany
---
