---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Service for use only by persons located in the United States.
  entity_types:
  - text: The Service is offered and available to users who are 18 years of age or older.
    type: individual
  - text: Our website and mobile applications allow companies to list apartments, houses or other real estate for rent or sale
    type: business
  minimum_age:
    text: The Service is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Service only for lawful purposes and in accordance with these Terms.
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
name: Apartment List
provenance_date: '2026-11-09'
provider_name: Apartment List
provider_slug: apartment-list
slug: apartment-list-eligibility
source_date: '2026-11-09'
source_filename: apartment-list-eligibility.yml
source_heading: Eligibility
source_page: https://www.apartmentlist.com/about/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apartment List\naid: apartment-list\nurl: https://www.apartmentlist.com/about/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Service for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: The Service is offered and available to users who are 18 years of age or older.\n- type: business\n  text: Our website and mobile applications allow companies to list apartments, houses or other real estate for\n    rent or sale\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Service only for lawful\
  \ purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/apartment-list/eligibility/apartment-list-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Apartment List's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Rentals
- Real Estate
- Housing
- Apartments
- Marketplace
- PropTech
- Consumer
---
