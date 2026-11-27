---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The service is intended for general adult audiences and is not directed at children.
    value: null
  restricted_uses:
  - summary: Misuse and automated overload
    text: You agree not to misuse the service, including attempting to disrupt it, overloading it with automated requests, or using it in any way that violates applicable law.
  verification:
    approval_required: false
    kyb: null
    kyc: false
    text: It has no accounts, no registration and no payments, so no age verification is performed.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CheckMyPayRate
provenance_date: '2026-11-09'
provider_name: CheckMyPayRate
provider_slug: checkmypayrate-com
slug: checkmypayrate-com-eligibility
source_date: '2026-11-09'
source_filename: checkmypayrate-com-eligibility.yml
source_heading: Eligibility
source_page: https://checkmypayrate.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CheckMyPayRate\naid: checkmypayrate-com\nurl: https://checkmypayrate.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Misuse and automated overload\n  text: You agree not to misuse the service, including attempting to disrupt it, overloading it with automated requests,\n    or using it in any way that violates applicable law.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: false\n  text: It has no accounts, no registration and no payments, so no age verification is performed.\nminimum_age:\n  value: null\n\
  \  text: The service is intended for general adult audiences and is not directed at children.\n"
source_yaml_url: https://artifacts.apis.io/checkmypayrate-com/eligibility/checkmypayrate-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from CheckMyPayRate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Salary
- Compensation
- Benchmarks
- Labor Market Data
- Open Data
- Calculators
---
