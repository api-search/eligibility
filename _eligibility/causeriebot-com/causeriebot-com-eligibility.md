---
api_specs:
- filename: causeriebot-com-chatbots-api-openapi.yml
  format: yaml
  label: Causerie Chatbots API
  slug: causeriebot-com-chatbots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/causeriebot-com/openapi/causeriebot-com-chatbots-api-openapi.yml
- filename: causeriebot-com-conversations-api-openapi.yml
  format: yaml
  label: Causerie Conversations API
  slug: causeriebot-com-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/causeriebot-com/openapi/causeriebot-com-conversations-api-openapi.yml
- filename: causeriebot-com-leads-api-openapi.yml
  format: yaml
  label: Causerie Leads API
  slug: causeriebot-com-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/causeriebot-com/openapi/causeriebot-com-leads-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Le Service est destiné à un usage professionnel.
    type: business
  - text: Vous devez avoir au moins 18 ans, ou disposer de l'autorisation de votre représentant légal.
    type: individual
  minimum_age:
    text: Vous devez avoir au moins 18 ans
    value: '18'
  restricted_uses:
  - summary: Illegal or abusive content
    text: Diffuser des contenus illégaux, haineux, discriminatoires, pornographiques ou incitant à la violence
  - summary: Deceiving or harassing end users
    text: Tromper, harceler ou escroquer des utilisateurs finaux via vos chatbots
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: L'accès au Service nécessite la création d'un compte avec une adresse e-mail valide ou via Google OAuth.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Causerie
provenance_date: '2026-11-09'
provider_name: Causerie
provider_slug: causeriebot-com
slug: causeriebot-com-eligibility
source_date: '2026-11-09'
source_filename: causeriebot-com-eligibility.yml
source_heading: Eligibility
source_page: https://dashboard.causeriebot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Causerie\naid: causeriebot-com\nurl: https://dashboard.causeriebot.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Le Service est destiné à un usage professionnel.\n- type: individual\n  text: Vous devez avoir au moins 18 ans, ou disposer de l'autorisation de votre représentant légal.\nrestricted_uses:\n- summary: Illegal or abusive content\n  text: Diffuser des contenus illégaux, haineux, discriminatoires, pornographiques ou incitant à la violence\n- summary: Deceiving or harassing end users\n  text: Tromper, harceler ou escroquer\
  \ des utilisateurs finaux via vos chatbots\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: L'accès au Service nécessite la création d'un compte avec une adresse e-mail valide ou via Google OAuth.\nminimum_age:\n  value: '18'\n  text: Vous devez avoir au moins 18 ans\n"
source_yaml_url: https://artifacts.apis.io/causeriebot-com/eligibility/causeriebot-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Causerie's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Chatbots
- Customer Service
- Lead Qualification
- French
---
