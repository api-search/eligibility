---
api_specs:
- filename: awareness-market-openapi-generated.yml
  format: yaml
  label: Awareness API
  slug: awareness-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awareness-market/openapi/_ae-authored/awareness-market-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses
    text: any use that creates undue risk to individual or public safety
  - summary: High-risk decisions without human review
    text: Never use AI output for live financial decisions or other high-risk actions without independent human verification and appropriate professional review.
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
name: Awareness
provenance_date: '2026-11-09'
provider_name: Awareness
provider_slug: awareness-market
slug: awareness-market-eligibility
source_date: '2026-11-09'
source_filename: awareness-market-eligibility.yml
source_heading: Eligibility
source_page: https://awareness.market/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Awareness\naid: awareness-market\nurl: https://awareness.market/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\nrestricted_uses:\n- summary: Prohibited uses\n  text: any use that creates undue risk to individual or public safety\n- summary: High-risk decisions\
  \ without human review\n  text: Never use AI output for live financial decisions or other high-risk actions without independent human verification\n    and appropriate professional review.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/awareness-market/eligibility/awareness-market-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Awareness's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Agents
- Open Source
- Cloud
---
