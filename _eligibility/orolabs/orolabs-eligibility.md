---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Services you must be, and represent and warrant that you are, of legal age
    type: individual
  minimum_age:
    text: 18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental consent, 13 years of age
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: Use the Services commercially, for benchmarking, or to compile information for a product or service;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You understand and agree that we may require you to provide information that may be used to confirm your identity and help ensure the security of your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Orolabs
provenance_date: '2026-11-10'
provider_name: Orolabs
provider_slug: orolabs
slug: orolabs-eligibility
source_date: '2026-11-10'
source_filename: orolabs-eligibility.yml
source_heading: Eligibility
source_page: https://www.orolabs.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Orolabs\naid: orolabs\nurl: https://www.orolabs.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Services you must be, and represent and warrant that you are, of legal age\nrestricted_uses:\n- summary: Commercial use\n  text: Use the Services commercially, for benchmarking, or to compile information for a product or service;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You understand and agree that we may require you to provide information that may be used to confirm your\n\
  \    identity and help ensure the security of your account.\nminimum_age:\n  value: '18'\n  text: 18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental consent,\n    13 years of age\n"
source_yaml_url: https://artifacts.apis.io/orolabs/eligibility/orolabs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Orolabs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Procurement
- Spend Management
- Supplier Management
- AI Agents
- Workflow Automation
- Enterprise Software
- ProcureTech
---
