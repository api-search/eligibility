---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a business or other entity, you represent that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Business-owner accounts are currently invite-only. You may not create a business-owner account without an invitation from us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Advocate
provenance_date: '2026-11-09'
provider_name: Advocate
provider_slug: advocatemcp-com
slug: advocatemcp-com-eligibility
source_date: '2026-11-09'
source_filename: advocatemcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://app.advocatemcp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Advocate\naid: advocatemcp-com\nurl: https://app.advocatemcp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a business or other entity, you represent that you have\n    the authority to bind that entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Business-owner accounts are currently invite-only. You may not create a business-owner account without an\n    invitation from us.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/advocatemcp-com/eligibility/advocatemcp-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Advocate's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Business
- Directory
- Local
- Services
---
