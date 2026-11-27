---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    served: []
    text: subject to country sanctions imposed by the U.S. Government for any reason, including but not limited to being organized or headquartered in or a governmental entity of a country or territory subject to such sanctions (currently Crimea, Cuba, North Korea, Iran, and Syria).
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for retail investors
    text: MOODY’S CREDIT RATINGS AND MOODY’S MATERIALS ARE NOT INTENDED FOR USE BY RETAIL INVESTORS
  - summary: QIB Information limited to qualified institutional buyers
    text: you must be a QIB to access the QIB Information
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Moody's
provenance_date: '2026-11-10'
provider_name: Moody's
provider_slug: moodysanalytics
slug: moodysanalytics-eligibility
source_date: '2026-11-10'
source_filename: moodysanalytics-eligibility.yml
source_heading: Eligibility
source_page: https://community.moodysanalytics.com/site/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moody's\naid: moodysanalytics\nurl: https://community.moodysanalytics.com/site/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  text: subject to country sanctions imposed by the U.S. Government for any reason, including but not limited to\n    being organized or headquartered in or a governmental entity of a country or territory subject to such sanctions\n    (currently Crimea, Cuba, North Korea, Iran, and Syria).\nentity_types: []\nrestricted_uses:\n- summary: Not for retail investors\n  text: MOODY’S CREDIT RATINGS AND MOODY’S MATERIALS ARE NOT INTENDED\
  \ FOR USE BY RETAIL INVESTORS\n- summary: QIB Information limited to qualified institutional buyers\n  text: you must be a QIB to access the QIB Information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moodysanalytics/eligibility/moodysanalytics-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Moody's's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
