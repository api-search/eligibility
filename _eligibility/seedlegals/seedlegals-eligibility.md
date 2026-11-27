---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you confirm that you intend to use the Platform and Services in the course of your business, craft, trade or profession.
    type: business
  minimum_age:
    text: you are over 18 years of age
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: we may run KYC and AML verification checks on your company profile to confirm you are who you say you are
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SeedLegals
provenance_date: '2026-11-10'
provider_name: SeedLegals
provider_slug: seedlegals
slug: seedlegals-eligibility
source_date: '2026-11-10'
source_filename: seedlegals-eligibility.yml
source_heading: Eligibility
source_page: https://seedlegals.com/us/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SeedLegals\naid: seedlegals\nurl: https://seedlegals.com/us/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you confirm that you intend to use the Platform and Services in the course of your business, craft, trade\n    or profession.\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: we may run KYC and AML verification checks on your company profile to confirm you are who you say you are\nminimum_age:\n  value: '18'\n  text: you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/seedlegals/eligibility/seedlegals-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from SeedLegals's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Applications
- Legal Tech
- Startups
- Fundraising
- Cap Table
- Equity
- Compliance
- MCP
---
