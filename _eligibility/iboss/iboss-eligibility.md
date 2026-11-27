---
claim_count: 2
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
  - summary: No filtering of End-User content without consent
    text: Customer hereby further represents and warrants that iboss Property will not be used to filter, screen, manage or censor Internet content for End-Users without permission from the affected End-Users.
  - summary: Export compliance
    text: iboss Property and Customer Content may be subject export requirements, including licenses, under United States or foreign laws.
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
name: iboss
provenance_date: '2026-11-09'
provider_name: iboss
provider_slug: iboss
slug: iboss-eligibility
source_date: '2026-11-09'
source_filename: iboss-eligibility.yml
source_heading: Eligibility
source_page: https://www.iboss.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iboss\naid: iboss\nurl: https://www.iboss.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No filtering of End-User content without consent\n  text: Customer hereby further represents and warrants that iboss Property will not be used to filter, screen,\n    manage or censor Internet content for End-Users without permission from the affected End-Users.\n- summary: Export compliance\n  text: iboss Property and Customer Content may be subject export requirements, including licenses, under United\n    States or foreign laws.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/iboss/eligibility/iboss-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from iboss's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Zero Trust
- SASE
- Secure Web Gateway
- CASB
- ZTNA
- Data Loss Prevention
- Network Security
- Cloud Security
- Compliance
---
