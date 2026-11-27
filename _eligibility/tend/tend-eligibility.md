---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is controlled and offered by Tend from its facilities in the United States of America. Tend makes no representations that the Site is appropriate or available for use in other locations.
  minimum_age:
    text: THE SITE IS NOT INTENDED FOR USERS WHO ARE YOUNGER THAN THIRTEEN (13) YEARS OF AGE.
    value: '13'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: solely for your personal and non-commercial purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may reject your application for an Account, or cancel an existing Account, for any reason, in our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tend
provenance_date: '2026-11-10'
provider_name: Tend
provider_slug: tend
slug: tend-eligibility
source_date: '2026-11-10'
source_filename: tend-eligibility.yml
source_heading: Eligibility
source_page: https://www.hellotend.com/site/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tend\naid: tend\nurl: https://www.hellotend.com/site/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Site is controlled and offered by Tend from its facilities in the United States of America. Tend makes\n    no representations that the Site is appropriate or available for use in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: solely for your personal and non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We may reject your application for an\
  \ Account, or cancel an existing Account, for any reason, in our sole\n    discretion.\nminimum_age:\n  value: '13'\n  text: THE SITE IS NOT INTENDED FOR USERS WHO ARE YOUNGER THAN THIRTEEN (13) YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/tend/eligibility/tend-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Tend's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Dental
- Healthcare
- Consumer Health
- Booking
- Local Services
---
