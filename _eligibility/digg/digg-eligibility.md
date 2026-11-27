---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 14 years old to use Digg.
    type: individual
  - text: If you are using Digg on behalf of an organization, you confirm that you are authorized to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 14 years old to use Digg.
    value: '14'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: for your personal, non-commercial use, subject to these Terms
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
name: Digg
provenance_date: '2026-11-09'
provider_name: Digg
provider_slug: digg
slug: digg-eligibility
source_date: '2026-11-09'
source_filename: digg-eligibility.yml
source_heading: Eligibility
source_page: https://digg.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Digg\naid: digg\nurl: https://digg.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 14 years old to use Digg.\n- type: business\n  text: If you are using Digg on behalf of an organization, you confirm that you are authorized to bind that organization\n    to these Terms.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: for your personal, non-commercial use, subject to these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '14'\n  text: You must be at least 14 years old to use Digg.\n"
source_yaml_url: https://artifacts.apis.io/digg/eligibility/digg-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Digg's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News Aggregation
- Social News
- Content Curation
- Technology
- Media
- Artificial Intelligence
- News
---
