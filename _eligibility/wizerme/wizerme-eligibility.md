---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may not use the services or accept the Terms if you are not at least 13 years old UNLESS YOUR PARENT OR SCHOOL HAVE PROVIDED THE NECESSARY CONSENT.
    type: individual
  minimum_age:
    text: you may not use the services or accept the Terms if you are not at least 13 years old UNLESS YOUR PARENT OR SCHOOL HAVE PROVIDED THE NECESSARY CONSENT.
    value: '13'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: You agree not to use the Services to collect, upload, transmit, display, or distribute any User Content
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
name: WizerMe
provenance_date: '2026-11-10'
provider_name: WizerMe
provider_slug: wizerme
slug: wizerme-eligibility
source_date: '2026-11-10'
source_filename: wizerme-eligibility.yml
source_heading: Eligibility
source_page: https://info.wizer.me/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WizerMe\naid: wizerme\nurl: https://info.wizer.me/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may not use the services or accept the Terms if you are not at least 13 years old UNLESS YOUR PARENT\n    OR SCHOOL HAVE PROVIDED THE NECESSARY CONSENT.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You agree not to use the Services to collect, upload, transmit, display, or distribute any User Content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: you may not use the services or accept the Terms if you are not at least 13 years old UNLESS YOUR PARENT\n    OR SCHOOL HAVE PROVIDED THE NECESSARY CONSENT.\n"
source_yaml_url: https://artifacts.apis.io/wizerme/eligibility/wizerme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from WizerMe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Worksheets
- Assessment
- Learning
- Teachers
- K-12
---
