---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region or jurisdiction.
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: No commercial resale or export
    text: You represent and warrant that your purchases are for your own personal or household use and not for commercial resale or export.
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
name: 1Balance
provenance_date: '2026-11-09'
provider_name: 1Balance
provider_slug: 1balance
slug: 1balance-eligibility
source_date: '2026-11-09'
source_filename: 1balance-eligibility.yml
source_heading: Eligibility
source_page: https://1balance.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1Balance\naid: 1balance\nurl: https://1balance.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region or jurisdiction.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: No commercial resale or export\n  text: You represent and warrant that your purchases\
  \ are for your own personal or household use and not for commercial\n    resale or export.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/1balance/eligibility/1balance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 1Balance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Wellness
- Herbal Tea
- Nutrition
- Supplements
- E-Commerce
- Direct to Consumer
- Subscription
---
