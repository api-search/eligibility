---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: our brokerage service can only help UK residents, and we can only help you buy properties registered in the UK.
  entity_types:
  - text: If you’d like to get a mortgage in a company’s name, we can help you get a buy-to-let mortgage, but not a residential mortgage.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Properties outside UK
    text: You’re applying for a mortgage we can’t help you get – for example, it’s for a property outside the UK.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We’re unable to complete our identity verification, anti-money laundering, or financial crime checks satisfactorily.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Habito
provenance_date: '2026-11-09'
provider_name: Habito
provider_slug: habito
slug: habito-eligibility
source_date: '2026-11-09'
source_filename: habito-eligibility.yml
source_heading: Eligibility
source_page: https://www.habito.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Habito\naid: habito\nurl: https://www.habito.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: our brokerage service can only help UK residents, and we can only help you buy properties registered in\n    the UK.\nentity_types:\n- type: business\n  text: If you’d like to get a mortgage in a company’s name, we can help you get a buy-to-let mortgage, but not\n    a residential mortgage.\nrestricted_uses:\n- summary: Properties outside UK\n  text: You’re applying for a mortgage we can’t help you get – for example, it’s for a property outside the UK.\nverification:\n  kyc:\
  \ true\n  kyb: null\n  approval_required: null\n  text: We’re unable to complete our identity verification, anti-money laundering, or financial crime checks satisfactorily.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/habito/eligibility/habito-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Habito's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Mortgage
- Lending
- Financial Services
- Real Estate
- Home Buying
- United Kingdom
---
