---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: A Cartena é uma plataforma desenvolvida para auxiliar investidores brasileiros na gestão e acompanhamento de suas carteiras de investimento de forma organizada e intuitiva.
  entity_types:
  - text: Tem pelo menos 18 anos de idade
    type: individual
  minimum_age:
    text: Tem pelo menos 18 anos de idade
    value: '18'
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
name: Cartena
provenance_date: '2026-11-09'
provider_name: Cartena
provider_slug: cartena-com-br
slug: cartena-com-br-eligibility
source_date: '2026-11-09'
source_filename: cartena-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://cartena.com.br/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cartena\naid: cartena-com-br\nurl: https://cartena.com.br/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: A Cartena é uma plataforma desenvolvida para auxiliar investidores brasileiros na gestão e acompanhamento\n    de suas carteiras de investimento de forma organizada e intuitiva.\nentity_types:\n- type: individual\n  text: Tem pelo menos 18 anos de idade\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Tem pelo menos 18 anos de idade\n"
source_yaml_url: https://artifacts.apis.io/cartena-com-br/eligibility/cartena-com-br-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Cartena's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Investment
- Portfolio
- Dividends
- Brazil
---
