---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old, or the age of legal capacity in your jurisdiction, to use the Services.
    value: '16'
  restricted_uses:
  - summary: Unsolicited messaging
    text: AddCal strictly prohibits the use of unsolicited messages (such as spam) to advertise, promote, or share links to our website, Services, or any user-generated content.
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
name: AddCal
provenance_date: '2026-11-09'
provider_name: AddCal
provider_slug: addcal-co
slug: addcal-co-eligibility
source_date: '2026-11-09'
source_filename: addcal-co-eligibility.yml
source_heading: Eligibility
source_page: https://addcal.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AddCal\naid: addcal-co\nurl: https://addcal.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited messaging\n  text: AddCal strictly prohibits the use of unsolicited messages (such as spam) to advertise, promote, or share\n    links to our website, Services, or any user-generated content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old, or the age of legal capacity in your jurisdiction, to use the\
  \ Services.\n"
source_yaml_url: https://artifacts.apis.io/addcal-co/eligibility/addcal-co-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from AddCal's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Event Management
- Software-as-a-Service
- Integration
- Productivity
- Company
---
