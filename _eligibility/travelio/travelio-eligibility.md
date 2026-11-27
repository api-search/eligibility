---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Saya telah berusia 18 tahun ke atas dan menyetujui Kebijakan Privasi yang berlaku
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
name: Travelio
provenance_date: '2026-11-10'
provider_name: Travelio
provider_slug: travelio
slug: travelio-eligibility
source_date: '2026-11-10'
source_filename: travelio-eligibility.yml
source_heading: Eligibility
source_page: https://www.travelio.com/termsandcondition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Travelio\naid: travelio\nurl: https://www.travelio.com/termsandcondition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Saya telah berusia 18 tahun ke atas dan menyetujui Kebijakan Privasi yang berlaku\n"
source_yaml_url: https://artifacts.apis.io/travelio/eligibility/travelio-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Travelio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Property Rental
- Real Estate
- Property Management
- Hospitality
- Travel
- Indonesia
- Apartments
---
