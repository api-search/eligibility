---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Non-U.S. residents referenced only generally regarding limitations for certain international investors; no countries named.
  minimum_age:
    text: This Platform is intended solely for Users who, if they are a natural person, are eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: Illegal funds for investment
    text: Use any funds derived or obtained from an illegal activity or source to make any investment through the Platform
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Masterworks and any RIA Partner will perform Know Your Customer (" KYC") procedures on all subscribers
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Masterworks
provenance_date: '2026-11-10'
provider_name: Masterworks
provider_slug: masterworks
slug: masterworks-eligibility
source_date: '2026-11-10'
source_filename: masterworks-eligibility.yml
source_heading: Eligibility
source_page: https://www.masterworks.com/about/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Masterworks\naid: masterworks\nurl: https://www.masterworks.com/about/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Non-U.S. residents referenced only generally regarding limitations for certain international investors;\n    no countries named.\nentity_types: []\nrestricted_uses:\n- summary: Illegal funds for investment\n  text: Use any funds derived or obtained from an illegal activity or source to make any investment through the\n    Platform\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Masterworks and any RIA Partner\
  \ will perform Know Your Customer (\" KYC\") procedures on all subscribers\nminimum_age:\n  value: '18'\n  text: This Platform is intended solely for Users who, if they are a natural person, are eighteen (18) years of\n    age or older\n"
source_yaml_url: https://artifacts.apis.io/masterworks/eligibility/masterworks-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Masterworks's own page on 2026-11-10.
synthetic: false
tags:
- Art
- Art Investing
- Alternative Investments
- Fintech
- Investing
- Securities
- Fractional Ownership
- Secondary Market
- Wealth Management
- Regulation A
- GraphQL
---
