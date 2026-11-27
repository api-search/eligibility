---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are an individual (not an organication), You hereby certifiy to Baydin that You are at least 16 years of age.
    type: individual
  - text: In the event You are using the Service as the employee or agent of an organization that has a separate commercial agreement with Baydin for use of the Service and such agreement conflicts with this Agreement – such separate agreement shall control.
    type: business
  minimum_age:
    text: If You are an individual (not an organication), You hereby certifiy to Baydin that You are at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Unlawful purposes
    text: (v) use the Service for any unlawful purpose
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
name: Boomerang
provenance_date: '2026-11-09'
provider_name: Boomerang
provider_slug: boomerang
slug: boomerang-eligibility
source_date: '2026-11-09'
source_filename: boomerang-eligibility.yml
source_heading: Eligibility
source_page: https://www.boomeranggmail.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boomerang\naid: boomerang\nurl: https://www.boomeranggmail.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If You are an individual (not an organication), You hereby certifiy to Baydin that You are at least 16 years\n    of age.\n- type: business\n  text: In the event You are using the Service as the employee or agent of an organization that has a separate commercial\n    agreement with Baydin for use of the Service and such agreement conflicts with this Agreement – such separate\n    agreement shall control.\nrestricted_uses:\n\
  - summary: Unlawful purposes\n  text: (v) use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: If You are an individual (not an organication), You hereby certifiy to Baydin that You are at least 16 years\n    of age.\n"
source_yaml_url: https://artifacts.apis.io/boomerang/eligibility/boomerang-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Boomerang's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Productivity
- Email
- Scheduling
- Meetings
- Task Management
- Gmail
- Outlook
---
