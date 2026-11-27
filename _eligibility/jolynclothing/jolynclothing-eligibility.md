---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  - text: Membership is only available to (i) individuals above the age of majority and who have legal capacity, and (ii) corporations, businesses, charities, partnerships, enterprises, schools or anyone other than an individual
    type: business
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
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
name: JOLYN
provenance_date: '2026-11-09'
provider_name: JOLYN
provider_slug: jolynclothing
slug: jolynclothing-eligibility
source_date: '2026-11-09'
source_filename: jolynclothing-eligibility.yml
source_heading: Eligibility
source_page: https://jolyn.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JOLYN\naid: jolynclothing\nurl: https://jolyn.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\n- type: business\n  text: Membership is only available to (i) individuals above the age of majority and who have legal capacity, and\n    (ii) corporations, businesses, charities, partnerships, enterprises, schools or anyone other than an individual\nrestricted_uses: []\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/jolynclothing/eligibility/jolynclothing-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from JOLYN's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Apparel
- Swimwear
- Direct to Consumer
- Shopify
- Agentic Commerce
---
