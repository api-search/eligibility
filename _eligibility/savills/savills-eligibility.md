---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'The services listed on this website are only available to persons in the United Kingdom for the following companies: SPF Private Clients Limited, Savills Capital Advisors Limited and Savills Investment Management Limited.'
  minimum_age:
    text: null
    value: null
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
name: Savills
provenance_date: '2026-11-10'
provider_name: Savills
provider_slug: savills
slug: savills-eligibility
source_date: '2026-11-10'
source_filename: savills-eligibility.yml
source_heading: Eligibility
source_page: https://www.savills.com/footer/terms-and-conditions.aspx
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Savills\naid: savills\nurl: https://www.savills.com/footer/terms-and-conditions.aspx\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'The services listed on this website are only available to persons in the United Kingdom for the following\n    companies: SPF Private Clients Limited, Savills Capital Advisors Limited and Savills Investment Management Limited.'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/savills/eligibility/savills-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Savills's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- United Kingdom
- Commercial Real Estate
- Property Listings
- Valuation
- Property Management
- Brokerage
- Rentals
- PropTech
- Investment Management
---
