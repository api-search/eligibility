---
api_specs:
- filename: usebutton-accounts-api-openapi.yml
  format: yaml
  label: Button Accounts API
  slug: usebutton-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usebutton/openapi/usebutton-accounts-api-openapi.yml
- filename: usebutton-brands-api-api-openapi.yml
  format: yaml
  label: Button Brands Api
  slug: usebutton-brands-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usebutton/openapi/usebutton-brands-api-api-openapi.yml
- filename: usebutton-create-api-openapi.yml
  format: yaml
  label: Button Create API
  slug: usebutton-create-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usebutton/openapi/usebutton-create-api-openapi.yml
- filename: usebutton-links-api-api-openapi.yml
  format: yaml
  label: Button Links Api
  slug: usebutton-links-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usebutton/openapi/usebutton-links-api-api-openapi.yml
- filename: usebutton-offers-api-openapi.yml
  format: yaml
  label: Button Offers API
  slug: usebutton-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usebutton/openapi/usebutton-offers-api-openapi.yml
- filename: usebutton-transactions-api-openapi.yml
  format: yaml
  label: Button Transactions API
  slug: usebutton-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usebutton/openapi/usebutton-transactions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not accept these Terms, and therefore may not use the Button Technology, if you are barred from doing so under the laws of the United States and/or any other country, including the country in which you are resident or from which you use the Button Technology.
  entity_types:
  - text: You represent that you are at least 18 years of age.
    type: individual
  - text: If you are using the Technology on behalf of an employer or other business entity, then the term “you” also refers to that employer or business entity.
    type: business
  minimum_age:
    text: You represent that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: OFAC sanctions certification
    text: You hereby certify that you, or anyone you facilitate, direct, or assist in using the Button Technology and/or the Services, are not currently identified on the Specially Designated Nationals and Blocked Persons List
  - summary: Minors
    text: Individuals under the age of 18 (“Minors”) are not permitted to use the Services without the supervision of a parent or legal guardian.
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
name: Button
provenance_date: '2026-11-10'
provider_name: Button
provider_slug: usebutton
slug: usebutton-eligibility
source_date: '2026-11-10'
source_filename: usebutton-eligibility.yml
source_heading: Eligibility
source_page: https://www.usebutton.com/support/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Button\naid: usebutton\nurl: https://www.usebutton.com/support/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not accept these Terms, and therefore may not use the Button Technology, if you are barred from\n    doing so under the laws of the United States and/or any other country, including the country in which you are\n    resident or from which you use the Button Technology.\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years of age.\n- type: business\n  text: If you are using the Technology on behalf of an employer\
  \ or other business entity, then the term “you” also\n    refers to that employer or business entity.\nrestricted_uses:\n- summary: OFAC sanctions certification\n  text: You hereby certify that you, or anyone you facilitate, direct, or assist in using the Button Technology\n    and/or the Services, are not currently identified on the Specially Designated Nationals and Blocked Persons\n    List\n- summary: Minors\n  text: Individuals under the age of 18 (“Minors”) are not permitted to use the Services without the supervision\n    of a parent or legal guardian.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/usebutton/eligibility/usebutton-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Button's own page on 2026-11-10.
synthetic: false
tags:
- Commerce
- Mobile Commerce
- Affiliates
- Attribution
- Deep Linking
- Offers
- Publishers
- Retail
---
