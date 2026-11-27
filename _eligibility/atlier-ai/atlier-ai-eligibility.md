---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be old enough to form a binding contract in your jurisdiction to use the Service.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you are authorized to bind that organization to these Terms, and "you" includes that organization.
    type: business
  minimum_age:
    text: You must be old enough to form a binding contract in your jurisdiction to use the Service.
    value: null
  restricted_uses:
  - summary: Sensitive data and credentials
    text: submit payment-card data, protected health information, government identifiers, passwords, API keys, MFA/OTP codes, or other access credentials/authentication secrets to a Project Desk field
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
name: Atlier
provenance_date: '2026-11-09'
provider_name: Atlier
provider_slug: atlier-ai
slug: atlier-ai-eligibility
source_date: '2026-11-09'
source_filename: atlier-ai-eligibility.yml
source_heading: Eligibility
source_page: https://atlier.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlier\naid: atlier-ai\nurl: https://atlier.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be old enough to form a binding contract in your jurisdiction to use the Service.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you are authorized to bind that\n    organization to these Terms, and \"you\" includes that organization.\nrestricted_uses:\n- summary: Sensitive data and credentials\n  text: submit payment-card data, protected health information, government identifiers,\
  \ passwords, API keys, MFA/OTP\n    codes, or other access credentials/authentication secrets to a Project Desk field\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to form a binding contract in your jurisdiction to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/atlier-ai/eligibility/atlier-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Atlier's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Project Management
- Software-as-a-Service
- Collaboration
- Productivity
- Beta
---
