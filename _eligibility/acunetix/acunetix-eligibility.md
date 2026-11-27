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
  - summary: Communications facility rules
    text: When using the enquiry form or any other System on the Web Site you should do so in accordance with the following rules
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
name: Invicti (formerly Acunetix)
provenance_date: '2026-11-09'
provider_name: Invicti (formerly Acunetix)
provider_slug: acunetix
slug: acunetix-eligibility
source_date: '2026-11-09'
source_filename: acunetix-eligibility.yml
source_heading: Eligibility
source_page: https://www.acunetix.com/about/terms_conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Invicti (formerly Acunetix)\naid: acunetix\nurl: https://www.acunetix.com/about/terms_conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Communications facility rules\n  text: When using the enquiry form or any other System on the Web Site you should do so in accordance with the\n    following rules\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acunetix/eligibility/acunetix-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Invicti (formerly Acunetix)'s own page on 2026-11-09.
synthetic: false
tags:
- Security
- Web Application Security
- Vulnerability Scanning
- API Testing
- DevSecOps
---
