---
api_specs:
- filename: secfeedapi-com-api-openapi.json
  format: json
  label: SecFeed API API
  slug: secfeed-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secfeedapi-com/openapi/_original/secfeedapi-com-api-openapi.json
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in, or are a national or resident of, a country or region subject to comprehensive U.S. sanctions, or if you appear on any U.S. government restricted party list.
  entity_types:
  - text: The Service is intended for business and professional use.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Fair Credit Reporting Act purposes
    text: or for any purpose regulated by the U.S. Fair Credit Reporting Act (such as eligibility for credit, insurance, employment or housing)
  - summary: Harassment or unlawful profiling of individuals
    text: use data about individuals obtained through the Service to harass, stalk, discriminate against, defame or unlawfully profile any person
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we use the card to verify identity and prevent abuse.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: secfeedapi-com
provenance_date: '2026-11-10'
provider_name: secfeedapi-com
provider_slug: secfeedapi-com
slug: secfeedapi-com-eligibility
source_date: '2026-11-10'
source_filename: secfeedapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://secfeedapi.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: secfeedapi-com\naid: secfeedapi-com\nurl: https://secfeedapi.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in, or are a national or resident of, a country or region\n    subject to comprehensive U.S. sanctions, or if you appear on any U.S. government restricted party list.\nentity_types:\n- type: business\n  text: The Service is intended for business and professional use.\nrestricted_uses:\n- summary: Fair Credit Reporting Act purposes\n  text: or for any purpose regulated by the U.S. Fair Credit Reporting Act (such as eligibility\
  \ for credit, insurance,\n    employment or housing)\n- summary: Harassment or unlawful profiling of individuals\n  text: use data about individuals obtained through the Service to harass, stalk, discriminate against, defame or\n    unlawfully profile any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we use the card to verify identity and prevent abuse.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/secfeedapi-com/eligibility/secfeedapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from secfeedapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SEC
- EDGAR
- Data
- Finance
---
