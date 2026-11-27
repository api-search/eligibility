---
api_specs:
- filename: kvcore-openapi-generated.yml
  format: yaml
  label: Inside Real Estate (kvCORE / BoldTrail) API
  slug: kvcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kvcore/openapi/_ae-authored/kvcore-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Subscription is intended for Users located within the United States and Canada.
  entity_types:
  - text: If Customer is a company or another legal entity, the individual signing or User accessing on behalf of the Customer represents that he or she has the authority to bind Customer
    type: business
  minimum_age:
    text: you are at least 18 years of age (or have reached the age of majority in the jurisdiction where you reside)
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
name: Inside Real Estate (kvCORE / BoldTrail)
provenance_date: '2026-11-09'
provider_name: Inside Real Estate (kvCORE / BoldTrail)
provider_slug: kvcore
slug: kvcore-eligibility
source_date: '2026-11-09'
source_filename: kvcore-eligibility.yml
source_heading: Eligibility
source_page: https://insiderealestate.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inside Real Estate (kvCORE / BoldTrail)\naid: kvcore\nurl: https://insiderealestate.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Subscription is intended for Users located within the United States and Canada.\nentity_types:\n- type: business\n  text: If Customer is a company or another legal entity, the individual signing or User accessing on behalf of\n    the Customer represents that he or she has the authority to bind Customer\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: you are at least 18 years of age (or have reached the age of majority in the jurisdiction where you reside)\n"
source_yaml_url: https://artifacts.apis.io/kvcore/eligibility/kvcore-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Inside Real Estate (kvCORE / BoldTrail)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Software-as-a-Service
- CRM
- Lead Generation
- Marketing Automation
---
