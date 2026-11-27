---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: AcreScout is a search and analysis tool for land listed for sale in Canada
  entity_types:
  - text: Accounts are for one person and can be signed in on up to 3 devices at once
    type: individual
  minimum_age:
    text: null
    value: null
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
name: AcreScout
provenance_date: '2026-11-09'
provider_name: AcreScout
provider_slug: acrescout-ca
slug: acrescout-ca-eligibility
source_date: '2026-11-09'
source_filename: acrescout-ca-eligibility.yml
source_heading: Eligibility
source_page: https://acrescout.ca/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AcreScout\naid: acrescout-ca\nurl: https://acrescout.ca/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: AcreScout is a search and analysis tool for land listed for sale in Canada\nentity_types:\n- type: individual\n  text: Accounts are for one person and can be signed in on up to 3 devices at once\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acrescout-ca/eligibility/acrescout-ca-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from AcreScout's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Canada
- Land Listings
- Data Aggregation
- Open Data
---
