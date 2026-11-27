---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we make no representation that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: You must be at least 18 years of age to use the Services.
    type: individual
  - text: If you are a real estate or mortgage professional acting in your professional capacity, you may additionally use the Services to provide information, to the extent permitted by applicable law, to your clients and to take actions on behalf of your clients (“Pro Use”).
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: No commercial real estate transactions
    text: The Services may not be used for transactions in commercial real estate, which includes, without limitation, commercially zoned properties and vacation rentals.
  - summary: Personal transactions only unless commercial agreement
    text: Unless you have entered into a commercial agreement with us permitting you to use the Services for transactions on behalf of another person, you may use the Services only for transactions on your own behalf.
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
name: Zillow Group
provenance_date: '2026-11-10'
provider_name: Zillow Group
provider_slug: zillow-group
slug: zillow-group-eligibility
source_date: '2026-11-10'
source_filename: zillow-group-eligibility.yml
source_heading: Eligibility
source_page: https://www.zillow.com/corporate/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zillow Group\naid: zillow-group\nurl: https://www.zillow.com/corporate/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: we make no representation that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services.\n- type: business\n  text: If you are a real estate or mortgage professional acting in your professional capacity, you may additionally\n    use the Services to provide information, to the extent permitted by applicable law, to your clients and to take\n\
  \    actions on behalf of your clients (“Pro Use”).\nrestricted_uses:\n- summary: No commercial real estate transactions\n  text: The Services may not be used for transactions in commercial real estate, which includes, without limitation,\n    commercially zoned properties and vacation rentals.\n- summary: Personal transactions only unless commercial agreement\n  text: Unless you have entered into a commercial agreement with us permitting you to use the Services for transactions\n    on behalf of another person, you may use the Services only for transactions on your own behalf.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/zillow-group/eligibility/zillow-group-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Zillow Group's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Property Data
- MLS
- Mortgage
- Rentals
- Valuation
- Housing Data
- Transaction Management
- Listings
- RESO
- IDX
---
