---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Marketing without consent
    text: Every marketing message must reference a valid consent_record_id in the consent_store
  - summary: Cold outreach and prospecting
    text: Cold outreach — contacting any recipient who has no prior relationship with the SMB and has not initiated or pre-authorized the communication.
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
name: hatchloop-dev
provenance_date: '2026-11-09'
provider_name: hatchloop-dev
provider_slug: hatchloop-dev
slug: hatchloop-dev-eligibility
source_date: '2026-11-09'
source_filename: hatchloop-dev-eligibility.yml
source_heading: Eligibility
source_page: https://hatchloop.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hatchloop-dev\naid: hatchloop-dev\nurl: https://hatchloop.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Marketing without consent\n  text: Every marketing message must reference a valid consent_record_id in the consent_store\n- summary: Cold outreach and prospecting\n  text: Cold outreach — contacting any recipient who has no prior relationship with the SMB and has not initiated\n    or pre-authorized the communication.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/hatchloop-dev/eligibility/hatchloop-dev-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from hatchloop-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automation
- Platform
- Developer Tools
---
