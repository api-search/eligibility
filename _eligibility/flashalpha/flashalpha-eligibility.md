---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Shared compute fair use
    text: Sustained, disproportionate, or runaway consumption (for example, malfunctioning or unbounded scripts, tight retry loops, or workloads that materially degrade performance for other users on the same node) goes beyond what a shared environment can fairly absorb.
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
name: Flashalpha
provenance_date: '2026-11-09'
provider_name: Flashalpha
provider_slug: flashalpha
slug: flashalpha-eligibility
source_date: '2026-11-09'
source_filename: flashalpha-eligibility.yml
source_heading: Eligibility
source_page: https://flashalpha.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flashalpha\naid: flashalpha\nurl: https://flashalpha.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Shared compute fair use\n  text: Sustained, disproportionate, or runaway consumption (for example, malfunctioning or unbounded scripts, tight\n    retry loops, or workloads that materially degrade performance for other users on the same node) goes beyond\n    what a shared environment can fairly absorb.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/flashalpha/eligibility/flashalpha-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Flashalpha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Options
- Analytics
---
