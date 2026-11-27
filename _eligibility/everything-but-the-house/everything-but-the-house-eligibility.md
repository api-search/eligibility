---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: When purchasing Items on EBTH , you attest that you do not reside in any banned country and that you are not, and are not affiliated with, any such banned organizations, businesses, or individuals.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Resale or export of purchased items
    text: You represent and warrant that your purchase of Buy Now Items is for personal or household use only, and not for resale or export in violation of any laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: EBTH requires Users to maintain valid and updated payment information on file.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Everything But The House
provenance_date: '2026-11-09'
provider_name: Everything But The House
provider_slug: everything-but-the-house
slug: everything-but-the-house-eligibility
source_date: '2026-11-09'
source_filename: everything-but-the-house-eligibility.yml
source_heading: Eligibility
source_page: https://www.ebth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everything But The House\naid: everything-but-the-house\nurl: https://www.ebth.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: When purchasing Items on EBTH , you attest that you do not reside in any banned country and that you are\n    not, and are not affiliated with, any such banned organizations, businesses, or individuals.\nentity_types: []\nrestricted_uses:\n- summary: Resale or export of purchased items\n  text: You represent and warrant that your purchase of Buy Now Items is for personal or household use only, and\n    not for resale or export\
  \ in violation of any laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: EBTH requires Users to maintain valid and updated payment information on file.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/everything-but-the-house/eligibility/everything-but-the-house-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Everything But The House's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Auctions
- E-Commerce
- Estate Sales
- Consignment
- Antiques
- Collectibles
- Art
- Jewelry
- Retail
- Secondary Market
---
