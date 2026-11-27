---
api_specs:
- filename: google-marketing-platform-organizations-api-openapi.yml
  format: yaml
  label: Google Marketing Platform Admin Organizations API
  slug: google-marketing-platform-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-marketing-platform/openapi/google-marketing-platform-organizations-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are a business, you will defend and indemnify Google
    type: business
  - text: If you are accepting the Terms on behalf of a United States federal government entity
    type: government
  minimum_age:
    text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: HIPAA covered data
    text: If you are (or become) a "covered entity" or "business associate" as defined in HIPAA, you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
  - summary: ITAR-controlled data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: High-risk activities
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
name: Google Marketing Platform Admin
provenance_date: '2026-11-09'
provider_name: Google Marketing Platform Admin
provider_slug: google-marketing-platform
slug: google-marketing-platform-eligibility
source_date: '2026-11-09'
source_filename: google-marketing-platform-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Marketing Platform Admin\naid: google-marketing-platform\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are a business, you will defend and indemnify Google\n- type: government\n  text: If you are accepting the Terms on behalf of a United States federal government entity\nrestricted_uses:\n- summary: HIPAA covered data\n  text: If you are (or become) a \"covered entity\" or \"business associate\" as defined in HIPAA, you will not use\n    the APIs for any purpose or in any manner\
  \ involving transmitting protected health information to Google unless\n    you have received prior written consent to such use from Google.\n- summary: ITAR-controlled data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: High-risk activities\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding\n    contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-marketing-platform/eligibility/google-marketing-platform-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Google Marketing Platform Admin's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Google Marketing Platform
- Marketing
- Organization Management
- Platform Administration
---
