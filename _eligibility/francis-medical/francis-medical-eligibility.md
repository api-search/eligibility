---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: right to use Trident+ solely for Customer’s internal business purposes in the United States
  entity_types:
  - text: means the legal entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Qualified personnel only
    text: Customer will ensure that the Trident+ System is only used by duly qualified personnel
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
name: Francis Medical
provenance_date: '2026-11-09'
provider_name: Francis Medical
provider_slug: francis-medical
slug: francis-medical-eligibility
source_date: '2026-11-09'
source_filename: francis-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.francismedical.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Francis Medical\naid: francis-medical\nurl: https://www.francismedical.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: right to use Trident+ solely for Customer’s internal business purposes in the United States\nentity_types:\n- type: business\n  text: means the legal entity\nrestricted_uses:\n- summary: Qualified personnel only\n  text: Customer will ensure that the Trident+ System is only used by duly qualified personnel\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/francis-medical/eligibility/francis-medical-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Francis Medical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Devices
- Oncology
- Urology
- Prostate Cancer
- Surgery
- Ablation
- Clinical Trials
- Minimally Invasive
---
