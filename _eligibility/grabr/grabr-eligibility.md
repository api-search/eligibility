---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Payment services may not be used to send or receive funds into United States embargoed countries.
  entity_types:
  - text: Access to and use of the Grabr Platform is available only to individuals who are at least 18 years old, who can form legally binding contracts under applicable law
    type: individual
  minimum_age:
    text: at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited items
    text: Shoppers shall not request Prohibited Grab'd Items.
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
name: Grabr
provenance_date: '2026-11-09'
provider_name: Grabr
provider_slug: grabr
slug: grabr-eligibility
source_date: '2026-11-09'
source_filename: grabr-eligibility.yml
source_heading: Eligibility
source_page: https://grabr.io/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grabr\naid: grabr\nurl: https://grabr.io/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Payment services may not be used to send or receive funds into United States embargoed countries.\nentity_types:\n- type: individual\n  text: Access to and use of the Grabr Platform is available only to individuals who are at least 18 years old,\n    who can form legally binding contracts under applicable law\nrestricted_uses:\n- summary: Prohibited items\n  text: Shoppers shall not request Prohibited Grab'd Items.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/grabr/eligibility/grabr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Grabr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Cross-Border Commerce
- Peer-to-Peer
- Shopping
- Delivery
- Travel
- Fintech
- Consumer
---
