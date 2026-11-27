---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 or otherwise legally able to contract
    type: individual
  - text: If you use BlinkHost for an organisation, you represent that you have authority to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 or otherwise legally able to contract
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: Do not upload secrets, unlawful material or content that infringes another person's rights.
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
name: blinkhost-me
provenance_date: '2026-11-09'
provider_name: blinkhost-me
provider_slug: blinkhost-me
slug: blinkhost-me-eligibility
source_date: '2026-11-09'
source_filename: blinkhost-me-eligibility.yml
source_heading: Eligibility
source_page: https://blinkhost.me/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: blinkhost-me\naid: blinkhost-me\nurl: https://blinkhost.me/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 or otherwise legally able to contract\n- type: business\n  text: If you use BlinkHost for an organisation, you represent that you have authority to bind it.\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: Do not upload secrets, unlawful material or content that infringes another person's rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 or otherwise legally able to contract\n"
source_yaml_url: https://artifacts.apis.io/blinkhost-me/eligibility/blinkhost-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from blinkhost-me's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Platform
- Full-Stack
- Developer Tools
- Edge Deployment
---
