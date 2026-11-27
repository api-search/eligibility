---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not be barred from using the Services under the laws of the United States, your country of residence, or your country of use
  entity_types:
  - text: be a natural person creating the account, or be authorized to act on behalf of the entity for which you are creating the account
    type: individual
  - text: If you are entering into these Terms on behalf of a company or other entity, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: PHI without a BAA prohibited
    text: You agree not to upload, transmit, store, or otherwise process Protected Health Information (“ PHI “) as defined by the Health Insurance Portability and Accountability Act of 1996 (“ HIPAA “) through the Services unless you have entered into a written Business Associate Agreement
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: provide accurate and complete information at sign-up
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SegMetrics
provenance_date: '2026-11-10'
provider_name: SegMetrics
provider_slug: segmetrics
slug: segmetrics-eligibility
source_date: '2026-11-10'
source_filename: segmetrics-eligibility.yml
source_heading: Eligibility
source_page: https://segmetrics.io/terms-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SegMetrics\naid: segmetrics\nurl: https://segmetrics.io/terms-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not be barred from using the Services under the laws of the United States, your country of residence, or\n    your country of use\nentity_types:\n- type: individual\n  text: be a natural person creating the account, or be authorized to act on behalf of the entity for which you\n    are creating the account\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other entity, you represent that you have\n    authority to bind that\
  \ entity\nrestricted_uses:\n- summary: PHI without a BAA prohibited\n  text: You agree not to upload, transmit, store, or otherwise process Protected Health Information (“ PHI “) as\n    defined by the Health Insurance Portability and Accountability Act of 1996 (“ HIPAA “) through the Services\n    unless you have entered into a written Business Associate Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: provide accurate and complete information at sign-up\nminimum_age:\n  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/segmetrics/eligibility/segmetrics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from SegMetrics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Analytics
- Attribution
- Marketing Analytics
- Reporting
- Business Intelligence
- Advertising
- Software-as-a-Service
- MCP
---
