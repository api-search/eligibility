---
api_specs:
- filename: google-gmail-domains-api-openapi.yml
  format: yaml
  label: Google Gmail Domains API
  slug: google-gmail-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gmail/openapi/google-gmail-domains-api-openapi.yml
- filename: google-gmail-domainstats-api-openapi.yml
  format: yaml
  label: Google Gmail Domain Stats API
  slug: google-gmail-domainstats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gmail/openapi/google-gmail-domainstats-api-openapi.yml
- filename: google-gmail-users-api-openapi.yml
  format: yaml
  label: Google Gmail Users API
  slug: google-gmail-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gmail/openapi/google-gmail-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: No ITAR-controlled data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: No high-risk uses
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: No protected health information without consent
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
name: Google Gmail
provenance_date: '2026-11-09'
provider_name: Google Gmail
provider_slug: google-gmail
slug: google-gmail-eligibility
source_date: '2026-11-09'
source_filename: google-gmail-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Gmail\naid: google-gmail\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\nrestricted_uses:\n- summary: No ITAR-controlled data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: No high-risk uses\n  text: Use the APIs for any\
  \ activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: No protected health information without consent\n  text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information\n    to Google unless you have received prior written consent to such use from Google.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-gmail/eligibility/google-gmail-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Google Gmail's own page on 2026-11-09.
synthetic: false
tags:
- Drafts
- Email
- Gmail
- Google
- Google Workspace
- Labels
- Messaging
- Threads
---
