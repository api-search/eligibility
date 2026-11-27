---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: A Contratante poderá utilizar a Plataforma Lais exclusivamente no Brasil
  entity_types:
  - text: o faturamento permanecerá vinculado exclusivamente ao número de CNPJ informado no ato da contratação
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use or infringement
    text: usar ou permitir o uso da Lais para qualquer finalidade ilícita ou para infringir direitos de terceiros
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
name: Lastro
provenance_date: '2026-11-09'
provider_name: Lastro
provider_slug: lastro
slug: lastro-eligibility
source_date: '2026-11-09'
source_filename: lastro-eligibility.yml
source_heading: Eligibility
source_page: https://www.lastro.co/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lastro\naid: lastro\nurl: https://www.lastro.co/termos-de-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: A Contratante poderá utilizar a Plataforma Lais exclusivamente no Brasil\nentity_types:\n- type: business\n  text: o faturamento permanecerá vinculado exclusivamente ao número de CNPJ informado no ato da contratação\nrestricted_uses:\n- summary: Illegal use or infringement\n  text: usar ou permitir o uso da Lais para qualquer finalidade ilícita ou para infringir direitos de terceiros\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lastro/eligibility/lastro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Lastro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Artificial Intelligence
- Brazil
- Lead Management
- Conversational AI
- WhatsApp
---
