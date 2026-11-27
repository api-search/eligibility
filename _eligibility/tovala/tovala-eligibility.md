---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are only available in the 48 states that make up the continental United States.
  entity_types:
  - text: The Services are only offered and available to users who are of legal age and capacity to form a binding contract with Tovala
    type: individual
  minimum_age:
    text: You represent and warrant that you are of legal age in your state of residence
    value: null
  restricted_uses:
  - summary: Personal use only
    text: the Services are offered only for your use, and not for the use or benefit of any third party.
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
name: Tovala
provenance_date: '2026-11-10'
provider_name: Tovala
provider_slug: tovala
slug: tovala-eligibility
source_date: '2026-11-10'
source_filename: tovala-eligibility.yml
source_heading: Eligibility
source_page: https://my.tovala.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tovala\naid: tovala\nurl: https://my.tovala.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are only available in the 48 states that make up the continental United States.\nentity_types:\n- type: individual\n  text: The Services are only offered and available to users who are of legal age and capacity to form a binding\n    contract with Tovala\nrestricted_uses:\n- summary: Personal use only\n  text: the Services are offered only for your use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are of legal age in your state of residence\n"
source_yaml_url: https://artifacts.apis.io/tovala/eligibility/tovala-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tovala's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food
- Meal Delivery
- Smart Ovens
- Kitchen Appliances
- IoT
- Consumer
- Food Technology
---
