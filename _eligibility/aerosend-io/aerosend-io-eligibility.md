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
  - summary: Sending to personal email addresses
    text: Clients must not send emails to personal email addresses (e.g., Gmail, Yahoo, Hotmail).
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
name: Aerosend
provenance_date: '2026-11-09'
provider_name: Aerosend
provider_slug: aerosend-io
slug: aerosend-io-eligibility
source_date: '2026-11-09'
source_filename: aerosend-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.aerosend.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aerosend\naid: aerosend-io\nurl: https://www.aerosend.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sending to personal email addresses\n  text: Clients must not send emails to personal email addresses (e.g., Gmail, Yahoo, Hotmail).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aerosend-io/eligibility/aerosend-io-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Aerosend's own page on 2026-11-09.
synthetic: false
tags:
- Email Deliverability
- Cold Email
- Software-as-a-Service
- Marketing
---
