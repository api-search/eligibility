---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An individual contracting personally accepts on their own behalf.
    type: individual
  - text: A person authorized to bind the contracting organization expressly accepts them at account setup, checkout, an agreed migration or by expressly accepting a Service Order (statement of work, SOW) that incorporates these terms and identifies their exact version.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data requires authorization
    text: Special-category, highly sensitive or legally protected data requires the agreed authorization and safeguards.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Referral participation requires Zephior approval and a mutually accepted partner-specific commercial schedule incorporating this exact Terms version.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: zephior-com
provenance_date: '2026-11-10'
provider_name: zephior-com
provider_slug: zephior-com
slug: zephior-com-eligibility
source_date: '2026-11-10'
source_filename: zephior-com-eligibility.yml
source_heading: Eligibility
source_page: https://zephior.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: zephior-com\naid: zephior-com\nurl: https://zephior.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An individual contracting personally accepts on their own behalf.\n- type: business\n  text: A person authorized to bind the contracting organization expressly accepts them at account setup, checkout,\n    an agreed migration or by expressly accepting a Service Order (statement of work, SOW) that incorporates these\n    terms and identifies their exact version.\nrestricted_uses:\n- summary: Sensitive data requires authorization\n\
  \  text: Special-category, highly sensitive or legally protected data requires the agreed authorization and safeguards.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Referral participation requires Zephior approval and a mutually accepted partner-specific commercial schedule\n    incorporating this exact Terms version.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zephior-com/eligibility/zephior-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from zephior-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Procurement
- Tender
- Marketplace
---
