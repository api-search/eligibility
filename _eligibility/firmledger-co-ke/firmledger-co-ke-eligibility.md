---
api_specs:
- filename: firmledger-co-ke-openapi-generated.yml
  format: yaml
  label: FirmLedger API
  slug: firmledger-co-ke-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firmledger-co-ke/openapi/_ae-authored/firmledger-co-ke-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to form a binding contract to hold an account.
    type: individual
  - text: Job listings are submitted by businesses and their authorised representatives.
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a binding contract to hold an account.
    value: '18'
  restricted_uses:
  - summary: Discriminatory or unlawful job posts
    text: You must not post discriminatory, misleading or unlawful roles
  - summary: False or fabricated submissions
    text: You must not submit deliberately false facts, fabricate sources, impersonate another entity
  - summary: Fraudulent ownership claims
    text: Fraudulent claiming (including impersonation, doctored screenshots, or DNS takeovers) is a material breach of these terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All submissions pass human review before publication.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FirmLedger
provenance_date: '2026-11-09'
provider_name: FirmLedger
provider_slug: firmledger-co-ke
slug: firmledger-co-ke-eligibility
source_date: '2026-11-09'
source_filename: firmledger-co-ke-eligibility.yml
source_heading: Eligibility
source_page: https://firmledger.co.ke/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FirmLedger\naid: firmledger-co-ke\nurl: https://firmledger.co.ke/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a binding contract to hold an account.\n- type: business\n  text: Job listings are submitted by businesses and their authorised representatives.\nrestricted_uses:\n- summary: Discriminatory or unlawful job posts\n  text: You must not post discriminatory, misleading or unlawful roles\n- summary: False or fabricated submissions\n  text: You must not submit deliberately false facts,\
  \ fabricate sources, impersonate another entity\n- summary: Fraudulent ownership claims\n  text: Fraudulent claiming (including impersonation, doctored screenshots, or DNS takeovers) is a material breach\n    of these terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All submissions pass human review before publication.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract to hold an account.\n"
source_yaml_url: https://artifacts.apis.io/firmledger-co-ke/eligibility/firmledger-co-ke-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from FirmLedger's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Directory
- Business Intelligence
- Kenya
---
