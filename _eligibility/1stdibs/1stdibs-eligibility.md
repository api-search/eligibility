---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Many of 1stdibs services, including the Site, are accessible to Sellers, Buyers, and Users outside of the US.
  entity_types:
  - text: Users must be 18 years of age or older to use this Site.
    type: individual
  - text: select trade purchasers may be eligible to participate in the 1stdibs Trade Rewards Program
    type: business
  minimum_age:
    text: Users must be 18 years of age or older to use this Site.
    value: '18'
  restricted_uses:
  - summary: Trade Rewards Program limited to professional designers
    text: The Trade Rewards Program is only intended for and available to professional interior designers and architects who have been accepted into the 1stdibs Trade Rewards Program by 1stdibs in its sole discretion
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Trade Rewards Program is only intended for and available to professional interior designers and architects who have been accepted into the 1stdibs Trade Rewards Program by 1stdibs in its sole discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 1stdibs
provenance_date: '2026-11-09'
provider_name: 1stdibs
provider_slug: 1stdibs
slug: 1stdibs-eligibility
source_date: '2026-11-09'
source_filename: 1stdibs-eligibility.yml
source_heading: Eligibility
source_page: https://www.1stdibs.com/about/user-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1stdibs\naid: 1stdibs\nurl: https://www.1stdibs.com/about/user-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Many of 1stdibs services, including the Site, are accessible to Sellers, Buyers, and Users outside of the\n    US.\nentity_types:\n- type: individual\n  text: Users must be 18 years of age or older to use this Site.\n- type: business\n  text: select trade purchasers may be eligible to participate in the 1stdibs Trade Rewards Program\nrestricted_uses:\n- summary: Trade Rewards Program limited to professional designers\n  text: The Trade Rewards Program is only\
  \ intended for and available to professional interior designers and architects\n    who have been accepted into the 1stdibs Trade Rewards Program by 1stdibs in its sole discretion\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Trade Rewards Program is only intended for and available to professional interior designers and architects\n    who have been accepted into the 1stdibs Trade Rewards Program by 1stdibs in its sole discretion\nminimum_age:\n  value: '18'\n  text: Users must be 18 years of age or older to use this Site.\n"
source_yaml_url: https://artifacts.apis.io/1stdibs/eligibility/1stdibs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from 1stdibs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Marketplace
- Luxury Goods
- E-Commerce
- Furniture
- Art
- Jewelry
- MCP
---
