---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Be a permanent resident of the United States.
  entity_types:
  - text: Be 18 years or older.
    type: individual
  - text: you have obtained all business licenses, permits, and fulfilled any other necessary requirements to legally provide pet care services.
    type: business
  minimum_age:
    text: Be 18 years or older.
    value: '18'
  restricted_uses:
  - summary: No use by children under 13
    text: Children under the age of 13 are not permitted to use our Services.
  - summary: No services for venomous or dangerous pets
    text: You may not seek services for venomous pets or pets that pose a potential threat to another person or pet.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: although we may attempt to verify the information of users of the Services, we do not screen users of our Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Petstore.com
provenance_date: '2026-11-10'
provider_name: Petstore.com
provider_slug: petstorecom
slug: petstorecom-eligibility
source_date: '2026-11-10'
source_filename: petstorecom-eligibility.yml
source_heading: Eligibility
source_page: https://petstore.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Petstore.com\naid: petstorecom\nurl: https://petstore.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Be a permanent resident of the United States.\nentity_types:\n- type: individual\n  text: Be 18 years or older.\n- type: business\n  text: you have obtained all business licenses, permits, and fulfilled any other necessary requirements to legally\n    provide pet care services.\nrestricted_uses:\n- summary: No use by children under 13\n  text: Children under the age of 13 are not permitted to use our Services.\n- summary: No services for venomous\
  \ or dangerous pets\n  text: You may not seek services for venomous pets or pets that pose a potential threat to another person or pet.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: although we may attempt to verify the information of users of the Services, we do not screen users of our\n    Services\nminimum_age:\n  value: '18'\n  text: Be 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/petstorecom/eligibility/petstorecom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Petstore.com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Retail
- Pet Supplies
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
---
