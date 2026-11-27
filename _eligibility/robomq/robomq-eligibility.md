---
api_specs:
- filename: robomq-openapi-generated.yml
  format: yaml
  label: RoboMQ API
  slug: robomq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robomq/openapi/_ae-authored/robomq-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: à condition que vous ayez l’âge légal et la capacité juridique de conclure un contrat contraignant
    type: other
  minimum_age:
    text: à condition que vous ayez l’âge légal et la capacité juridique de conclure un contrat contraignant
    value: null
  restricted_uses:
  - summary: Resale or access by third parties
    text: Vous acceptez de ne revendre aucun Service RoboMQ à un tiers et de ne rendre aucun Service RoboMQ accessible à un tiers, sauf si vous y êtes expressément autorisé dans un accord écrit distinct.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Pour accéder aux Services RoboMQ, vous pouvez être tenu de fournir une identification actuelle et exacte, y compris une adresse e-mail valide
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RoboMQ
provenance_date: '2026-11-10'
provider_name: RoboMQ
provider_slug: robomq
slug: robomq-eligibility
source_date: '2026-11-10'
source_filename: robomq-eligibility.yml
source_heading: Eligibility
source_page: https://www.robomq.io/fr/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RoboMQ\naid: robomq\nurl: https://www.robomq.io/fr/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: à condition que vous ayez l’âge légal et la capacité juridique de conclure un contrat contraignant\nrestricted_uses:\n- summary: Resale or access by third parties\n  text: Vous acceptez de ne revendre aucun Service RoboMQ à un tiers et de ne rendre aucun Service RoboMQ accessible\n    à un tiers, sauf si vous y êtes expressément autorisé dans un accord écrit distinct.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Pour accéder aux Services RoboMQ, vous pouvez être tenu de fournir une identification actuelle et exacte,\n    y compris une adresse e-mail valide\nminimum_age:\n  value: null\n  text: à condition que vous ayez l’âge légal et la capacité juridique de conclure un contrat contraignant\n"
source_yaml_url: https://artifacts.apis.io/robomq/eligibility/robomq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from RoboMQ's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- Cloud
- Event-Driven
- IoT
- Integration
---
