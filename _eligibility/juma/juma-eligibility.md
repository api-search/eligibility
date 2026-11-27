---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is designed exclusively for business entities and organizations.
    type: business
  - text: By accessing the Service, you affirm that you are a business entity (including sole proprietors) or non-profit organization
    type: nonprofit
  minimum_age:
    text: You must not use the Services if you are under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: No PHI without BAA
    text: You agree not to submit, upload, or otherwise transmit PHI through the Service unless you have executed a separate Business Associate Agreement ("BAA") with Team-GPT Ltd.
  - summary: No high-risk AI systems
    text: use of the Service with high-risk AI systems
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to accept or decline any subscription offer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Juma
provenance_date: '2026-11-09'
provider_name: Juma
provider_slug: juma
slug: juma-eligibility
source_date: '2026-11-09'
source_filename: juma-eligibility.yml
source_heading: Eligibility
source_page: https://juma.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Juma\naid: juma\nurl: https://juma.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is designed exclusively for business entities and organizations.\n- type: nonprofit\n  text: By accessing the Service, you affirm that you are a business entity (including sole proprietors) or non-profit\n    organization\nrestricted_uses:\n- summary: No PHI without BAA\n  text: You agree not to submit, upload, or otherwise transmit PHI through the Service unless you have executed\n    a separate Business Associate Agreement\
  \ (\"BAA\") with Team-GPT Ltd.\n- summary: No high-risk AI systems\n  text: use of the Service with high-risk AI systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right to accept or decline any subscription offer.\nminimum_age:\n  value: '13'\n  text: You must not use the Services if you are under 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/juma/eligibility/juma-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Juma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Marketing
- Automation
- Software-as-a-Service
- Advertising
---
