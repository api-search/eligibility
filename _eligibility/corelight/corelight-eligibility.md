---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We control and operate this Website from Our headquarters in the United States of America and the entirety of this Website may not be appropriate or available for use in other locations.
  entity_types:
  - text: We invite You to use this Website for individual, consumer purposes
    type: individual
  minimum_age:
    text: By using this Website, You promise that You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Unauthorized use beyond Permitted Purposes
    text: Any other use of this Website beyond the Permitted Purposes is prohibited
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
name: Corelight
provenance_date: '2026-11-09'
provider_name: Corelight
provider_slug: corelight
slug: corelight-eligibility
source_date: '2026-11-09'
source_filename: corelight-eligibility.yml
source_heading: Eligibility
source_page: https://corelight.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corelight\naid: corelight\nurl: https://corelight.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We control and operate this Website from Our headquarters in the United States of America and the entirety\n    of this Website may not be appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: We invite You to use this Website for individual, consumer purposes\nrestricted_uses:\n- summary: Unauthorized use beyond Permitted Purposes\n  text: Any other use of this Website beyond the Permitted Purposes is prohibited\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using this Website, You promise that You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/corelight/eligibility/corelight-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Corelight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Network Detection and Response
- Network Security
- Threat Detection
- Zeek
- Incident Response
- Security
---
