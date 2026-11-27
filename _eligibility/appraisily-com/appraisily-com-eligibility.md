---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our paid Services are currently intended for customers located in the United States.
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to place an order or create an account on your own behalf.
    value: '18'
  restricted_uses:
  - summary: Unlawful or misleading submissions
    text: You must not submit content that is unlawful, defamatory, fraudulent, invasive of privacy, infringing, or misleading.
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
name: Appraisily
provenance_date: '2026-11-09'
provider_name: Appraisily
provider_slug: appraisily-com
slug: appraisily-com-eligibility
source_date: '2026-11-09'
source_filename: appraisily-com-eligibility.yml
source_heading: Eligibility
source_page: https://appraisily.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appraisily\naid: appraisily-com\nurl: https://appraisily.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our paid Services are currently intended for customers located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or misleading submissions\n  text: You must not submit content that is unlawful, defamatory, fraudulent, invasive of privacy, infringing, or\n    misleading.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age\
  \ of legal majority in your jurisdiction, to place an order\n    or create an account on your own behalf.\n"
source_yaml_url: https://artifacts.apis.io/appraisily-com/eligibility/appraisily-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Appraisily's own page on 2026-11-09.
synthetic: false
tags:
- Art
- Antiques
- Appraisal
- Valuation
- E-Commerce
---
