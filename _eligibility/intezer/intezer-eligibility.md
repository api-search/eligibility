---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may use the Site only if you are at least thirteen (13) years old.
    value: '13'
  restricted_uses:
  - summary: Prohibited conduct on Site
    text: There are certain conducts that are strictly prohibited on and/or with respect to the Site.
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
name: Intezer
provenance_date: '2026-11-09'
provider_name: Intezer
provider_slug: intezer
slug: intezer-eligibility
source_date: '2026-11-09'
source_filename: intezer-eligibility.yml
source_heading: Eligibility
source_page: https://intezer.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Intezer\naid: intezer\nurl: https://intezer.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited conduct on Site\n  text: There are certain conducts that are strictly prohibited on and/or with respect to the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may use the Site only if you are at least thirteen (13) years old.\n"
source_yaml_url: https://artifacts.apis.io/intezer/eligibility/intezer-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Intezer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Security
- Malware Analysis
- Threat Intelligence
- SOC
- Incident Response
- Artificial Intelligence
- Automation
---
