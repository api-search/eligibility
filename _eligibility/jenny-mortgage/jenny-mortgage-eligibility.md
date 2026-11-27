---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: The calculations use Canadian mortgage conventions and apply anywhere in Canada. The preparation guides are written for Ontario. Jenny Tate's own mortgage agent services are offered in Ontario only.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No rate prediction or qualification assessment
    text: The tools do not search or predict interest rates, calculate a prepayment penalty, assess whether you qualify, or recommend a lender.
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
name: Mortgage Tools by Jenny
provenance_date: '2026-11-09'
provider_name: Mortgage Tools by Jenny
provider_slug: jenny-mortgage
slug: jenny-mortgage-eligibility
source_date: '2026-11-09'
source_filename: jenny-mortgage-eligibility.yml
source_heading: Eligibility
source_page: https://jenny.mortgage/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mortgage Tools by Jenny\naid: jenny-mortgage\nurl: https://jenny.mortgage/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: The calculations use Canadian mortgage conventions and apply anywhere in Canada. The preparation guides\n    are written for Ontario. Jenny Tate's own mortgage agent services are offered in Ontario only.\nentity_types: []\nrestricted_uses:\n- summary: No rate prediction or qualification assessment\n  text: The tools do not search or predict interest rates, calculate a prepayment penalty, assess whether you qualify,\n    or recommend\
  \ a lender.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jenny-mortgage/eligibility/jenny-mortgage-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Mortgage Tools by Jenny's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mortgage
- Calculator
- Artificial Intelligence
- Canada
---
