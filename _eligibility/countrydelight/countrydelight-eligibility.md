---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The Products and Services on the Platform are available to only select geographies in India
  entity_types:
  - text: shall mean the person or any legal entity who accept the offer for sale on the Platform
    type: business
  minimum_age:
    text: The Platform is not available to persons under the age of 18 (eighteen) years.
    value: '18'
  restricted_uses:
  - summary: Personal consumption only
    text: any purchase made through the Company’s application or any other mode authorised by the Company is strictly for personal consumption and not for any commercial purpose.
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
name: Country Delight
provenance_date: '2026-11-09'
provider_name: Country Delight
provider_slug: countrydelight
slug: countrydelight-eligibility
source_date: '2026-11-09'
source_filename: countrydelight-eligibility.yml
source_heading: Eligibility
source_page: https://countrydelight.in/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Country Delight\naid: countrydelight\nurl: https://countrydelight.in/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The Products and Services on the Platform are available to only select geographies in India\nentity_types:\n- type: business\n  text: shall mean the person or any legal entity who accept the offer for sale on the Platform\nrestricted_uses:\n- summary: Personal consumption only\n  text: any purchase made through the Company’s application or any other mode authorised by the Company is strictly\n    for personal consumption and not for any commercial\
  \ purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Platform is not available to persons under the age of 18 (eighteen) years.\n"
source_yaml_url: https://artifacts.apis.io/countrydelight/eligibility/countrydelight-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Country Delight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Grocery Delivery
- Dairy
- Milk
- Direct to Consumer
- Consumer
- Food and Beverage
- Subscription
- India
- Consumer Goods
---
