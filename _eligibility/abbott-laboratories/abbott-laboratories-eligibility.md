---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Policy applies to residents of the United States. Persons listed as denied parties by OFAC are not intended to use this Web site.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for OFAC denied parties
    text: This Web site is not intended to be used by those parties listed as denied parties by the U.S. Department of Treasury's Office of Foreign Asset's Control (OFAC)
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
name: Abbott Laboratories
provenance_date: '2026-11-09'
provider_name: Abbott Laboratories
provider_slug: abbott-laboratories
slug: abbott-laboratories-eligibility
source_date: '2026-11-09'
source_filename: abbott-laboratories-eligibility.yml
source_heading: Eligibility
source_page: https://www.abbott.com/en-us/online-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abbott Laboratories\naid: abbott-laboratories\nurl: https://www.abbott.com/en-us/online-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Policy applies to residents of the United States. Persons listed as denied parties by OFAC are not\n    intended to use this Web site.\nentity_types: []\nrestricted_uses:\n- summary: Not for OFAC denied parties\n  text: This Web site is not intended to be used by those parties listed as denied parties by the U.S. Department\n    of Treasury's Office of Foreign Asset's Control (OFAC)\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/abbott-laboratories/eligibility/abbott-laboratories-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Abbott Laboratories's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Medical Devices
- Diagnostics
- Digital Health
- Life Sciences
- Fortune 500
---
