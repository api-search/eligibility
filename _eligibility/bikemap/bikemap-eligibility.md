---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: All of our customers located in the European Union have the right to cancel any purchase within the first fourteen (14) days
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassment of users
    text: every user is obliged not to harass other users through intrusive communication attempts.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A legal entitlement to registration as a user of the services of Bikemap does not exist. This allows Bikemap to reject a registration requested by message to the user without providing any justification or reasoning.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bikemap
provenance_date: '2026-11-09'
provider_name: Bikemap
provider_slug: bikemap
slug: bikemap-eligibility
source_date: '2026-11-09'
source_filename: bikemap-eligibility.yml
source_heading: Eligibility
source_page: https://blog.bikemap.net/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bikemap\naid: bikemap\nurl: https://blog.bikemap.net/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: All of our customers located in the European Union have the right to cancel any purchase within the first\n    fourteen (14) days\nentity_types: []\nrestricted_uses:\n- summary: Harassment of users\n  text: every user is obliged not to harass other users through intrusive communication attempts.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A legal entitlement to registration as a user of the services of Bikemap does not exist. This\
  \ allows Bikemap\n    to reject a registration requested by message to the user without providing any justification or reasoning.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bikemap/eligibility/bikemap-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Bikemap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cycling
- Navigation
- Maps
- Route Planning
- Mobility
- Outdoor
- Consumer App
---
