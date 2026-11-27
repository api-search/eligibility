---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: A Babá Certa é o app brasileiro de babás verificadas
  entity_types:
  - text: A plataforma é destinada a pessoas reais, atuando em nome próprio
    type: individual
  minimum_age:
    text: Para criar conta, família ou babá, é preciso ter 18 anos completos
    value: '18'
  restricted_uses:
  - summary: No agency or recruiting use
    text: É proibido usar a Babá Certa como agência, recrutadora, intermediadora, representante
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Famílias devem validar e-mail, WhatsApp, CPF e biometria/prova de vida antes de publicar vaga ativa
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Babá Certa
provenance_date: '2026-11-09'
provider_name: Babá Certa
provider_slug: babacerta-com-br
slug: babacerta-com-br-eligibility
source_date: '2026-11-09'
source_filename: babacerta-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://babacerta.com.br/termos-de-uso/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Babá Certa\naid: babacerta-com-br\nurl: https://babacerta.com.br/termos-de-uso/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: A Babá Certa é o app brasileiro de babás verificadas\nentity_types:\n- type: individual\n  text: A plataforma é destinada a pessoas reais, atuando em nome próprio\nrestricted_uses:\n- summary: No agency or recruiting use\n  text: É proibido usar a Babá Certa como agência, recrutadora, intermediadora, representante\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Famílias devem validar e-mail, WhatsApp, CPF e biometria/prova\
  \ de vida antes de publicar vaga ativa\nminimum_age:\n  value: '18'\n  text: Para criar conta, família ou babá, é preciso ter 18 anos completos\n"
source_yaml_url: https://artifacts.apis.io/babacerta-com-br/eligibility/babacerta-com-br-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Babá Certa's own page on 2026-11-09.
synthetic: false
tags:
- Babysitting
- Marketplace
- Verification
- Brazil
- Childcare
---
