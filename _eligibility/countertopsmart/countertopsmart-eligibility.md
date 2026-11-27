---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Service is void where prohibited.
  entity_types:
  - text: Buyers may include (without limitation) individual consumers, designers or contractors.
    type: individual
  - text: Buyers may include (without limitation) individual consumers, designers or contractors.
    type: business
  minimum_age:
    text: In order to qualify as a Buyer, you must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Intended use only
    text: You may not use the Service for any use other than its intended use.
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
name: CountertopSmart
provenance_date: '2026-11-09'
provider_name: CountertopSmart
provider_slug: countertopsmart
slug: countertopsmart-eligibility
source_date: '2026-11-09'
source_filename: countertopsmart-eligibility.yml
source_heading: Eligibility
source_page: https://www.countertopsmart.com/home/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CountertopSmart\naid: countertopsmart\nurl: https://www.countertopsmart.com/home/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Service is void where prohibited.\nentity_types:\n- type: individual\n  text: Buyers may include (without limitation) individual consumers, designers or contractors.\n- type: business\n  text: Buyers may include (without limitation) individual consumers, designers or contractors.\nrestricted_uses:\n- summary: Intended use only\n  text: You may not use the Service for any use other than its intended use.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to qualify as a Buyer, you must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/countertopsmart/eligibility/countertopsmart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CountertopSmart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Home Improvement
- Marketplace
- Countertops
---
