---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - SE
    - GB
    text: FOR USERS IN SWEDEN ... FOR USERS IN THE UK
  entity_types:
  - text: Only natural persons can register as a user of the Service via the App.
    type: individual
  - text: For legal persons who wish to use the Service as a Helper, special conditions apply and registration can be made at Tiptapp’s website.
    type: business
  minimum_age:
    text: you must be at least 18 years old, or of the age when you, under applicable law, have legal capacity
    value: '18'
  restricted_uses:
  - summary: Prohibited advertising categories
    text: It is not allowed to advertise animals in the Service.
  - summary: Tobacco or alcohol
    text: It is not allowed to advertise tobacco or alcohol in the Service.
  - summary: Professional helper activity
    text: It is not allowed to use the Service to professionally perform assignments as a Helper.
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
name: Tiptapp
provenance_date: '2026-11-10'
provider_name: Tiptapp
provider_slug: tiptapp
slug: tiptapp-eligibility
source_date: '2026-11-10'
source_filename: tiptapp-eligibility.yml
source_heading: Eligibility
source_page: https://tiptapp.com/en-gb/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tiptapp\naid: tiptapp\nurl: https://tiptapp.com/en-gb/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SE\n  - GB\n  excluded: []\n  text: FOR USERS IN SWEDEN ... FOR USERS IN THE UK\nentity_types:\n- type: individual\n  text: Only natural persons can register as a user of the Service via the App.\n- type: business\n  text: For legal persons who wish to use the Service as a Helper, special conditions apply and registration can\n    be made at Tiptapp’s website.\nrestricted_uses:\n- summary: Prohibited advertising categories\n  text: It is not allowed to advertise animals in the Service.\n\
  - summary: Tobacco or alcohol\n  text: It is not allowed to advertise tobacco or alcohol in the Service.\n- summary: Professional helper activity\n  text: It is not allowed to use the Service to professionally perform assignments as a Helper.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old, or of the age when you, under applicable law, have legal capacity\n"
source_yaml_url: https://artifacts.apis.io/tiptapp/eligibility/tiptapp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Tiptapp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Moving
- Delivery
- Recycling
- Sustainability
---
