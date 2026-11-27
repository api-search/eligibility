---
api_specs:
- filename: open-insurance-policy-api-openapi.yml
  format: yaml
  label: Open Policy API
  slug: open-insurance-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-insurance/openapi/open-insurance-policy-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The information on this website is provided for Australian residents only
  entity_types:
  - text: These Website Terms apply to all users of our website, including consumers
    type: individual
  - text: This website contains content intended for viewing and consumption only by commercial entities interested in understanding opportunities to embed insurance into commercial offerings.
    type: business
  minimum_age:
    text: You will not use Open if you are under 17.
    value: '17'
  restricted_uses:
  - summary: Commercial entities only
    text: This website contains content intended for viewing and consumption only by commercial entities interested in understanding opportunities to embed insurance into commercial offerings.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We will need to verify your identity before you can use certain parts of the Open Technology.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Open
provenance_date: '2026-11-10'
provider_name: Open
provider_slug: open-insurance
slug: open-insurance-eligibility
source_date: '2026-11-10'
source_filename: open-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://beopen.com/terms/australia
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Open\naid: open-insurance\nurl: https://beopen.com/terms/australia\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The information on this website is provided for Australian residents only\nentity_types:\n- type: individual\n  text: These Website Terms apply to all users of our website, including consumers\n- type: business\n  text: This website contains content intended for viewing and consumption only by commercial entities interested\n    in understanding opportunities to embed insurance into commercial offerings.\nrestricted_uses:\n- summary: Commercial entities only\n \
  \ text: This website contains content intended for viewing and consumption only by commercial entities interested\n    in understanding opportunities to embed insurance into commercial offerings.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We will need to verify your identity before you can use certain parts of the Open Technology.\nminimum_age:\n  value: '17'\n  text: You will not use Open if you are under 17.\n"
source_yaml_url: https://artifacts.apis.io/open-insurance/eligibility/open-insurance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Open's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Australia
- Insurtech
- Embedded Insurance
- Property and Casualty
- Travel Insurance
- Underwriting
- Policy Administration
- White Label
- Quotes
---
