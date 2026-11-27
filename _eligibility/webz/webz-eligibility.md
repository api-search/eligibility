---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You are invited to use the Website, the RESTful API, the Data Derivatives, and/or the Services only if you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal or improper purposes
    text: use the RESTful API, and any of the Data Derivatives contained therein for any illegal, unauthorized or other improper purposes
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
name: Webz.io
provenance_date: '2026-11-10'
provider_name: Webz.io
provider_slug: webz
slug: webz-eligibility
source_date: '2026-11-10'
source_filename: webz-eligibility.yml
source_heading: Eligibility
source_page: https://webz.io/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Webz.io\naid: webz\nurl: https://webz.io/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or improper purposes\n  text: use the RESTful API, and any of the Data Derivatives contained therein for any illegal, unauthorized or\n    other improper purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are invited to use the Website, the RESTful API, the Data Derivatives, and/or the Services only if you\n    are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/webz/eligibility/webz-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Webz.io's own page on 2026-11-10.
synthetic: false
tags:
- News Data
- Web Data
- Web Scraping
- Dark Web
- deep-web
- Cybersecurity
- Threat Intelligence
- Data Breaches
- pii-monitoring
- OSINT
- reviews-data
- AI Training Data
- Media Monitoring
---
