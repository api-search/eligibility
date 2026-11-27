---
api_specs:
- filename: wahi-search-api-openapi.yml
  format: yaml
  label: Wahi Search API
  slug: wahi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahi/openapi/wahi-search-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: The Service is available for individuals aged 18 years or older located in Canada.
  entity_types:
  - text: The Service is available for individuals aged 18 years or older located in Canada.
    type: individual
  - text: If you are using the Service on behalf of an organization, then you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: The Service is available for individuals aged 18 years or older located in Canada.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: You will not use the Site for any unlawful purpose;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Wahi may accept or reject any registration in our sole and exclusive discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wahi
provenance_date: '2026-11-10'
provider_name: Wahi
provider_slug: wahi
slug: wahi-eligibility
source_date: '2026-11-10'
source_filename: wahi-eligibility.yml
source_heading: Eligibility
source_page: https://wahi.com/ca/en/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wahi\naid: wahi\nurl: https://wahi.com/ca/en/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: The Service is available for individuals aged 18 years or older located in Canada.\nentity_types:\n- type: individual\n  text: The Service is available for individuals aged 18 years or older located in Canada.\n- type: business\n  text: If you are using the Service on behalf of an organization, then you are agreeing to these Terms for that\n    organization\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You will not use the Site for any unlawful purpose;\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: Wahi may accept or reject any registration in our sole and exclusive discretion.\nminimum_age:\n  value: '18'\n  text: The Service is available for individuals aged 18 years or older located in Canada.\n"
source_yaml_url: https://artifacts.apis.io/wahi/eligibility/wahi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Wahi's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Canada
- Property Listings
- MLS
- Valuation
- AVM
- PropTech
- Rentals
- Brokerage
---
