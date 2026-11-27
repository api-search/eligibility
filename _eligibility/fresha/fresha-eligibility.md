---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are in the United Kingdom ... If you are outside the United Kingdom, local consumer law may apply.
  entity_types:
  - text: If you are a consumer, you have legal rights in relation to services that are not performed with reasonable care and skill or are otherwise not as described.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted access for fraud or abuse
    text: we reasonably suspect fraud or money laundering by you or someone using your Fresha Account
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Fresha may verify the information that you provide, and may refuse use of the Fresha Services or Fresha Platform without providing reasons.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fresha
provenance_date: '2026-11-09'
provider_name: Fresha
provider_slug: fresha
slug: fresha-eligibility
source_date: '2026-11-09'
source_filename: fresha-eligibility.yml
source_heading: Eligibility
source_page: https://terms.fresha.com/terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fresha\naid: fresha\nurl: https://terms.fresha.com/terms-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are in the United Kingdom ... If you are outside the United Kingdom, local consumer law may apply.\nentity_types:\n- type: individual\n  text: If you are a consumer, you have legal rights in relation to services that are not performed with reasonable\n    care and skill or are otherwise not as described.\nrestricted_uses:\n- summary: Restricted access for fraud or abuse\n  text: we reasonably suspect fraud or money laundering by you or someone using your Fresha\
  \ Account\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Fresha may verify the information that you provide, and may refuse use of the Fresha Services or Fresha\n    Platform without providing reasons.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fresha/eligibility/fresha-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Fresha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Applicative Saas
- Beauty
- Wellness
- Booking
- Scheduling
- Payments
- Marketplace
- Point-of-Sale
- Salon
- Spa
- Software-as-a-Service
---
