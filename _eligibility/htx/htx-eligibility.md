---
api_specs:
- filename: htx-websocket-asyncapi.yml
  format: yaml
  label: HTX Spot REST API
  slug: htx-spot-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/htx/asyncapi/htx-websocket-asyncapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CN
    - US
    - CU
    - IR
    - KP
    - SD
    - SY
    - VE
    - HK
    - GB
    - SG
    - MM
    - RU
    - BD
    - BO
    - EC
    - IL
    - IQ
    - KG
    - NZ
    - TW
    served: []
    text: 'USERS FROM THE FOLLOWING JURISDICTIONS ARE PROHIBITED FROM USING ALL SERVICES: MAINLAND CHINA, THE UNITED STATES OF AMERICA, CUBA, IRAN, NORTH KOREA, SUDAN, SYRIA, VENEZUELA, HONG KONG CHINA, THE UNITED KINGDOM, SINGAPORE, MYANMAR, CRIMEA, DONETSK, LUHANSK, KHERSON, ZAPORIZHZHIA, SEVASTOPOL, THE RUSSIAN FEDERATION AND ALL MEMBER STATES OF THE EUROPEAN UNION (EU)'
  entity_types:
  - text: To be eligible to create an Account, you confirm that you are a natural person, a legal person or any other entity with the authority to enter into this agreement
    type: individual
  - text: a legal person or any other entity with the authority to enter into this agreement
    type: business
  minimum_age:
    text: you are of statutory age, have the capacity and are authorised to enter into this Agreement
    value: null
  restricted_uses:
  - summary: Derivatives trading restricted in listed jurisdictions
    text: 'USERS FROM THE FOLLOWING JURISDICTIONS ARE PROHIBITED FROM TRADING IN DERIVATIVES: TAIWAN CHINA, ISRAEL, IRAQ, BANGLADESH, BOLIVIA, ECUADOR, KYRGYZSTAN AND NEW ZEALAND.'
  - summary: Sanctioned persons and countries
    text: 'You are not permitted to acquire Digital Assets or use any of the Services if: you are located in, under the control of, or a national or resident of any country or territory subject to comprehensive or broad-based economic sanctions'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CN
- US
- CU
- IR
- KP
- SD
- SY
- VE
- HK
- GB
- SG
- MM
- RU
- BD
- BO
- EC
- IL
- IQ
- KG
- NZ
- TW
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HTX
provenance_date: '2026-11-09'
provider_name: HTX
provider_slug: htx
slug: htx-eligibility
source_date: '2026-11-09'
source_filename: htx-eligibility.yml
source_heading: Eligibility
source_page: https://www.htx.com/support/360000298561/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HTX\naid: htx\nurl: https://www.htx.com/support/360000298561/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CN\n  - US\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  - VE\n  - HK\n  - GB\n  - SG\n  - MM\n  - RU\n  - BD\n  - BO\n  - EC\n  - IL\n  - IQ\n  - KG\n  - NZ\n  - TW\n  text: 'USERS FROM THE FOLLOWING JURISDICTIONS ARE PROHIBITED FROM USING ALL SERVICES: MAINLAND CHINA, THE UNITED\n    STATES OF AMERICA, CUBA, IRAN, NORTH KOREA, SUDAN, SYRIA, VENEZUELA, HONG KONG CHINA, THE UNITED KINGDOM, SINGAPORE,\n    MYANMAR, CRIMEA, DONETSK, LUHANSK, KHERSON, ZAPORIZHZHIA,\
  \ SEVASTOPOL, THE RUSSIAN FEDERATION AND ALL MEMBER\n    STATES OF THE EUROPEAN UNION (EU)'\nentity_types:\n- type: individual\n  text: To be eligible to create an Account, you confirm that you are a natural person, a legal person or any other\n    entity with the authority to enter into this agreement\n- type: business\n  text: a legal person or any other entity with the authority to enter into this agreement\nrestricted_uses:\n- summary: Derivatives trading restricted in listed jurisdictions\n  text: 'USERS FROM THE FOLLOWING JURISDICTIONS ARE PROHIBITED FROM TRADING IN DERIVATIVES: TAIWAN CHINA, ISRAEL,\n    IRAQ, BANGLADESH, BOLIVIA, ECUADOR, KYRGYZSTAN AND NEW ZEALAND.'\n- summary: Sanctioned persons and countries\n  text: 'You are not permitted to acquire Digital Assets or use any of the Services if: you are located in, under\n    the control of, or a national or resident of any country or territory subject to comprehensive or broad-based\n    economic sanctions'\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of statutory age, have the capacity and are authorised to enter into this Agreement\n"
source_yaml_url: https://artifacts.apis.io/htx/eligibility/htx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from HTX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Technology
- Cryptocurrency
- Cryptocurrency Exchange
- Trading
- Digital Assets
- Blockchain
- Financial Services
- Market Data
- WebSocket
---
