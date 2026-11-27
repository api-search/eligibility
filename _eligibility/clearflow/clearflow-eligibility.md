---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the product information on the ClearFlow site is intended for use by U.S. residents.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Promotion of unauthorized products
    text: You should not construe anything on the site as a promotion or solicitation for any product or for the use of any product that is not authorized by the laws and regulations of the country where you are located.
  - summary: Diagnosing health problems from site information
    text: You should not use the information contained herein for diagnosing a health or fitness problem or disease.
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
name: ClearFlow
provenance_date: '2026-11-09'
provider_name: ClearFlow
provider_slug: clearflow
slug: clearflow-eligibility
source_date: '2026-11-09'
source_filename: clearflow-eligibility.yml
source_heading: Eligibility
source_page: https://clearflow.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClearFlow\naid: clearflow\nurl: https://clearflow.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the product information on the ClearFlow site is intended for use by U.S. residents.\nentity_types: []\nrestricted_uses:\n- summary: Promotion of unauthorized products\n  text: You should not construe anything on the site as a promotion or solicitation for any product or for the use\n    of any product that is not authorized by the laws and regulations of the country where you are located.\n- summary: Diagnosing health problems from site information\n  text: You\
  \ should not use the information contained herein for diagnosing a health or fitness problem or disease.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clearflow/eligibility/clearflow-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from ClearFlow's own page on 2026-11-09.
synthetic: false
tags:
- Medical Devices
- Surgery
- Healthcare
- Innovation
- Patient Recovery
---
