---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: provide a valid shipping address within the continental United States
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Personal or internal business use only
    text: may only be exercised by you for your personal, non-commercial use or internal business purposes
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
name: Cratejoy
provenance_date: '2026-11-09'
provider_name: Cratejoy
provider_slug: cratejoy
slug: cratejoy-eligibility
source_date: '2026-11-09'
source_filename: cratejoy-eligibility.yml
source_heading: Eligibility
source_page: https://www.cratejoy.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cratejoy\naid: cratejoy\nurl: https://www.cratejoy.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: provide a valid shipping address within the continental United States\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\nrestricted_uses:\n- summary: Personal or internal business use only\n  text: may only be exercised by you for your personal, non-commercial use or internal business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/cratejoy/eligibility/cratejoy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cratejoy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Subscription
- Subscription Boxes
- Marketplace
- Payments
- Order
- Webhook
- REST
---
