---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Services are intended for use by healthcare organizations, credentialing professionals, and authorized individuals involved in medical credentialing and enrollment processes.
    type: business
  - text: You must be at least 18 years of age and have the legal capacity to enter into binding contracts to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age and have the legal capacity to enter into binding contracts to use our Services.
    value: '18'
  restricted_uses:
  - summary: Fraudulent information
    text: Use the Services to transmit false, misleading, or fraudulent information
  - summary: Unauthorized access
    text: Access or attempt to access systems, data, or accounts not authorized for your use
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
name: Credflow
provenance_date: '2026-11-09'
provider_name: Credflow
provider_slug: credflow
slug: credflow-eligibility
source_date: '2026-11-09'
source_filename: credflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.credflow.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Credflow\naid: credflow\nurl: https://www.credflow.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Services are intended for use by healthcare organizations, credentialing professionals, and authorized\n    individuals involved in medical credentialing and enrollment processes.\n- type: individual\n  text: You must be at least 18 years of age and have the legal capacity to enter into binding contracts to use\n    our Services.\nrestricted_uses:\n- summary: Fraudulent information\n  text: Use the Services to\
  \ transmit false, misleading, or fraudulent information\n- summary: Unauthorized access\n  text: Access or attempt to access systems, data, or accounts not authorized for your use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age and have the legal capacity to enter into binding contracts to use\n    our Services.\n"
source_yaml_url: https://artifacts.apis.io/credflow/eligibility/credflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Credflow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Healthcare
- Artificial Intelligence
- Credentialing
---
