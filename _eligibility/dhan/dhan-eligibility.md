---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Online account opening using Aadhaar Card ("Aadhaar") is currently available only for residents of India opening accounts for an individual
  entity_types:
  - text: Online account opening using Aadhaar Card ("Aadhaar") is currently available only for residents of India opening accounts for an individual (HUFs, corporate bodies, NRIs, etc., shall not be eligible).
    type: individual
  minimum_age:
    text: Minors or people below 18 years old are not allowed to use this Platform
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: Using the Dhan Platform in anyway contrary to applicable laws and regulations
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Registration to the Dhan Platform is subject to the satisfactory completion of the registration form and submission of all mandatory documents and valid Permanent Account Number ("PAN") and its subsequent verification and KYC Registration Agency (KRA) verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dhan
provenance_date: '2026-11-09'
provider_name: Dhan
provider_slug: dhan
slug: dhan-eligibility
source_date: '2026-11-09'
source_filename: dhan-eligibility.yml
source_heading: Eligibility
source_page: https://dhan.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dhan\naid: dhan\nurl: https://dhan.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Online account opening using Aadhaar Card (\"Aadhaar\") is currently available only for residents of India\n    opening accounts for an individual\nentity_types:\n- type: individual\n  text: Online account opening using Aadhaar Card (\"Aadhaar\") is currently available only for residents of India\n    opening accounts for an individual (HUFs, corporate bodies, NRIs, etc., shall not be eligible).\nrestricted_uses:\n- summary: Unlawful use\n  text: Using the Dhan Platform in anyway contrary\
  \ to applicable laws and regulations\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Registration to the Dhan Platform is subject to the satisfactory completion of the registration form and\n    submission of all mandatory documents and valid Permanent Account Number (\"PAN\") and its subsequent verification\n    and KYC Registration Agency (KRA) verification.\nminimum_age:\n  value: '18'\n  text: Minors or people below 18 years old are not allowed to use this Platform\n"
source_yaml_url: https://artifacts.apis.io/dhan/eligibility/dhan-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Dhan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Trading
- Investment
---
