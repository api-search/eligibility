---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is not intended for use by persons in any jurisdiction or country where such use would be contrary to applicable laws or regulations.
  minimum_age:
    text: The Site is not intended for use by persons under the age of 18 years.
    value: '18'
  restricted_uses:
  - summary: Commercial use beyond own use
    text: Constitutes a commercial use other than for your own use
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
name: Filtricine
provenance_date: '2026-11-09'
provider_name: Filtricine
provider_slug: filtricine
slug: filtricine-eligibility
source_date: '2026-11-09'
source_filename: filtricine-eligibility.yml
source_heading: Eligibility
source_page: https://filtricine.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Filtricine\naid: filtricine\nurl: https://filtricine.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is not intended for use by persons in any jurisdiction or country where such use would be contrary\n    to applicable laws or regulations.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use beyond own use\n  text: Constitutes a commercial use other than for your own use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is not intended for use by persons under the age\
  \ of 18 years.\n"
source_yaml_url: https://artifacts.apis.io/filtricine/eligibility/filtricine-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Filtricine's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Cancer
- Medical-Food
- Clinical Trials
- San Francisco
---
