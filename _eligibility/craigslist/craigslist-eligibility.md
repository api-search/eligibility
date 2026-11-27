---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you agree to the TOU and (1) are of sufficient age and capacity to use CL and be bound by the TOU
    type: individual
  - text: use CL on behalf of a business, thereby binding that business to the TOU
    type: business
  minimum_age:
    text: are of sufficient age and capacity to use CL and be bound by the TOU
    value: null
  restricted_uses:
  - summary: Misleading, unsolicited or unlawful postings and accounts
    text: Misleading, unsolicited, and/or unlawful postings/communications/accounts are prohibited, as is buying or selling accounts.
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
name: Craigslist
provenance_date: '2026-11-09'
provider_name: Craigslist
provider_slug: craigslist
slug: craigslist-eligibility
source_date: '2026-11-09'
source_filename: craigslist-eligibility.yml
source_heading: Eligibility
source_page: https://www.craigslist.org/about/terms.of.use/en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Craigslist\naid: craigslist\nurl: https://www.craigslist.org/about/terms.of.use/en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you agree to the TOU and (1) are of sufficient age and capacity to use CL and be bound by the TOU\n- type: business\n  text: use CL on behalf of a business, thereby binding that business to the TOU\nrestricted_uses:\n- summary: Misleading, unsolicited or unlawful postings and accounts\n  text: Misleading, unsolicited, and/or unlawful postings/communications/accounts are prohibited, as is buying or\n\
  \    selling accounts.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: are of sufficient age and capacity to use CL and be bound by the TOU\n"
source_yaml_url: https://artifacts.apis.io/craigslist/eligibility/craigslist-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Craigslist's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Classifieds
- Marketplace
- Job
- Housing
- Community
---
