---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"User" or "you" means the person using the Service.'
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: No unsolicited bulk AI messages
    text: Use an AI app with Buzzfy to send unsolicited, bulk or automated messages or replies
  - summary: No Instagram policy violations
    text: Use the Service to post content that violates Instagram's Terms of Use, Community Guidelines, or any applicable law
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
name: Buzzfy
provenance_date: '2026-11-09'
provider_name: Buzzfy
provider_slug: buzzfy-co
slug: buzzfy-co-eligibility
source_date: '2026-11-09'
source_filename: buzzfy-co-eligibility.yml
source_heading: Eligibility
source_page: https://buzzfy.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buzzfy\naid: buzzfy-co\nurl: https://buzzfy.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"User\" or \"you\" means the person using the Service.'\nrestricted_uses:\n- summary: No unsolicited bulk AI messages\n  text: Use an AI app with Buzzfy to send unsolicited, bulk or automated messages or replies\n- summary: No Instagram policy violations\n  text: Use the Service to post content that violates Instagram's Terms of Use, Community Guidelines, or any applicable\n    law\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/buzzfy-co/eligibility/buzzfy-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Buzzfy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Instagram
- Growth
- Analytics
- Social Media
---
