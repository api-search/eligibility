---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you represent a business, any advertising, marketing, privacy, or other self-regulatory code(s) applicable to your industry
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: DFS will verify and approve all registrants in accordance with its standard verification procedures.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Discover
provenance_date: '2026-11-09'
provider_name: Discover
provider_slug: discover
slug: discover-eligibility
source_date: '2026-11-09'
source_filename: discover-eligibility.yml
source_heading: Eligibility
source_page: https://www.discoverglobalnetwork.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Discover\naid: discover\nurl: https://www.discoverglobalnetwork.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you represent a business, any advertising, marketing, privacy, or other self-regulatory code(s) applicable\n    to your industry\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: DFS will verify and approve all registrants in accordance with its standard verification procedures.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/discover/eligibility/discover-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Discover's own page on 2026-11-09.
synthetic: false
tags:
- Credit Cards
- Payments
- Card Network
- Tokenization
- Financial Services
- Fraud Prevention
- Fortune 500
---
