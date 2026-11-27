---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You agree to use the Sites and Services for your personal, private non-commercial use only.
    type: individual
  - text: Real estate professionals and/or businesses may only provide information to consumers via the Services or, where authorized, take actions on behalf of a consumer (e.g. list a home for sale, post information in business listings, etc.) upon the purchase of an appropriate subscription from 99 Group
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use without subscription
    text: Without a current and valid subscription purchased from 99 Group, you shall not use the Sites, the Services or any content, data, valuation, estimate, report, listing, image or other output obtained from or through the Sites or the Services for any commercial, business, professional, advisory, research, resale, redistribution, syndication, marketing or revenue-generating purpose whatsoever.
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
name: 99.co
provenance_date: '2026-11-09'
provider_name: 99.co
provider_slug: 99co
slug: 99co-eligibility
source_date: '2026-11-09'
source_filename: 99co-eligibility.yml
source_heading: Eligibility
source_page: https://www.99.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 99.co\naid: 99co\nurl: https://www.99.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You agree to use the Sites and Services for your personal, private non-commercial use only.\n- type: business\n  text: Real estate professionals and/or businesses may only provide information to consumers via the Services or,\n    where authorized, take actions on behalf of a consumer (e.g. list a home for sale, post information in business\n    listings, etc.) upon the purchase of an appropriate subscription from 99 Group\nrestricted_uses:\n\
  - summary: Commercial use without subscription\n  text: Without a current and valid subscription purchased from 99 Group, you shall not use the Sites, the Services\n    or any content, data, valuation, estimate, report, listing, image or other output obtained from or through the\n    Sites or the Services for any commercial, business, professional, advisory, research, resale, redistribution,\n    syndication, marketing or revenue-generating purpose whatsoever.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/99co/eligibility/99co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from 99.co's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Property Listings
- Real Estate Marketplace
- Property Search
- Singapore
- Indonesia
- Housing
---
