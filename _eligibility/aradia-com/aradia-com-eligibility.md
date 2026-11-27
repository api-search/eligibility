---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Partners and legally registered autonomous entities must complete Stripe Connected Account onboarding, including identity verification (KYC/KYB) and bank/treasury setup.
    type: business
  - text: AI Agents operating via programmatic headers or cryptographic wallets are expressly permitted to register as Partners and route commissions to their own managed Stripe Connect accounts or treasuries.
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated-context use is customer responsibility
    text: You assume total responsibility for how the appliance is used in medical, legal, or financial contexts.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Human partners and legally registered autonomous entities must complete Stripe Connected Account onboarding, including identity verification (KYC/KYB) and bank/treasury setup. Onboarding and risk-management are handled entirely by Stripe.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aradia Systems
provenance_date: '2026-11-09'
provider_name: Aradia Systems
provider_slug: aradia-com
slug: aradia-com-eligibility
source_date: '2026-11-09'
source_filename: aradia-com-eligibility.yml
source_heading: Eligibility
source_page: https://aradia.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aradia Systems\naid: aradia-com\nurl: https://aradia.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Partners and legally registered autonomous entities must complete Stripe Connected Account onboarding, including\n    identity verification (KYC/KYB) and bank/treasury setup.\n- type: developer\n  text: AI Agents operating via programmatic headers or cryptographic wallets are expressly permitted to register\n    as Partners and route commissions to their own managed Stripe Connect accounts or treasuries.\nrestricted_uses:\n\
  - summary: Regulated-context use is customer responsibility\n  text: You assume total responsibility for how the appliance is used in medical, legal, or financial contexts.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Human partners and legally registered autonomous entities must complete Stripe Connected Account onboarding,\n    including identity verification (KYC/KYB) and bank/treasury setup. Onboarding and risk-management are handled\n    entirely by Stripe.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aradia-com/eligibility/aradia-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Aradia Systems's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Private AI
- Infrastructure
- NVIDIA
- DGX
- Sovereign
- On-Prem
- AI Agents
---
