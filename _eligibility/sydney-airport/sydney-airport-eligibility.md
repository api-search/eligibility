---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 18 years of age, you must only accept these Terms of Use with the approval of a parent or guardian.
    value: '18'
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
name: Sydney Airport
provenance_date: '2026-11-10'
provider_name: Sydney Airport
provider_slug: sydney-airport
slug: sydney-airport-eligibility
source_date: '2026-11-10'
source_filename: sydney-airport-eligibility.yml
source_heading: Eligibility
source_page: https://www.sydneyairport.com.au/info-sheet/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sydney Airport\naid: sydney-airport\nurl: https://www.sydneyairport.com.au/info-sheet/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you must only accept these Terms of Use with the approval of a parent\n    or guardian.\n"
source_yaml_url: https://artifacts.apis.io/sydney-airport/eligibility/sydney-airport-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Sydney Airport's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Australia
- Airports
- Aviation
- Airport Infrastructure
- Transportation
- Flight Information
- Passenger Experience
---
