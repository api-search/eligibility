---
api_specs:
- filename: google-chrome-challenge-api-openapi.yml
  format: yaml
  label: Google Chrome Challenge API
  slug: google-chrome-challenge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chrome/openapi/google-chrome-challenge-api-openapi.yml
- filename: google-chrome-customers-api-openapi.yml
  format: yaml
  label: Google Chrome Customers API
  slug: google-chrome-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chrome/openapi/google-chrome-customers-api-openapi.yml
- filename: google-chrome-media-api-openapi.yml
  format: yaml
  label: Google Chrome Media API
  slug: google-chrome-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chrome/openapi/google-chrome-media-api-openapi.yml
- filename: google-chrome-operations-api-openapi.yml
  format: yaml
  label: Google Chrome Operations API
  slug: google-chrome-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chrome/openapi/google-chrome-operations-api-openapi.yml
- filename: google-chrome-platforms-api-openapi.yml
  format: yaml
  label: Google Chrome Platforms API
  slug: google-chrome-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chrome/openapi/google-chrome-platforms-api-openapi.yml
- filename: google-chrome-publishers-api-openapi.yml
  format: yaml
  label: Google Chrome Publishers API
  slug: google-chrome-publishers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chrome/openapi/google-chrome-publishers-api-openapi.yml
- filename: google-chrome-records-api-openapi.yml
  format: yaml
  label: Google Chrome Records API
  slug: google-chrome-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chrome/openapi/google-chrome-records-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  - text: If you are accepting the Terms on behalf of a United States federal government entity, then the following applies instead of the paragraph above
    type: government
  minimum_age:
    text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding contract with Google
    value: legal age to form a binding contract
  restricted_uses:
  - summary: Life-critical activities
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: Protected health information
    text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access certain APIs you may be required to provide certain information (such as identification or contact details) as part of the registration process for the APIs
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Chrome
provenance_date: '2026-11-09'
provider_name: Google Chrome
provider_slug: google-chrome
slug: google-chrome-eligibility
source_date: '2026-11-09'
source_filename: google-chrome-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Chrome\naid: google-chrome\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\n- type: government\n  text: If you are accepting the Terms on behalf of a United States federal government entity, then the following\n    applies instead of the paragraph above\nrestricted_uses:\n- summary: Life-critical activities\n  text: Use the APIs for any activities where\
  \ the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: Protected health information\n  text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information\n    to Google unless you have received prior written consent to such use from Google.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access certain APIs you may be required to provide certain information (such as identification\n    or contact details) as part of the registration process for the APIs\nminimum_age:\n  value: legal age to form a binding contract\n  text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding\n    contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-chrome/eligibility/google-chrome-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Google Chrome's own page on 2026-11-09.
synthetic: false
tags:
- Browser
- Chrome Extensions
- Developer Tools
- Web Platform
---
