---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Wenn der Käufer Verbraucher im Sinne des § 13 BGB ist, steht ihm ein gesetzliches Widerrufsrecht nach §§ 312g, 355 BGB zu.
    type: individual
  - text: Gegenüber Unternehmern beträgt die Gewährleistungspflicht auf von everdrop gelieferte Produkte 12 Monate.
    type: business
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
name: Everdrop
provenance_date: '2026-11-09'
provider_name: Everdrop
provider_slug: everdrop
slug: everdrop-eligibility
source_date: '2026-11-09'
source_filename: everdrop-eligibility.yml
source_heading: Eligibility
source_page: https://www.everdrop.de/en/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everdrop\naid: everdrop\nurl: https://www.everdrop.de/en/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Wenn der Käufer Verbraucher im Sinne des § 13 BGB ist, steht ihm ein gesetzliches Widerrufsrecht nach §§\n    312g, 355 BGB zu.\n- type: business\n  text: Gegenüber Unternehmern beträgt die Gewährleistungspflicht auf von everdrop gelieferte Produkte 12 Monate.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/everdrop/eligibility/everdrop-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Everdrop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Consumer Goods
- E-Commerce
- Sustainability
- Cleaning Products
- Direct to Consumer
- Subscription
---
