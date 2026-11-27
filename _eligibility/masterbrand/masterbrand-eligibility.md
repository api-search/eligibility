---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are a resident of the United States
  entity_types:
  - text: You must be 18 years of age or older to access our Site.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older to access our Site.
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: not for any commercial purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: MLLC is not under any obligation to verify the actual identity or authority of any person using a User Account to access and use the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MasterBrand
provenance_date: '2026-11-10'
provider_name: MasterBrand
provider_slug: masterbrand
slug: masterbrand-eligibility
source_date: '2026-11-10'
source_filename: masterbrand-eligibility.yml
source_heading: Eligibility
source_page: https://www.masterbrand.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MasterBrand\naid: masterbrand\nurl: https://www.masterbrand.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are a resident of the United States\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to access our Site.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: not for any commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: MLLC is not under any obligation to verify the actual identity or authority of any person using a User Account\n    to access\
  \ and use the Site.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to access our Site.\n"
source_yaml_url: https://artifacts.apis.io/masterbrand/eligibility/masterbrand-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from MasterBrand's own page on 2026-11-10.
synthetic: false
tags:
- Cabinetry
- Home Improvement
- Manufacturing
- Building Products
---
