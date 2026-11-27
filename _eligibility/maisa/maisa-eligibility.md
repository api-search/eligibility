---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Services provided under this Agreement are for businesses, professionals and developers, not consumers
    type: business
  minimum_age:
    text: Access to and use of the Website is only permitted for individuals eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Criminal justice, law enforcement, censorship or surveillance
    text: To use it for criminal justice, law enforcement, censorship or surveillance purposes
  - summary: Replacing regulated professional advice
    text: To fully replace advice generally provided by qualified or registered advisors or professionals; including financial advisors, architects, lawyers and doctors, psychologists and any other healthcare professionals.
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
name: Maisa
provenance_date: '2026-11-10'
provider_name: Maisa
provider_slug: maisa
slug: maisa-eligibility
source_date: '2026-11-10'
source_filename: maisa-eligibility.yml
source_heading: Eligibility
source_page: https://maisa.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maisa\naid: maisa\nurl: https://maisa.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the Services provided under this Agreement are for businesses, professionals and developers, not consumers\nrestricted_uses:\n- summary: Criminal justice, law enforcement, censorship or surveillance\n  text: To use it for criminal justice, law enforcement, censorship or surveillance purposes\n- summary: Replacing regulated professional advice\n  text: To fully replace advice generally provided by qualified or registered advisors\
  \ or professionals; including\n    financial advisors, architects, lawyers and doctors, psychologists and any other healthcare professionals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Access to and use of the Website is only permitted for individuals eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/maisa/eligibility/maisa-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Maisa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Digital Workers
- Business Process Automation
- Enterprise Automation
- Banking
- Insurance
---
