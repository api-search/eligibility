---
api_specs:
- filename: snapchat-conversion-events-api-openapi.yml
  format: yaml
  label: Snapchat Conversion Events API
  slug: snapchat-conversion-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snapchat/openapi/snapchat-conversion-events-api-openapi.yml
- filename: snapchat-user-profile-api-openapi.yml
  format: yaml
  label: Snapchat User Profile API
  slug: snapchat-user-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snapchat/openapi/snapchat-user-profile-api-openapi.yml
- filename: snapchat-oauth-api-openapi.yml
  format: yaml
  label: Snapchat O Auth API
  slug: snapchat-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snapchat/openapi/snapchat-oauth-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Terms apply if you live in the United States or if your principal place of business is in the United States.
  entity_types:
  - text: If you are using the Services on behalf of a business or some other entity, you represent that you are authorized to bind that business or entity to these Terms
    type: business
  - text: If you are using the Services on behalf of an entity of the U.S. Government, you agree to the Amendment to Snap Inc. Terms of Service for U.S. Government Users
    type: government
  minimum_age:
    text: Our Services are not directed to children under the age of 13
    value: '13'
  restricted_uses:
  - summary: Sanctioned or barred persons
    text: you are not a person who is barred from using the Services under the laws of the United States
  - summary: Unsafe use while driving or distracted
    text: So do not use our Services in a way that would distract you from obeying traffic or safety laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to verify your age before you are allowed to use our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Snapchat
provenance_date: '2026-11-10'
provider_name: Snapchat
provider_slug: snapchat
slug: snapchat-eligibility
source_date: '2026-11-10'
source_filename: snapchat-eligibility.yml
source_heading: Eligibility
source_page: https://www.snap.com/terms?lang=en-US
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snapchat\naid: snapchat\nurl: https://www.snap.com/terms?lang=en-US\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Terms apply if you live in the United States or if your principal place of business is in the United\n    States.\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a business or some other entity, you represent that you are authorized\n    to bind that business or entity to these Terms\n- type: government\n  text: If you are using the Services on behalf of an entity of the U.S. Government, you agree to\
  \ the Amendment\n    to Snap Inc. Terms of Service for U.S. Government Users\nrestricted_uses:\n- summary: Sanctioned or barred persons\n  text: you are not a person who is barred from using the Services under the laws of the United States\n- summary: Unsafe use while driving or distracted\n  text: So do not use our Services in a way that would distract you from obeying traffic or safety laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to verify your age before you are allowed to use our Services.\nminimum_age:\n  value: '13'\n  text: Our Services are not directed to children under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/snapchat/eligibility/snapchat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Snapchat's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Augmented Reality
- Marketing
- Messaging
- Social Media
---
