---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of an entity, such as your employer or the company you work for, you represent that you have the legal authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No special category or criminal offence data
    text: Subscriber will not and will not assist or permit any third party to, pass special category data or criminal offence data through the use of JivoChat applications.
  - summary: Competitors barred
    text: You may not access or use the JivoChat Services if you are a competitor of JivoChat, except with our prior written consent.
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
name: JivoChat
provenance_date: '2026-11-09'
provider_name: JivoChat
provider_slug: jivochat
slug: jivochat-eligibility
source_date: '2026-11-09'
source_filename: jivochat-eligibility.yml
source_heading: Eligibility
source_page: https://www.jivochat.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JivoChat\naid: jivochat\nurl: https://www.jivochat.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of an entity, such as your employer or the company you work\n    for, you represent that you have the legal authority to bind that entity.\nrestricted_uses:\n- summary: No special category or criminal offence data\n  text: Subscriber will not and will not assist or permit any third party to, pass special category data or criminal\n    offence data through the use of JivoChat applications.\n\
  - summary: Competitors barred\n  text: You may not access or use the JivoChat Services if you are a competitor of JivoChat, except with our prior\n    written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jivochat/eligibility/jivochat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from JivoChat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Live Chat
- Messaging
- Artificial Intelligence
- Customer Service
---
