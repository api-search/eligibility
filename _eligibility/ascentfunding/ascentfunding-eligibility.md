---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Services (excluding Ascent sweepstakes and contests) are only available to individuals aged 18 and over.
    type: individual
  minimum_age:
    text: the Services (excluding Ascent sweepstakes and contests) are only available to individuals aged 18 and over.
    value: '18'
  restricted_uses:
  - summary: Commercial use beyond own use
    text: Constitutes a commercial use other than for your own use;
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
name: Ascentfunding
provenance_date: '2026-11-09'
provider_name: Ascentfunding
provider_slug: ascentfunding
slug: ascentfunding-eligibility
source_date: '2026-11-09'
source_filename: ascentfunding-eligibility.yml
source_heading: Eligibility
source_page: https://www.ascentfunding.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ascentfunding\naid: ascentfunding\nurl: https://www.ascentfunding.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the Services (excluding Ascent sweepstakes and contests) are only available to individuals aged 18 and over.\nrestricted_uses:\n- summary: Commercial use beyond own use\n  text: Constitutes a commercial use other than for your own use;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Services (excluding Ascent\
  \ sweepstakes and contests) are only available to individuals aged 18 and over.\n"
source_yaml_url: https://artifacts.apis.io/ascentfunding/eligibility/ascentfunding-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ascentfunding's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Education
- Loans
- Student Loans
---
