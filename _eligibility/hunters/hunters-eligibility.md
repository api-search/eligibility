---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Site is only intended for individuals aged thirteen (13) years or older.
    value: '13'
  restricted_uses:
  - summary: Automated access to the Site
    text: use or launch any automated system (including without limitation, “robots” and “spiders”) to access the Site
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
name: Hunters
provenance_date: '2026-11-09'
provider_name: Hunters
provider_slug: hunters
slug: hunters-eligibility
source_date: '2026-11-09'
source_filename: hunters-eligibility.yml
source_heading: Eligibility
source_page: https://www.hunters.security/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hunters\naid: hunters\nurl: https://www.hunters.security/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Automated access to the Site\n  text: use or launch any automated system (including without limitation, “robots” and “spiders”) to access the\n    Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/hunters/eligibility/hunters-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Hunters's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- SIEM
- SOC
- Threat Detection
- Security Operations
- Incident Response
- Threat Hunting
---
