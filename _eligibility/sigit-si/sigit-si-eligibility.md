---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old, or 16 in the EU.
    value: '13'
  restricted_uses:
  - summary: Unlawful or malware content
    text: Upload malware, or use repositories to distribute it
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account to use most features, handled through smbCloud Auth.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: sigit-si
provenance_date: '2026-11-10'
provider_name: sigit-si
provider_slug: sigit-si
slug: sigit-si-eligibility
source_date: '2026-11-10'
source_filename: sigit-si-eligibility.yml
source_heading: Eligibility
source_page: https://sigit.si/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sigit-si\naid: sigit-si\nurl: https://sigit.si/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or malware content\n  text: Upload malware, or use repositories to distribute it\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need an account to use most features, handled through smbCloud Auth.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old, or 16 in the EU.\n"
source_yaml_url: https://artifacts.apis.io/sigit-si/eligibility/sigit-si-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from sigit-si's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Git Hosting
- Artificial Intelligence
- Version Control
- Model Storage
- Open Source
---
