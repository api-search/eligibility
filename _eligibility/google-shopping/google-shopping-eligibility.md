---
api_specs:
- filename: google-shopping-accounts-api-openapi.yml
  format: yaml
  label: Google Content API for Shopping Accounts API
  slug: google-shopping-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-shopping/openapi/google-shopping-accounts-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs if you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: HIPAA covered data
    text: If you are (or become) a "covered entity" or "business associate" as defined in HIPAA, you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
  - summary: ITAR data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: Life-critical uses
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be required to provide certain information (such as identification or contact details) as part of the registration process for the APIs
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Content API for Shopping
provenance_date: '2026-11-09'
provider_name: Google Content API for Shopping
provider_slug: google-shopping
slug: google-shopping-eligibility
source_date: '2026-11-09'
source_filename: google-shopping-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Content API for Shopping\naid: google-shopping\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs if you are a person barred from using or receiving the APIs under the applicable\n    laws of the United States or other countries including the country in which you are resident or from which you\n    use the APIs.\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\nrestricted_uses:\n-\
  \ summary: HIPAA covered data\n  text: If you are (or become) a \"covered entity\" or \"business associate\" as defined in HIPAA, you will not use\n    the APIs for any purpose or in any manner involving transmitting protected health information to Google unless\n    you have received prior written consent to such use from Google.\n- summary: ITAR data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: Life-critical uses\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be required to provide certain information (such as identification or contact details) as part of\n    the registration process for the APIs\nminimum_age:\n  value: null\n  text: You may not use the APIs and may not accept\
  \ the Terms if (a) you are not of legal age to form a binding\n    contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-shopping/eligibility/google-shopping-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Google Content API for Shopping's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Google Shopping
- Merchant Center
- Product Listings
- Retail
- Shopping
---
