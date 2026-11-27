---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - CA
    - NZ
    - US
    - GB
    text: Our Services are intended to be utilized throughout Australia, Canada (except the provinces of Saskatchewan and Quebec), New Zealand, the United States and the United Kingdom (where they are accessed from the United Kingdom).
  entity_types:
  - text: The Services are intended solely for businesses with recurring revenues that are based in Australia, Canada, (except the provinces of Saskatchewan or Quebec), New Zealand, the United States, or the United Kingdom
    type: business
  - text: The Services are not intended for consumers or for personal, family, or household use.
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
name: Pipe
provenance_date: '2026-11-10'
provider_name: Pipe
provider_slug: pipe
slug: pipe-eligibility
source_date: '2026-11-10'
source_filename: pipe-eligibility.yml
source_heading: Eligibility
source_page: https://pipe.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pipe\naid: pipe\nurl: https://pipe.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AU\n  - CA\n  - NZ\n  - US\n  - GB\n  excluded: []\n  text: Our Services are intended to be utilized throughout Australia, Canada (except the provinces of Saskatchewan\n    and Quebec), New Zealand, the United States and the United Kingdom (where they are accessed from the United\n    Kingdom).\nentity_types:\n- type: business\n  text: The Services are intended solely for businesses with recurring revenues that are based in Australia, Canada,\n    (except the provinces of Saskatchewan\
  \ or Quebec), New Zealand, the United States, or the United Kingdom\n- type: individual\n  text: The Services are not intended for consumers or for personal, family, or household use.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pipe/eligibility/pipe-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from Pipe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Embedded Finance
- Capital
- Lending
- Payments
- Cash Flow
- Small Business
- Embedded Financial Services
---
