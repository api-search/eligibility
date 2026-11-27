---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Kinside Services are currently available in the continental U.S. only.
  minimum_age:
    text: You represent and warrant that you are at least eighteen (18) years of age or have otherwise reached the age of majority where you reside
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Kinside Services only for lawful purposes and in accordance with this Agreement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Kinside does not make any attempt to verify the statements of users of the Kinside Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kinside
provenance_date: '2026-11-09'
provider_name: Kinside
provider_slug: kinside
slug: kinside-eligibility
source_date: '2026-11-09'
source_filename: kinside-eligibility.yml
source_heading: Eligibility
source_page: https://daycare.urbansitter.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kinside\naid: kinside\nurl: https://daycare.urbansitter.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Kinside Services are currently available in the continental U.S. only.\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Kinside Services only for lawful purposes and in accordance with this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Kinside does not make any attempt to verify the statements of users of the Kinside Services.\nminimum_age:\n  value: '18'\n\
  \  text: You represent and warrant that you are at least eighteen (18) years of age or have otherwise reached the\n    age of majority where you reside\n"
source_yaml_url: https://artifacts.apis.io/kinside/eligibility/kinside-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Kinside's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Childcare
- Family Benefits
- Employee Benefits
- Care Marketplace
- Government Data
---
