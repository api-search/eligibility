---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export restrictions: Customer must not export ... to (a) any U.S. embargoed jurisdiction, (b) anyone on any U.S. or applicable non-U.S. restricted- or denied-party list'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive personal information prohibited
    text: (h) upload or input Sensitive Personal Information to the Services
  - summary: Not a replacement for non-emergency communications
    text: (iii) not use the Services to replace typical non-emergency or non-critical communications systems
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
name: AlertMedia
provenance_date: '2026-11-09'
provider_name: AlertMedia
provider_slug: alertmedia
slug: alertmedia-eligibility
source_date: '2026-11-09'
source_filename: alertmedia-eligibility.yml
source_heading: Eligibility
source_page: https://www.alertmedia.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlertMedia\naid: alertmedia\nurl: https://www.alertmedia.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export restrictions: Customer must not export ... to (a) any U.S. embargoed jurisdiction, (b) anyone on\n    any U.S. or applicable non-U.S. restricted- or denied-party list'\nentity_types: []\nrestricted_uses:\n- summary: Sensitive personal information prohibited\n  text: (h) upload or input Sensitive Personal Information to the Services\n- summary: Not a replacement for non-emergency communications\n  text: (iii) not use the Services to replace typical\
  \ non-emergency or non-critical communications systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alertmedia/eligibility/alertmedia-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from AlertMedia's own page on 2026-11-09.
synthetic: false
tags:
- Mass Notification
- Threat Intelligence
- Travel Risk Management
- Employee Safety Monitoring
- Incident Response
- Social Intelligence
- Risk Intelligence Platform
---
