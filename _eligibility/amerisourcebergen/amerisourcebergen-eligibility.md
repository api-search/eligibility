---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - GB
    text: Information concerning pharmaceutical distribution services applies only to services provided within the United States, Canada or the United Kingdom
  minimum_age:
    text: You also represent that you are at least 18 years of age and possess the legal capacity to enter into this Agreement.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you agree not to use this Web Site or its Content for any purpose that is unlawful or prohibited by these terms, conditions, and notices.
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
name: AmerisourceBergen
provenance_date: '2026-11-09'
provider_name: AmerisourceBergen
provider_slug: amerisourcebergen
slug: amerisourcebergen-eligibility
source_date: '2026-11-09'
source_filename: amerisourcebergen-eligibility.yml
source_heading: Eligibility
source_page: https://www.cencora.com/global-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AmerisourceBergen\naid: amerisourcebergen\nurl: https://www.cencora.com/global-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - GB\n  excluded: []\n  text: Information concerning pharmaceutical distribution services applies only to services provided within the\n    United States, Canada or the United Kingdom\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you agree not to use this Web Site or its Content for any purpose that is unlawful or prohibited by these\n    terms, conditions, and notices.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You also represent that you are at least 18 years of age and possess the legal capacity to enter into this\n    Agreement.\n"
source_yaml_url: https://artifacts.apis.io/amerisourcebergen/eligibility/amerisourcebergen-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AmerisourceBergen's own page on 2026-11-09.
synthetic: false
tags:
- Pharmaceutical Distribution
- Healthcare
- Drug Distribution
- Manufacturer Solutions
- Provider Solutions
- Animal Health
- Life Sciences
- Fortune 100
---
