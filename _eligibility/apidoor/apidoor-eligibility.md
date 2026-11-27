---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The initial seller-to-customer monetization offering is limited to sellers based in the United States using eligible, verified US connected payment accounts, and customers based in the United States with US billing addresses.
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into a binding agreement.
    type: individual
  - text: Sellers and customers may act individually or for a business, but may not create an account for someone else without authorization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into a binding agreement.
    value: '18'
  restricted_uses:
  - summary: Safety-critical uses
    text: Use the service for emergency response, life-support, weapons control, or another safety-critical purpose where interruption or incorrect operation could reasonably cause death, personal injury, or severe physical damage.
  - summary: Protected health information and sensitive data
    text: Unless Apidoor expressly agrees in a separate written agreement that covers the relevant workload, you must not use the service to process protected health information subject to a business associate agreement, complete payment-card numbers, card security codes, PINs
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
name: Apidoor
provenance_date: '2026-11-09'
provider_name: Apidoor
provider_slug: apidoor
slug: apidoor-eligibility
source_date: '2026-11-09'
source_filename: apidoor-eligibility.yml
source_heading: Eligibility
source_page: https://apidoor.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apidoor\naid: apidoor\nurl: https://apidoor.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The initial seller-to-customer monetization offering is limited to sellers based in the United States using\n    eligible, verified US connected payment accounts, and customers based in the United States with US billing addresses.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into a binding agreement.\n- type: business\n  text: Sellers and customers may act individually or for a business, but may not create an account\
  \ for someone\n    else without authorization.\nrestricted_uses:\n- summary: Safety-critical uses\n  text: Use the service for emergency response, life-support, weapons control, or another safety-critical purpose\n    where interruption or incorrect operation could reasonably cause death, personal injury, or severe physical\n    damage.\n- summary: Protected health information and sensitive data\n  text: Unless Apidoor expressly agrees in a separate written agreement that covers the relevant workload, you must\n    not use the service to process protected health information subject to a business associate agreement, complete\n    payment-card numbers, card security codes, PINs\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/apidoor/eligibility/apidoor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Apidoor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Gateway
- API Monetization
- APIKeys
- Rate Limiting
- Usage Analytics
- API Subscriptions
- Billing
---
