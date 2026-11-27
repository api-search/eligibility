---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Estes Termos de Uso são válidos e aplicáveis ao acesso da Plataforma, dentro ou fora do Brasil
  entity_types:
  - text: 'Usuário: pessoa física que se cadastra na Plataforma e que tem o seu registro efetivado pela Plataforma.'
    type: individual
  minimum_age:
    text: você declara ter (i) no mínimo 18 (dezoito) anos de idade
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
name: Justos
provenance_date: '2026-11-09'
provider_name: Justos
provider_slug: justos
slug: justos-eligibility
source_date: '2026-11-09'
source_filename: justos-eligibility.yml
source_heading: Eligibility
source_page: https://www.justos.com.br/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Justos\naid: justos\nurl: https://www.justos.com.br/termos-de-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Estes Termos de Uso são válidos e aplicáveis ao acesso da Plataforma, dentro ou fora do Brasil\nentity_types:\n- type: individual\n  text: 'Usuário: pessoa física que se cadastra na Plataforma e que tem o seu registro efetivado pela Plataforma.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: você declara ter (i) no mínimo 18 (dezoito) anos de idade\n"
source_yaml_url: https://artifacts.apis.io/justos/eligibility/justos-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Justos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Auto Insurance
- Telematics
- Usage-Based Insurance
- Brazil
- MGA
---
