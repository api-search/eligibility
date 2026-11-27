---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The listing content on this website is protected by copyright and other laws, and is intended solely for the private, non-commercial use by individuals.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: bona fide interest required
    text: Users must have a bona fide interest in the purchase, sale, or lease of real estate of the type being offered through this VOW.
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
name: HouseSigma
provenance_date: '2026-11-09'
provider_name: HouseSigma
provider_slug: housesigma
slug: housesigma-eligibility
source_date: '2026-11-09'
source_filename: housesigma-eligibility.yml
source_heading: Eligibility
source_page: https://housesigma.com/blog-en/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HouseSigma\naid: housesigma\nurl: https://housesigma.com/blog-en/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The listing content on this website is protected by copyright and other laws, and is intended solely for\n    the private, non-commercial use by individuals.\nrestricted_uses:\n- summary: bona fide interest required\n  text: Users must have a bona fide interest in the purchase, sale, or lease of real estate of the type being offered\n    through this VOW.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/housesigma/eligibility/housesigma-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from HouseSigma's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Canada
- Property Listings
- MLS
- Valuation
- AVM
- PropTech
- Rentals
- Blog
- Content
- WordPress
- oEmbed
- Ontario
- British Columbia
- Toronto
---
