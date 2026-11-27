---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered only to business customers acting in the course of their trade, business, craft or profession.
    type: business
  - text: Individuals acting as consumers for purposes of applicable consumer protection laws may not become customers under these ToS.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive evaluation or AI training
    text: for the purposes of competitive evaluation, research or benchmarking or training of any artificial intelligence model;
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
name: Next Matter
provenance_date: '2026-11-10'
provider_name: Next Matter
provider_slug: next-matter
slug: next-matter-eligibility
source_date: '2026-11-10'
source_filename: next-matter-eligibility.yml
source_heading: Eligibility
source_page: https://nextmatter.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Next Matter\naid: next-matter\nurl: https://nextmatter.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered only to business customers acting in the course of their trade, business, craft\n    or profession.\n- type: individual\n  text: Individuals acting as consumers for purposes of applicable consumer protection laws may not become customers\n    under these ToS.\nrestricted_uses:\n- summary: Competitive evaluation or AI training\n  text: for the purposes of competitive evaluation, research\
  \ or benchmarking or training of any artificial intelligence\n    model;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/next-matter/eligibility/next-matter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Next Matter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- Workflows
- Integration
- Software-as-a-Service
---
