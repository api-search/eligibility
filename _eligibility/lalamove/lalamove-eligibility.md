---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served:
    - HK
    text: Terms & Conditions for Hong Kong Users
  entity_types:
  - text: you are at least the age of legal majority in your place of residence and otherwise legally competent to enter into contracts.
    type: individual
  - text: including, without limitation, any organizations that enroll or otherwise access or use the Platform through their respective representatives or employees
    type: business
  - text: independent third party delivery partners (“Delivery Partner”) who provide transportation, logistics and/or delivery services.
    type: other
  minimum_age:
    text: you are at least the age of legal majority in your place of residence and otherwise legally competent to enter into contracts.
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: the Services cannot be used for unlawful purposes, including but not limited to (i) violation of Applicable Law;
  - summary: Fraudulent tipping
    text: You shall not use the Platform or the tipping feature to process fraudulent transactions including without limitation self-tipping
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: proof of identity or other documentations needs to be submitted immediately if requested by Lalamove;
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lalamove
provenance_date: '2026-11-09'
provider_name: Lalamove
provider_slug: lalamove
slug: lalamove-eligibility
source_date: '2026-11-09'
source_filename: lalamove-eligibility.yml
source_heading: Eligibility
source_page: https://www.lalamove.com/en-hk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lalamove\naid: lalamove\nurl: https://www.lalamove.com/en-hk/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - HK\n  excluded: []\n  text: Terms & Conditions for Hong Kong Users\nentity_types:\n- type: individual\n  text: you are at least the age of legal majority in your place of residence and otherwise legally competent to\n    enter into contracts.\n- type: business\n  text: including, without limitation, any organizations that enroll or otherwise access or use the Platform through\n    their respective representatives or employees\n- type: other\n  text: independent\
  \ third party delivery partners (“Delivery Partner”) who provide transportation, logistics and/or\n    delivery services.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: the Services cannot be used for unlawful purposes, including but not limited to (i) violation of Applicable\n    Law;\n- summary: Fraudulent tipping\n  text: You shall not use the Platform or the tipping feature to process fraudulent transactions including without\n    limitation self-tipping\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: proof of identity or other documentations needs to be submitted immediately if requested by Lalamove;\nminimum_age:\n  value: null\n  text: you are at least the age of legal majority in your place of residence and otherwise legally competent to\n    enter into contracts.\n"
source_yaml_url: https://artifacts.apis.io/lalamove/eligibility/lalamove-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Lalamove's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Technology
- Logistics
- Delivery
- Last Mile Delivery
- Couriers
- Transportation
- On-Demand
- Fleet Management
- Shipping
---
