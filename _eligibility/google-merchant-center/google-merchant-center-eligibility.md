---
api_specs:
- filename: google-merchant-center-accounts-api-openapi.yml
  format: yaml
  label: Google Merchant Center Accounts API
  slug: google-merchant-center-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-merchant-center/openapi/google-merchant-center-accounts-api-openapi.yml
- filename: google-merchant-center-issueresolution-api-openapi.yml
  format: yaml
  label: Google Merchant Center Issueresolution API
  slug: google-merchant-center-issueresolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-merchant-center/openapi/google-merchant-center-issueresolution-api-openapi.yml
- filename: google-merchant-center-termsofservice-api-openapi.yml
  format: yaml
  label: Google Merchant Center Terms Of Service API
  slug: google-merchant-center-termsofservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-merchant-center/openapi/google-merchant-center-termsofservice-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs ... if you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: ITAR-controlled data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations
  - summary: HIPAA protected health information
    text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
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
name: Google Merchant Center
provenance_date: '2026-11-09'
provider_name: Google Merchant Center
provider_slug: google-merchant-center
slug: google-merchant-center-eligibility
source_date: '2026-11-09'
source_filename: google-merchant-center-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Merchant Center\naid: google-merchant-center\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs ... if you are a person barred from using or receiving the APIs under the applicable\n    laws of the United States or other countries including the country in which you are resident\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\nrestricted_uses:\n- summary: High-risk activities\n  text:\
  \ Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: ITAR-controlled data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n- summary: HIPAA protected health information\n  text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information\n    to Google unless you have received prior written consent to such use from Google.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-merchant-center/eligibility/google-merchant-center-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Google Merchant Center's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Google Shopping
- Inventory
- Merchant Center
- Product
- Promotions
- Shopping
---
