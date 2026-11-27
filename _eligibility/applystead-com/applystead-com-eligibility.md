---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older and use one account in your own name.
    type: individual
  minimum_age:
    text: You must be 18 or older and use one account in your own name.
    value: '18'
  restricted_uses:
  - summary: Unlawful or ineligible job applications
    text: Do not use Applystead to break the law, to apply for jobs you are not eligible to hold
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
name: Applystead
provenance_date: '2026-11-09'
provider_name: Applystead
provider_slug: applystead-com
slug: applystead-com-eligibility
source_date: '2026-11-09'
source_filename: applystead-com-eligibility.yml
source_heading: Eligibility
source_page: https://applystead.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Applystead\naid: applystead-com\nurl: https://applystead.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older and use one account in your own name.\nrestricted_uses:\n- summary: Unlawful or ineligible job applications\n  text: Do not use Applystead to break the law, to apply for jobs you are not eligible to hold\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older and use one account in your own name.\n"
source_yaml_url: https://artifacts.apis.io/applystead-com/eligibility/applystead-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Applystead's own page on 2026-11-09.
synthetic: false
tags:
- Job Search
- Artificial Intelligence
- Resume
- Automation
- Careers
---
