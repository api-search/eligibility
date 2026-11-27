---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Flywire helps ... comprehensive sanctions, including, but not limited to, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk People’s Republic (DNR), and Luhansk People’s Republic (LNR) regions of Ukraine (each, a “Sanctioned Location”).
  entity_types:
  - text: If you are using the Platform on behalf of an entity, organization, company, or other payers, you represent and warrant that you have the authority to bind such parties to these Terms
    type: business
  - text: You must be at least 18 years of age to use the Platform.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Sanctions-restricted use
    text: 'You represent and warrant that you are not: (i) located or residing in a Sanctioned Location'
  - summary: Restricted activities list
    text: 'use the Platform for any of the following activities: sexually oriented materials or services, gambling activities, fraud, money-laundering, the funding of terrorist organizations, or the purchase or sale of tobacco, firearms, prescription drugs, or other controlled substances'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You authorize us, directly or through third parties, to make any inquiries we consider necessary to validate the information you have provided to us.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flywire
provenance_date: '2026-11-09'
provider_name: Flywire
provider_slug: flywire
slug: flywire-eligibility
source_date: '2026-11-09'
source_filename: flywire-eligibility.yml
source_heading: Eligibility
source_page: https://www.flywire.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flywire\naid: flywire\nurl: https://www.flywire.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Flywire helps ... comprehensive sanctions, including, but not limited to, Cuba, Iran, North Korea, Syria,\n    and the Crimea, Donetsk People’s Republic (DNR), and Luhansk People’s Republic (LNR) regions of Ukraine (each,\n    a “Sanctioned Location”).\nentity_types:\n- type: business\n  text: If you are using the Platform on behalf of an entity, organization, company, or other payers, you represent\n    and warrant\
  \ that you have the authority to bind such parties to these Terms\n- type: individual\n  text: You must be at least 18 years of age to use the Platform.\nrestricted_uses:\n- summary: Sanctions-restricted use\n  text: 'You represent and warrant that you are not: (i) located or residing in a Sanctioned Location'\n- summary: Restricted activities list\n  text: 'use the Platform for any of the following activities: sexually oriented materials or services, gambling\n    activities, fraud, money-laundering, the funding of terrorist organizations, or the purchase or sale of tobacco,\n    firearms, prescription drugs, or other controlled substances'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You authorize us, directly or through third parties, to make any inquiries we consider necessary to validate\n    the information you have provided to us.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/flywire/eligibility/flywire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Flywire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cross-Border Payments
- Fintech
- Education Payments
- Healthcare Payments
- Travel Payments
- B2B Payments
- Checkout
- Webhook
---
