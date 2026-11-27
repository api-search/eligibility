---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that you are of legal age to enter into this Agreement and to use the Services and Software.
    type: individual
  - text: For enterprise customers and developers, EasyWebinar offers an API
    type: developer
  minimum_age:
    text: Easywebinar is not intended for use by individuals under the age of sixteen (16) years old, unless it is through a School Subscriber using Easy Webinar for Education.
    value: '16'
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
name: EasyWebinar
provenance_date: '2026-11-09'
provider_name: EasyWebinar
provider_slug: easywebinar
slug: easywebinar-eligibility
source_date: '2026-11-09'
source_filename: easywebinar-eligibility.yml
source_heading: Eligibility
source_page: https://easywebinar.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EasyWebinar\naid: easywebinar\nurl: https://easywebinar.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that you are of legal age to enter into this Agreement and to use the Services and Software.\n- type: developer\n  text: For enterprise customers and developers, EasyWebinar offers an API\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Easywebinar is not intended for use by individuals under the age of sixteen\
  \ (16) years old, unless it is\n    through a School Subscriber using Easy Webinar for Education.\n"
source_yaml_url: https://artifacts.apis.io/easywebinar/eligibility/easywebinar-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from EasyWebinar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Webinars
- Video
- Live Streaming
- Marketing
- Event
- CRM
- Lead Generation
- Automation
- Identity
- OAuth
- Software-as-a-Service
- Identity Federation
- Authentication
---
