---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: This Site is directed to people residing in the United Kingdom. We do not represent that the content available on or through this Site is appropriate for use or available in other locations.
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
name: Kennek
provenance_date: '2026-11-09'
provider_name: Kennek
provider_slug: kennek
slug: kennek-eligibility
source_date: '2026-11-09'
source_filename: kennek-eligibility.yml
source_heading: Eligibility
source_page: https://kennek.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kennek\naid: kennek\nurl: https://kennek.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: This Site is directed to people residing in the United Kingdom. We do not represent that the content available\n    on or through this Site is appropriate for use or available in other locations.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kennek/eligibility/kennek-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Kennek's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Loan Management
- Loan Servicing
- Loan Origination
- Financial Services
- Software-as-a-Service
---
