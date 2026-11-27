---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you hereby confirm that you have all necessary and legal authority to bind the company you represent
    type: business
  minimum_age:
    text: BuildDirect.com is not created for children or persons who are under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Speculative or fraudulent orders
    text: to make any speculative, false or fraudulent orders or any order in anticipation of demand
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
name: BuildDirect
provenance_date: '2026-11-09'
provider_name: BuildDirect
provider_slug: builddirect-technologies
slug: builddirect-technologies-eligibility
source_date: '2026-11-09'
source_filename: builddirect-technologies-eligibility.yml
source_heading: Eligibility
source_page: https://www.builddirect.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuildDirect\naid: builddirect-technologies\nurl: https://www.builddirect.com/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you hereby confirm that you have all necessary and legal authority to bind the company you represent\nrestricted_uses:\n- summary: Speculative or fraudulent orders\n  text: to make any speculative, false or fraudulent orders or any order in anticipation of demand\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: BuildDirect.com\
  \ is not created for children or persons who are under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/builddirect-technologies/eligibility/builddirect-technologies-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BuildDirect's own page on 2026-11-09.
synthetic: false
tags:
- Flooring
- Home Improvement
- Building Materials
- Trade Services
---
