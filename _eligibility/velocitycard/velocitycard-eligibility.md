---
api_specs:
- filename: velocitycard-openapi-generated.yml
  format: yaml
  label: VelocityCard Card Issuing API
  slug: velocitycard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/velocitycard/openapi/_ae-authored/velocitycard-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Be a legal resident of the United States or an eligible jurisdiction where Velocity operates.
  entity_types:
  - text: Be at least 18 years of age (or the age of majority in your jurisdiction).
    type: individual
  minimum_age:
    text: Be at least 18 years of age (or the age of majority in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Gambling, adult content, or card-network restricted activities
    text: Conduct gambling, adult content, or other activities restricted by our card network partners.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To help the federal government fight the funding of terrorism and money laundering activities, the USA PATRIOT Act requires all financial institutions and their third parties to obtain, verify, and record information that identifies each person who opens a card account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VelocityCard Card Issuing
provenance_date: '2026-11-10'
provider_name: VelocityCard
provider_slug: velocitycard
slug: velocitycard-eligibility
source_date: '2026-11-10'
source_filename: velocitycard-eligibility.yml
source_heading: Eligibility
source_page: https://www.velocitycard.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VelocityCard Card Issuing\naid: velocitycard\nurl: https://www.velocitycard.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Be a legal resident of the United States or an eligible jurisdiction where Velocity operates.\nentity_types:\n- type: individual\n  text: Be at least 18 years of age (or the age of majority in your jurisdiction).\nrestricted_uses:\n- summary: Gambling, adult content, or card-network restricted activities\n  text: Conduct gambling, adult content, or other activities restricted by our card network partners.\nverification:\n  kyc: true\n  kyb: null\n\
  \  approval_required: null\n  text: To help the federal government fight the funding of terrorism and money laundering activities, the USA PATRIOT\n    Act requires all financial institutions and their third parties to obtain, verify, and record information that\n    identifies each person who opens a card account.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age (or the age of majority in your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/velocitycard/eligibility/velocitycard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from VelocityCard Card Issuing's own page on 2026-11-10.
synthetic: false
tags:
- Card Issuing
- Banking as a Service
- Embedded Finance
- Commercial Cards
- Payments
- Expense Management
---
