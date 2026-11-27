---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our UK website is solely for the promotion of our Products and services in the United Kingdom
  entity_types:
  - text: You must be purchasing as an individual for private use and not as a wholesaler or reseller.
    type: individual
  minimum_age:
    text: You must be at least 16 years old and reside in the UK to place an order through the Website for a Product or Membership.
    value: '16'
  restricted_uses:
  - summary: No commercial, business or resale use
    text: If you subscribe to our Memberships or use our Products for any commercial, business or re-sale purpose we will have no liability to you
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
name: Beauty Pie
provenance_date: '2026-11-09'
provider_name: Beauty Pie
provider_slug: beauty-pie
slug: beauty-pie-eligibility
source_date: '2026-11-09'
source_filename: beauty-pie-eligibility.yml
source_heading: Eligibility
source_page: https://www.beautypie.com/en-us/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beauty Pie\naid: beauty-pie\nurl: https://www.beautypie.com/en-us/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our UK website is solely for the promotion of our Products and services in the United Kingdom\nentity_types:\n- type: individual\n  text: You must be purchasing as an individual for private use and not as a wholesaler or reseller.\nrestricted_uses:\n- summary: No commercial, business or resale use\n  text: If you subscribe to our Memberships or use our Products for any commercial, business or re-sale purpose\n    we will\
  \ have no liability to you\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and reside in the UK to place an order through the Website for a Product\n    or Membership.\n"
source_yaml_url: https://artifacts.apis.io/beauty-pie/eligibility/beauty-pie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beauty Pie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Beauty
- Cosmetics
- Skincare
- Retail
- E-Commerce
- Shopify
- Agentic Commerce
---
