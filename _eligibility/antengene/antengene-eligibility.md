---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export compliance: You agree not to export or re-export any part of the Service to countries or persons prohibited under such export control laws.'
  minimum_age:
    text: The Service is not intended for, or designed to attract, children under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You expressly agree to comply with any applicable export restrictions under any applicable export control laws
  - summary: Automated access
    text: You will not access or use the Service through automated or non-human means, whether through a bot, script, or otherwise
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
name: antengene
provenance_date: '2026-11-09'
provider_name: antengene
provider_slug: antengene
slug: antengene-eligibility
source_date: '2026-11-09'
source_filename: antengene-eligibility.yml
source_heading: Eligibility
source_page: https://antengene.com/about.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: antengene\naid: antengene\nurl: https://antengene.com/about.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export compliance: You agree not to export or re-export any part of the Service to countries or persons\n    prohibited under such export control laws.'\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: You expressly agree to comply with any applicable export restrictions under any applicable export control\n    laws\n- summary: Automated access\n  text: You will not access or use the Service through automated or non-human means, whether through\
  \ a bot, script,\n    or otherwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is not intended for, or designed to attract, children under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/antengene/eligibility/antengene-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from antengene's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biopharmaceutical
- Oncology
- Pharmaceuticals
- Healthcare
- Life Sciences
- Drug Development
---
