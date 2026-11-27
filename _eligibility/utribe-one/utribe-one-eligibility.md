---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - KP
    - CU
    - BY
    - RU
    - MM
    served: []
    text: 'The following jurisdictions are subject to comprehensive sanctions and access to the Services from these jurisdictions is prohibited: Iran North Korea (Democratic People''s Republic of Korea) Cuba Crimea, Donetsk, Luhansk, Kherson, and Zaporizhzhia regions of Ukraine Belarus Russian Federation Myanmar (Burma)'
  entity_types:
  - text: 'To use the Services, you must: Be at least 18 years old'
    type: individual
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: Not use the Services on behalf of any person or entity subject to sanctions
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Complete identity verification (KYC) as required
excluded_countries:
- IR
- KP
- CU
- BY
- RU
- MM
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ubuntu
provenance_date: '2026-11-10'
provider_name: Ubuntu
provider_slug: utribe-one
slug: utribe-one-eligibility
source_date: '2026-11-10'
source_filename: utribe-one-eligibility.yml
source_heading: Eligibility
source_page: https://utribe.one/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ubuntu\naid: utribe-one\nurl: https://utribe.one/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - IR\n  - KP\n  - CU\n  - BY\n  - RU\n  - MM\n  text: 'The following jurisdictions are subject to comprehensive sanctions and access to the Services from these\n    jurisdictions is prohibited: Iran North Korea (Democratic People''s Republic of Korea) Cuba Crimea, Donetsk,\n    Luhansk, Kherson, and Zaporizhzhia regions of Ukraine Belarus Russian Federation Myanmar (Burma)'\nentity_types:\n- type: individual\n  text: 'To use the Services, you must: Be at\
  \ least 18 years old'\nrestricted_uses:\n- summary: Sanctioned persons\n  text: Not use the Services on behalf of any person or entity subject to sanctions\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Complete identity verification (KYC) as required\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/utribe-one/eligibility/utribe-one-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Ubuntu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Gold-Backed Tokens
- Digital Payments
- Cryptocurrency Alternative
---
