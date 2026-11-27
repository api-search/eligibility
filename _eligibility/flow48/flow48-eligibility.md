---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - ZA
    text: Flow48 provides fast, flexible business funding for South African SMEs.
  entity_types:
  - text: If you are accessing the Services on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms of Use
    type: business
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
name: Flow48
provenance_date: '2026-11-09'
provider_name: Flow48
provider_slug: flow48
slug: flow48-eligibility
source_date: '2026-11-09'
source_filename: flow48-eligibility.yml
source_heading: Eligibility
source_page: https://www.flow48.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flow48\naid: flow48\nurl: https://www.flow48.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - ZA\n  excluded: []\n  text: Flow48 provides fast, flexible business funding for South African SMEs.\nentity_types:\n- type: business\n  text: If you are accessing the Services on behalf of a company or other legal entity, you represent and warrant\n    that you have the authority to bind that entity to these Terms of Use\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flow48/eligibility/flow48-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Flow48's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Embedded Finance
- SME Lending
- Revenue-Based Financing
- Invoice Financing
- MENA
- Speedinvest Portfolio
---
