---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: for lawful and proper purposes which includes complying with all applicable laws, regulations and codes of practice
  - summary: Fraudulent applications
    text: submit any unauthorised, false or fraudulent applications;
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
name: Heathrow Airport
provenance_date: '2026-11-09'
provider_name: Heathrow Airport
provider_slug: heathrow-airport
slug: heathrow-airport-eligibility
source_date: '2026-11-09'
source_filename: heathrow-airport-eligibility.yml
source_heading: Eligibility
source_page: https://www.heathrow.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Heathrow Airport\naid: heathrow-airport\nurl: https://www.heathrow.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: for lawful and proper purposes which includes complying with all applicable laws, regulations and codes\n    of practice\n- summary: Fraudulent applications\n  text: submit any unauthorised, false or fraudulent applications;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/heathrow-airport/eligibility/heathrow-airport-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Heathrow Airport's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- United Kingdom
- Airports
- Aviation
- Airport Infrastructure
- Flight Information
- Transportation
- Passenger Experience
---
