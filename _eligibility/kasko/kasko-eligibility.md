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
  - summary: Text/data mining and web scraping
    text: You shall not conduct, facilitate, authorise or permit any text or data mining or web scraping in relation to our site
  - summary: Automated access
    text: Any "robot", "bot", "spider", "scraper" or other automated device, program, tool, algorithm, code, process or methodology to access, obtain, copy, monitor or republish any portion of the site
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
name: Kasko
provenance_date: '2026-11-09'
provider_name: Kasko
provider_slug: kasko
slug: kasko-eligibility
source_date: '2026-11-09'
source_filename: kasko-eligibility.yml
source_heading: Eligibility
source_page: https://www.kasko.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kasko\naid: kasko\nurl: https://www.kasko.io/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Text/data mining and web scraping\n  text: You shall not conduct, facilitate, authorise or permit any text or data mining or web scraping in relation\n    to our site\n- summary: Automated access\n  text: Any \"robot\", \"bot\", \"spider\", \"scraper\" or other automated device, program, tool, algorithm, code, process\n    or methodology to access, obtain, copy, monitor or republish any portion of the site\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kasko/eligibility/kasko-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Kasko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Insurance API
- Policy Management
- Payments
- Webhook
- Embedded Insurance
- No-Code
---
