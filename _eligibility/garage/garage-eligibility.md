---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served: []
    text: 'Goods destined for the following countries cannot be listed or sold on the platform: Cuba, Iran, North Korea, Syria, Russia, Belarus, or the Crimea, Luhansk, and Donetsk Regions of Ukraine.'
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract with Garage in order to use Garage
    type: individual
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract with Garage in order to use Garage
    value: '18'
  restricted_uses:
  - summary: Stripe restricted business categories
    text: Users may not engage in any business or activity that falls under the categories listed on the Stripe Restricted Business List
  - summary: Stolen, counterfeit or illegal items
    text: List or purchase items that are illegal, stolen, counterfeit, or infringe on intellectual property rights.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use Garage, you must create an account by providing accurate and complete information.
excluded_countries:
- CU
- IR
- KP
- SY
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Garage
provenance_date: '2026-11-09'
provider_name: Garage
provider_slug: garage
slug: garage-eligibility
source_date: '2026-11-09'
source_filename: garage-eligibility.yml
source_heading: Eligibility
source_page: https://www.shopgarage.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Garage\naid: garage\nurl: https://www.shopgarage.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: 'Goods destined for the following countries cannot be listed or sold on the platform: Cuba, Iran, North\n    Korea, Syria, Russia, Belarus, or the Crimea, Luhansk, and Donetsk Regions of Ukraine.'\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract with Garage in order to use\n    Garage\nrestricted_uses:\n- summary: Stripe restricted business\
  \ categories\n  text: Users may not engage in any business or activity that falls under the categories listed on the Stripe Restricted\n    Business List\n- summary: Stolen, counterfeit or illegal items\n  text: List or purchase items that are illegal, stolen, counterfeit, or infringe on intellectual property rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use Garage, you must create an account by providing accurate and complete information.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract with Garage in order to use\n    Garage\n"
source_yaml_url: https://artifacts.apis.io/garage/eligibility/garage-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Garage's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Marketplace
- Emergency Vehicles
- Fire Trucks
- Ambulances
- Municipal Equipment
- Government Surplus
---
