---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: as a commercial user of the Platform (“Client”)
    type: business
  - text: as an individual user only navigating through our Site (“you”, “your”, or “user”)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No automated access or scraping
    text: use any robot, spider, crawler, scraper or other automated means or interface not provided by us to access the Platform and the Site or to extract data
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
name: Siena
provenance_date: '2026-11-10'
provider_name: Siena
provider_slug: siena
slug: siena-eligibility
source_date: '2026-11-10'
source_filename: siena-eligibility.yml
source_heading: Eligibility
source_page: https://www.siena.cx/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Siena\naid: siena\nurl: https://www.siena.cx/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: as a commercial user of the Platform (“Client”)\n- type: individual\n  text: as an individual user only navigating through our Site (“you”, “your”, or “user”)\nrestricted_uses:\n- summary: No automated access or scraping\n  text: use any robot, spider, crawler, scraper or other automated means or interface not provided by us to access\n    the Platform and the Site or to extract data\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/siena/eligibility/siena-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Siena's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Customer Service
- Customer Experience
- Conversational AI
- E-Commerce
- Support Automation
---
