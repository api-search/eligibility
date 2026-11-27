---
api_specs:
- filename: appodeal-openapi-generated.yml
  format: yaml
  label: Appodeal API
  slug: appodeal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appodeal/openapi/_ae-authored/appodeal-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual user, in order to utilize and register for the Appodeal Services, you must be at least 18 years old.
    type: individual
  - text: You will not provide inaccurate, misleading or false information to Appodeal.
    type: business
  minimum_age:
    text: you must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Apps offering real monetary value to end users
    text: You are prohibited from using the Appodeal Services in an app that offers any real monetary value to the end users.
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
name: Appodeal
provenance_date: '2026-11-09'
provider_name: Appodeal
provider_slug: appodeal
slug: appodeal-eligibility
source_date: '2026-11-09'
source_filename: appodeal-eligibility.yml
source_heading: Eligibility
source_page: https://appodeal.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appodeal\naid: appodeal\nurl: https://appodeal.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual user, in order to utilize and register for the Appodeal Services, you must be at\n    least 18 years old.\n- type: business\n  text: You will not provide inaccurate, misleading or false information to Appodeal.\nrestricted_uses:\n- summary: Apps offering real monetary value to end users\n  text: You are prohibited from using the Appodeal Services in an app that offers any real monetary value\
  \ to the\n    end users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/appodeal/eligibility/appodeal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Appodeal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile
- Advertising
- Monetization
- SDK
- Analytics
---
