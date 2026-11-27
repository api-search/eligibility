---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: To transact from or within an OFAC-Sanctioned country or any country sanctioned by the United States Department of Treasury;
  entity_types:
  - text: You represent and warrant that you are at least eighteen (18) years of age and have the right, authority, and capacity to enter into these Terms, either on behalf of yourself or the entity that you represent
    type: individual
  minimum_age:
    text: The INK Games Pay App is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Sanctioned-country transactions
    text: To transact from or within an OFAC-Sanctioned country or any country sanctioned by the United States Department of Treasury;
  - summary: Commercial purpose
    text: You may not utilize for any commercial purpose, except as expressly permitted under these Terms;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Receipt of real-world fiat currency requires compliance with applicable laws, which may include anti-money-laundering (AML) and "know-your-client" (KYC) regulations. You will be required to provide personal information in order to receive fiat currency, and may be required to upload documents to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: INK Games
provenance_date: '2026-11-09'
provider_name: INK Games
provider_slug: ink-games
slug: ink-games-eligibility
source_date: '2026-11-09'
source_filename: ink-games-eligibility.yml
source_heading: Eligibility
source_page: https://www.inkgames.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: INK Games\naid: ink-games\nurl: https://www.inkgames.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: To transact from or within an OFAC-Sanctioned country or any country sanctioned by the United States Department\n    of Treasury;\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least eighteen (18) years of age and have the right, authority,\n    and capacity to enter into these Terms, either on behalf of yourself or the entity that you represent\nrestricted_uses:\n- summary: Sanctioned-country transactions\n  text: To\
  \ transact from or within an OFAC-Sanctioned country or any country sanctioned by the United States Department\n    of Treasury;\n- summary: Commercial purpose\n  text: You may not utilize for any commercial purpose, except as expressly permitted under these Terms;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Receipt of real-world fiat currency requires compliance with applicable laws, which may include anti-money-laundering\n    (AML) and \"know-your-client\" (KYC) regulations. You will be required to provide personal information in order\n    to receive fiat currency, and may be required to upload documents to verify your identity.\nminimum_age:\n  value: '18'\n  text: The INK Games Pay App is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/ink-games/eligibility/ink-games-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from INK Games's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Games
- Gaming
- Mobile Games
- Entertainment
- Consumer
- Rewards
- Payments
- Loyalty
- Referrals
- GraphQL
- Content Management
---
