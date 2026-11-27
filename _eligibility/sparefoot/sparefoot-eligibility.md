---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: you will only use the Service to initiate legitimate Reservations for you or for another person or company for whom you are legally authorized to act
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
name: SpareFoot
provenance_date: '2026-11-10'
provider_name: SpareFoot
provider_slug: sparefoot
slug: sparefoot-eligibility
source_date: '2026-11-10'
source_filename: sparefoot-eligibility.yml
source_heading: Eligibility
source_page: https://www.storable.com/privacy/sparefoot-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SpareFoot\naid: sparefoot\nurl: https://www.storable.com/privacy/sparefoot-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: you will only use the Service to initiate legitimate Reservations for you or for another person or company\n    for whom you are legally authorized to act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/sparefoot/eligibility/sparefoot-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from SpareFoot's own page on 2026-11-10.
synthetic: false
tags:
- Self Storage
- Marketplace
- Storage Unit Listings
- Lead Generation
- Reservations
- Partner Integration
- Data Feed
- Storable
- SiteLink
- storEDGE
---
