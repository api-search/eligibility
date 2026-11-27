---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Services is unauthorized in jurisdictions that do not give effect to this Agreement or where access to or use of the Services may be illegal or prohibited.
  minimum_age:
    text: are over the age of majority in your jurisdiction of residence and are not a convicted sex offender
    value: age of majority in jurisdiction of residence
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
name: StoryTap
provenance_date: '2026-11-10'
provider_name: StoryTap
provider_slug: storytap
slug: storytap-eligibility
source_date: '2026-11-10'
source_filename: storytap-eligibility.yml
source_heading: Eligibility
source_page: https://storytap.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StoryTap\naid: storytap\nurl: https://storytap.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Services is unauthorized in jurisdictions that do not give effect to this Agreement or where\n    access to or use of the Services may be illegal or prohibited.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in jurisdiction of residence\n  text: are over the age of majority in your jurisdiction of residence and are not a convicted sex offender\n"
source_yaml_url: https://artifacts.apis.io/storytap/eligibility/storytap-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from StoryTap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Testimonials
- User Generated Content
- Marketing
- Reviews
- Video Testimonials
- Software-as-a-Service
---
