---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Access to the Website is reserved for persons over 18 years of age.
    type: individual
  minimum_age:
    text: Access to the Website is reserved for persons over 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: The User must make use of the Website in full respect of the current legislation and these Terms of Use, under their sole responsibility.
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
name: WIVI Vision
provenance_date: '2026-11-10'
provider_name: WIVI Vision
provider_slug: wivi-vision
slug: wivi-vision-eligibility
source_date: '2026-11-10'
source_filename: wivi-vision-eligibility.yml
source_heading: Eligibility
source_page: https://wivivision.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WIVI Vision\naid: wivi-vision\nurl: https://wivivision.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Access to the Website is reserved for persons over 18 years of age.\nrestricted_uses:\n- summary: Lawful use only\n  text: The User must make use of the Website in full respect of the current legislation and these Terms of Use,\n    under their sole responsibility.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Access to the Website is reserved\
  \ for persons over 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/wivi-vision/eligibility/wivi-vision-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from WIVI Vision's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Eye Care
- Diagnostics
- Innovation
---
