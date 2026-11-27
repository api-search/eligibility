---
api_specs:
- filename: google-people-people-api-openapi.yml
  format: yaml
  label: Google People API
  slug: google-people-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-people/openapi/google-people-people-api-openapi.yml
- filename: google-people-othercontacts-api-openapi.yml
  format: yaml
  label: Google People Other Contacts API
  slug: google-people-othercontacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-people/openapi/google-people-othercontacts-api-openapi.yml
- filename: google-people-contact-groups-api-openapi.yml
  format: yaml
  label: Google People Contact Groups API
  slug: google-people-contact-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-people/openapi/google-people-contact-groups-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding contract with Google, or (b) you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: Life-critical or safety uses
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
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
name: Google People
provenance_date: '2026-11-09'
provider_name: Google People
provider_slug: google-people
slug: google-people-eligibility
source_date: '2026-11-09'
source_filename: google-people-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google People\naid: google-people\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding\n    contract with Google, or (b) you are a person barred from using or receiving the APIs under the applicable laws\n    of the United States or other countries including the country in which you are resident or from which you use\n    the APIs.\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant\
  \ that you have authority to bind\n    that entity to the Terms\nrestricted_uses:\n- summary: Life-critical or safety uses\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-people/eligibility/google-people-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Google People's own page on 2026-11-09.
synthetic: false
tags:
- Address Book
- Contacts
- Google
- People
- Profiles
---
