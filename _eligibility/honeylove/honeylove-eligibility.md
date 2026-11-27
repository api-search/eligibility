---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our Products or Services to any person, geographic region or jurisdiction.
  entity_types:
  - text: By agreeing to these Terms, you represent that you are at least the age of majority in your state or province of residence
    type: individual
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
name: Honeylove
provenance_date: '2026-11-09'
provider_name: Honeylove
provider_slug: honeylove
slug: honeylove-eligibility
source_date: '2026-11-09'
source_filename: honeylove-eligibility.yml
source_heading: Eligibility
source_page: https://www.honeylove.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Honeylove\naid: honeylove\nurl: https://www.honeylove.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our Products or Services to any person,\n    geographic region or jurisdiction.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms, you represent that you are at least the age of majority in your state or province\n    of residence\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n\
  \  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/honeylove/eligibility/honeylove-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Honeylove's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Shapewear
- Apparel
- E-Commerce
- Direct to Consumer
- Retail
- Intimates
- Shopify
---
