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
  - summary: Free trial refusal for sanctioned or criminal-record inquirers
    text: The inquirer has been sanctioned by a BAR association in any state or has a criminal record of any kind.
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
name: Answering Legal
provenance_date: '2026-11-09'
provider_name: Answering Legal
provider_slug: answering-legal
slug: answering-legal-eligibility
source_date: '2026-11-09'
source_filename: answering-legal-eligibility.yml
source_heading: Eligibility
source_page: https://www.answeringlegal.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Answering Legal\naid: answering-legal\nurl: https://www.answeringlegal.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Free trial refusal for sanctioned or criminal-record inquirers\n  text: The inquirer has been sanctioned by a BAR association in any state or has a criminal record of any kind.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/answering-legal/eligibility/answering-legal-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Answering Legal's own page on 2026-11-09.
synthetic: false
tags:
- Legal Services
- Call Answering
- Virtual Receptionist
- AI Chatbot
- Bilingual Support
- Live Translation
- Law Firm Software
---
