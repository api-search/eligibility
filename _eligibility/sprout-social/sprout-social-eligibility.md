---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: are not located in, under the control of, or a national or resident of any a prohibited country under applicable export or import restrictions, laws, or regulations
  entity_types:
  - text: The APIs and API Documentation are intended for use by businesses and organizations
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer purposes prohibited
    text: use for consumer purposes is strictly prohibited
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must obtain an API Key through the registration process to use and access the APIs.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sprout Social
provenance_date: '2026-11-10'
provider_name: Sprout Social
provider_slug: sprout-social
slug: sprout-social-eligibility
source_date: '2026-11-10'
source_filename: sprout-social-eligibility.yml
source_heading: Eligibility
source_page: https://sproutsocial.com/legal/api-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sprout Social\naid: sprout-social\nurl: https://sproutsocial.com/legal/api-terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: are not located in, under the control of, or a national or resident of any a prohibited country under applicable\n    export or import restrictions, laws, or regulations\nentity_types:\n- type: business\n  text: The APIs and API Documentation are intended for use by businesses and organizations\nrestricted_uses:\n- summary: Consumer purposes prohibited\n  text: use for consumer purposes is strictly prohibited\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: You must obtain an API Key through the registration process to use and access the APIs.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sprout-social/eligibility/sprout-social-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Sprout Social's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Social Media Management
- Publishing
- Analytics
- Reporting
- Messaging
- Social Listening
---
