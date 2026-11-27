---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older, reside in the United States or any of its territories and have not previously been suspended or removed
  entity_types:
  - text: You must be 18 years of age or older, reside in the United States or any of its territories
    type: individual
  minimum_age:
    text: You must be 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Commercial use requires signed agreement
    text: Use the Services for any commercial purpose, unless subject to a commercial agreement validly signed on behalf of Inhabitr
  - summary: Automated queries prohibited
    text: Conduct automated queries (including screen and database scraping, spiders, robots, crawlers, bypassing “captcha” or similar precautions, and any other automated activity with the purpose of obtaining information from the Services) on the Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be subject to a background check for verification of credit and/or ability to maintain consistent payments for our service each month.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Inhabitr
provenance_date: '2026-11-09'
provider_name: Inhabitr
provider_slug: inhabitr
slug: inhabitr-eligibility
source_date: '2026-11-09'
source_filename: inhabitr-eligibility.yml
source_heading: Eligibility
source_page: https://inhabitr.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inhabitr\naid: inhabitr\nurl: https://inhabitr.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older, reside in the United States or any of its territories and have not\n    previously been suspended or removed\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older, reside in the United States or any of its territories\nrestricted_uses:\n- summary: Commercial use requires signed agreement\n  text: Use the Services for any commercial purpose, unless subject to a commercial agreement validly signed\
  \ on\n    behalf of Inhabitr\n- summary: Automated queries prohibited\n  text: Conduct automated queries (including screen and database scraping, spiders, robots, crawlers, bypassing\n    “captcha” or similar precautions, and any other automated activity with the purpose of obtaining information\n    from the Services) on the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be subject to a background check for verification of credit and/or ability to maintain consistent\n    payments for our service each month.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/inhabitr/eligibility/inhabitr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Inhabitr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Furniture Rental
- Commercial Real Estate
- PropTech
- Hospitality
- Multifamily
- Interior Design
- Procurement
- E-Commerce
- Furnishing
---
