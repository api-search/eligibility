---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: This Website is offered and available to users who are 13 years of age or older and reside in the United States or any of its territories or possessions.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Arro
provenance_date: '2026-11-09'
provider_name: Arro
provider_slug: arro
slug: arro-eligibility
source_date: '2026-11-09'
source_filename: arro-eligibility.yml
source_heading: Eligibility
source_page: https://app.arrofinance.com/terms-of-use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arro\naid: arro\nurl: https://app.arrofinance.com/terms-of-use.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 13 years of age or older and reside in the United\n    States or any of its territories or possessions.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Website is offered and available to users who are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/arro/eligibility/arro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Credit
- Credit Cards
- Consumer Lending
- Credit Building
---
