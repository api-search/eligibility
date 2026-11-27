---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be the age of majority in your place of residence to use the Services.
    type: individual
  minimum_age:
    text: You must be the age of majority in your place of residence to use the Services.
    value: age of majority
  restricted_uses:
  - summary: Non-commercial personal education only
    text: We grant you a limited, non-exclusive, non-transferable, revocable license to use the Services for personal, non-commercial education.
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
name: CELPass
provenance_date: '2026-11-09'
provider_name: CELPass
provider_slug: celpass-com
slug: celpass-com-eligibility
source_date: '2026-11-09'
source_filename: celpass-com-eligibility.yml
source_heading: Eligibility
source_page: https://celpass.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CELPass\naid: celpass-com\nurl: https://celpass.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be the age of majority in your place of residence to use the Services.\nrestricted_uses:\n- summary: Non-commercial personal education only\n  text: We grant you a limited, non-exclusive, non-transferable, revocable license to use the Services for personal,\n    non-commercial education.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You\
  \ must be the age of majority in your place of residence to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/celpass-com/eligibility/celpass-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CELPass's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Language
- Test Prep
- Artificial Intelligence
- Canada
---
