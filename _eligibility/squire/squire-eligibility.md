---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Residents of Canada referenced only for SMS opt-out wording; no service territory stated.
  entity_types:
  - text: By becoming a User, you represent and warrant that you are at least 18 years old and that you have the right, authority and capacity to enter into and abide by the terms
    type: individual
  minimum_age:
    text: the Services are not available to children (persons under the age of 18)
    value: '18'
  restricted_uses:
  - summary: No protected health information
    text: You should not share any protected health information with service providers via the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Squire does not routinely screen its Users, inquire into the background of its Users or attempt to verify information provided by any User.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Squire
provenance_date: '2026-11-10'
provider_name: Squire
provider_slug: squire
slug: squire-eligibility
source_date: '2026-11-10'
source_filename: squire-eligibility.yml
source_heading: Eligibility
source_page: https://getsquire.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Squire\naid: squire\nurl: https://getsquire.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Residents of Canada referenced only for SMS opt-out wording; no service territory stated.\nentity_types:\n- type: individual\n  text: By becoming a User, you represent and warrant that you are at least 18 years old and that you have the right,\n    authority and capacity to enter into and abide by the terms\nrestricted_uses:\n- summary: No protected health information\n  text: You should not share any protected health information with service providers via the Service.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Squire does not routinely screen its Users, inquire into the background of its Users or attempt to verify\n    information provided by any User.\nminimum_age:\n  value: '18'\n  text: the Services are not available to children (persons under the age of 18)\n"
source_yaml_url: https://artifacts.apis.io/squire/eligibility/squire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Squire's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Booking
- Scheduling
- Payments
- Point-of-Sale
- Barbershop
- Software-as-a-Service
- Small Business
---
