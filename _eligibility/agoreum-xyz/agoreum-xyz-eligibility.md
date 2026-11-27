---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to make a binding agreement where you live.
    type: individual
  - text: If you use Agoreum for an organization, you confirm you may bind it, and these terms bind it too.
    type: business
  minimum_age:
    text: You must be at least 18 and able to make a binding agreement where you live.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or regions
    text: You may not use Agoreum if you are the subject of sanctions administered by the United Nations, the United States, the European Union or the United Kingdom, if you act for someone who is, or from a country or region under comprehensive sanctions.
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
name: agoreum-xyz
provenance_date: '2026-11-09'
provider_name: agoreum-xyz
provider_slug: agoreum-xyz
slug: agoreum-xyz-eligibility
source_date: '2026-11-09'
source_filename: agoreum-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://www.agoreum.xyz/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agoreum-xyz\naid: agoreum-xyz\nurl: https://www.agoreum.xyz/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to make a binding agreement where you live.\n- type: business\n  text: If you use Agoreum for an organization, you confirm you may bind it, and these terms bind it too.\nrestricted_uses:\n- summary: Sanctioned persons or regions\n  text: You may not use Agoreum if you are the subject of sanctions administered by the United Nations, the United\n    States, the European Union or the United\
  \ Kingdom, if you act for someone who is, or from a country or region\n    under comprehensive sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to make a binding agreement where you live.\n"
source_yaml_url: https://artifacts.apis.io/agoreum-xyz/eligibility/agoreum-xyz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from agoreum-xyz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Fintech
- Marketplace
- Web3
---
