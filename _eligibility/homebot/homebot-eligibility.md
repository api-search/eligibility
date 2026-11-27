---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Individual User” means an individual that pays to subscribe to the Service directly.
    type: individual
  - text: “Enterprise” means a business or other organization that enters into an Enterprise Agreement with Homebot.
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: send or store infringing, obscene, threatening, libelous, or otherwise unlawful or tortious material
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
name: Homebot
provenance_date: '2026-11-09'
provider_name: Homebot
provider_slug: homebot
slug: homebot-eligibility
source_date: '2026-11-09'
source_filename: homebot-eligibility.yml
source_heading: Eligibility
source_page: https://homebot.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Homebot\naid: homebot\nurl: https://homebot.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “Individual User” means an individual that pays to subscribe to the Service directly.\n- type: business\n  text: “Enterprise” means a business or other organization that enters into an Enterprise Agreement with Homebot.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: send or store infringing, obscene, threatening, libelous, or otherwise unlawful or tortious material\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/homebot/eligibility/homebot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Homebot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Mortgage
- PropTech
- Fintech
- Homeownership
- Client Engagement
- CRM
- Lead Generation
- Webhook
---
