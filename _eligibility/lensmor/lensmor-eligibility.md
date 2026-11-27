---
api_specs:
- filename: lensmor-actions-api-openapi.yml
  format: yaml
  label: Lensmor Actions API
  slug: lensmor-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-actions-api-openapi.yml
- filename: lensmor-contacts-api-openapi.yml
  format: yaml
  label: Lensmor Contacts API
  slug: lensmor-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-contacts-api-openapi.yml
- filename: lensmor-credits-api-openapi.yml
  format: yaml
  label: Lensmor Credits API
  slug: lensmor-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-credits-api-openapi.yml
- filename: lensmor-events-api-openapi.yml
  format: yaml
  label: Lensmor Events API
  slug: lensmor-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-events-api-openapi.yml
- filename: lensmor-exhibitors-api-openapi.yml
  format: yaml
  label: Lensmor Exhibitors API
  slug: lensmor-exhibitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-exhibitors-api-openapi.yml
- filename: lensmor-personnel-api-openapi.yml
  format: yaml
  label: Lensmor Personnel API
  slug: lensmor-personnel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-personnel-api-openapi.yml
- filename: lensmor-profile-matching-api-openapi.yml
  format: yaml
  label: Lensmor Profile Matching API
  slug: lensmor-profile-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-profile-matching-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By registering for an account or using the Services, you confirm that you are acting in a professional capacity for business purposes (B2B)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam and unsolicited email
    text: Use retrieved email addresses to send unsolicited spam in violation of CAN-SPAM, GDPR, or other anti-spam laws.
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
name: Lensmor
provenance_date: '2026-11-09'
provider_name: Lensmor
provider_slug: lensmor
slug: lensmor-eligibility
source_date: '2026-11-09'
source_filename: lensmor-eligibility.yml
source_heading: Eligibility
source_page: https://www.lensmor.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lensmor\naid: lensmor\nurl: https://www.lensmor.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By registering for an account or using the Services, you confirm that you are acting in a professional capacity\n    for business purposes (B2B)\nrestricted_uses:\n- summary: Spam and unsolicited email\n  text: Use retrieved email addresses to send unsolicited spam in violation of CAN-SPAM, GDPR, or other anti-spam\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lensmor/eligibility/lensmor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Lensmor's own page on 2026-11-09.
synthetic: false
tags:
- Event Intelligence
- B2B
- Software-as-a-Service
- Lead Generation
- Trade Shows
---
