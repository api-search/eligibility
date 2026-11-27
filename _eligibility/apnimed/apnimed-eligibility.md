---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Void Where Prohibited: the information herein is intended for use only by residents of the U.S.'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Medical advice reliance
    text: should not be considered complete, nor should it be used in any capacity as a basis for diagnosis or course of treatment
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
name: Apnimed
provenance_date: '2026-11-09'
provider_name: Apnimed
provider_slug: apnimed
slug: apnimed-eligibility
source_date: '2026-11-09'
source_filename: apnimed-eligibility.yml
source_heading: Eligibility
source_page: https://apnimed.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apnimed\naid: apnimed\nurl: https://apnimed.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Void Where Prohibited: the information herein is intended for use only by residents of the U.S.'\nentity_types: []\nrestricted_uses:\n- summary: Medical advice reliance\n  text: should not be considered complete, nor should it be used in any capacity as a basis for diagnosis or course\n    of treatment\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apnimed/eligibility/apnimed-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Apnimed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmaceuticals
- Biotechnology
- Healthcare
- Life Sciences
- Sleep Medicine
- Clinical Trials
---
