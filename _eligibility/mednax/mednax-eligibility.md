---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Information published on the Websites may refer to products, programs or services that are not available in your country or region.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical diagnosis or treatment
    text: The information provided on the Websites should not be used for the diagnosis or treatment of any medical condition.
  - summary: No patient-identifying information
    text: No patient-identifying information is to be shared or transmitted to the Websites.
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
name: Pediatrix Medical Group (formerly MEDNAX)
provenance_date: '2026-11-10'
provider_name: Pediatrix Medical Group (formerly MEDNAX)
provider_slug: mednax
slug: mednax-eligibility
source_date: '2026-11-10'
source_filename: mednax-eligibility.yml
source_heading: Eligibility
source_page: https://www.pediatrix.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pediatrix Medical Group (formerly MEDNAX)\naid: mednax\nurl: https://www.pediatrix.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Information published on the Websites may refer to products, programs or services that are not available\n    in your country or region.\nentity_types: []\nrestricted_uses:\n- summary: No medical diagnosis or treatment\n  text: The information provided on the Websites should not be used for the diagnosis or treatment of any medical\n    condition.\n- summary: No patient-identifying information\n  text: No patient-identifying information\
  \ is to be shared or transmitted to the Websites.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mednax/eligibility/mednax-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Pediatrix Medical Group (formerly MEDNAX)'s own page on 2026-11-10.
synthetic: false
tags:
- Fortune 1000
- Healthcare
- Healthcare Services
- Physician Services
- Pediatrics
- Neonatology
- Hospitals
- Telehealth
---
