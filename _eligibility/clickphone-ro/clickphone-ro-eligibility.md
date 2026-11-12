---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Utilizatorul persoana fizică trebuie să vorbească limba română pentru a putea folosi serviciile ClickPhone.
    type: individual
  - text: ClickPhone este serviciul de telefonie cloud pentru companii operat de Caro Network SRL
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud and illegal activity
    text: Să desfasoare activități frauduloase prin intermediul serviciilor furnizate de către CARO Network
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: La crearea unui cont nou, pentru alocarea numărului de telefon fix, CARO Network va solicita utilizatorilor o dovadă prin care să ateste corectitudinea datelor transmise
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClickPhone
provenance_date: '2026-11-09'
provider_name: ClickPhone
provider_slug: clickphone-ro
slug: clickphone-ro-eligibility
source_date: '2026-11-09'
source_filename: clickphone-ro-eligibility.yml
source_heading: Eligibility
source_page: https://www.clickphone.ro/termeni_conditii.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClickPhone\naid: clickphone-ro\nurl: https://www.clickphone.ro/termeni_conditii.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Utilizatorul persoana fizică trebuie să vorbească limba română pentru a putea folosi serviciile ClickPhone.\n- type: business\n  text: ClickPhone este serviciul de telefonie cloud pentru companii operat de Caro Network SRL\nrestricted_uses:\n- summary: Fraud and illegal activity\n  text: Să desfasoare activități frauduloase prin intermediul serviciilor furnizate de către CARO Network\nverification:\n\
  \  kyc: true\n  kyb: null\n  approval_required: null\n  text: La crearea unui cont nou, pentru alocarea numărului de telefon fix, CARO Network va solicita utilizatorilor\n    o dovadă prin care să ateste corectitudinea datelor transmise\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clickphone-ro/eligibility/clickphone-ro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from ClickPhone's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telecommunications
- VoIP
- Cloud PBX
- SIP Trunk
- SMS
- Call Center
- MCP
- Romania
---
