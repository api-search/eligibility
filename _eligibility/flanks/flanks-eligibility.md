---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Website is accessible to Users worldwide.
  entity_types:
  - text: By accessing or using the Website, individuals are considered users
    type: individual
  minimum_age:
    text: Users must be of legal age and have the necessary legal capacity to be bound by these Terms.
    value: legal age
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
name: Flanks
provenance_date: '2026-11-09'
provider_name: Flanks
provider_slug: flanks
slug: flanks-eligibility
source_date: '2026-11-09'
source_filename: flanks-eligibility.yml
source_heading: Eligibility
source_page: https://www.flanks.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flanks\naid: flanks\nurl: https://www.flanks.io/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Website is accessible to Users worldwide.\nentity_types:\n- type: individual\n  text: By accessing or using the Website, individuals are considered users\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: Users must be of legal age and have the necessary legal capacity to be bound by these Terms.\n"
source_yaml_url: https://artifacts.apis.io/flanks/eligibility/flanks-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Flanks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wealth Management
- Financial Data
- Data Aggregation
- Fintech
- Investment
- Open Banking
---
