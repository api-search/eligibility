---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    - LB
    served: []
    text: a country or region that is subject to comprehensive economic and/or trade sanctions imposed by Israel or the United States (currently Cuba, Crimea, North Korea, Iran, Syria, Lebanon, and the Crimea, Donetsk and Luhansk Provinces of Ukraine)
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Anti-money laundering and anti-bribery compliance
    text: Customer warrants and represents that it does not conduct its business in a manner that violates anti-money laundering or counter-terror financing laws
  - summary: Sanctions compliance warranty
    text: Customer warrants that neither it nor any person(s) that own(s), individually or collectively, or controls it is (a) subject to economic sanctions imposed by the United States, European Union or the United Kingdom
  - summary: Lawful use only
    text: Customer shall not use the Platform or Services in a manner which is unlawful, harmful, threatening, abusive, harassing, tortious, indecent, obscene, libelous or menacing
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
- LB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ThetaRay
provenance_date: '2026-11-10'
provider_name: ThetaRay
provider_slug: thetaray
slug: thetaray-eligibility
source_date: '2026-11-10'
source_filename: thetaray-eligibility.yml
source_heading: Eligibility
source_page: https://thetaray.com/website-terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ThetaRay\naid: thetaray\nurl: https://thetaray.com/website-terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  - LB\n  text: a country or region that is subject to comprehensive economic and/or trade sanctions imposed by Israel or\n    the United States (currently Cuba, Crimea, North Korea, Iran, Syria, Lebanon, and the Crimea, Donetsk and Luhansk\n    Provinces of Ukraine)\nentity_types: []\nrestricted_uses:\n- summary: Anti-money laundering and anti-bribery compliance\n  text: Customer warrants and represents that it does not conduct its business\
  \ in a manner that violates anti-money\n    laundering or counter-terror financing laws\n- summary: Sanctions compliance warranty\n  text: Customer warrants that neither it nor any person(s) that own(s), individually or collectively, or controls\n    it is (a) subject to economic sanctions imposed by the United States, European Union or the United Kingdom\n- summary: Lawful use only\n  text: Customer shall not use the Platform or Services in a manner which is unlawful, harmful, threatening, abusive,\n    harassing, tortious, indecent, obscene, libelous or menacing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thetaray/eligibility/thetaray-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 4 quoted statements, read from ThetaRay's own page on 2026-11-10.
synthetic: false
tags:
- AML
- Financial Crime
- Transaction Monitoring
- Sanctions Screening
- KYC
- RegTech
- Risk Assessment
- Artificial Intelligence
- Banking
- Fintech
- Payments
- Compliance
- MCP
---
