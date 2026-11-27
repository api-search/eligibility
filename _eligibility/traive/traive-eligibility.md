---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: O page names Brasil as the País (República Federativa do Brasil) but does not state a list of served or excluded countries.
  entity_types:
  - text: Caso seja pessoa física, você declara ser maior de 18 (dezoito) anos e possuir todas as capacidades legais necessárias para utilizar os Serviços fornecidos na Plataforma.
    type: individual
  - text: Caso seja pessoa jurídica, você declara estar devidamente registrado no Cadastro Nacional da Pessoa Jurídica (CNPJ) perante a Receita Federal.
    type: business
  minimum_age:
    text: Caso seja pessoa física, você declara ser maior de 18 (dezoito) anos
    value: '18'
  restricted_uses:
  - summary: No direct dealings bypassing Traive
    text: O Usuário compromete-se a não contornar a Plataforma e a Traive para realizar transações diretamente com outros Usuários da Plataforma
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A Traive poderá, a qualquer tempo e a seu único critério, solicitar o envio de documentação extraordinária para validação de sua conta.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Traive
provenance_date: '2026-11-10'
provider_name: Traive
provider_slug: traive
slug: traive-eligibility
source_date: '2026-11-10'
source_filename: traive-eligibility.yml
source_heading: Eligibility
source_page: https://traive.com.br/termos-e-condicoes-de-uso/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Traive\naid: traive\nurl: https://traive.com.br/termos-e-condicoes-de-uso/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: O page names Brasil as the País (República Federativa do Brasil) but does not state a list of served or\n    excluded countries.\nentity_types:\n- type: individual\n  text: Caso seja pessoa física, você declara ser maior de 18 (dezoito) anos e possuir todas as capacidades legais\n    necessárias para utilizar os Serviços fornecidos na Plataforma.\n- type: business\n  text: Caso seja pessoa jurídica, você declara estar devidamente registrado no Cadastro Nacional\
  \ da Pessoa Jurídica\n    (CNPJ) perante a Receita Federal.\nrestricted_uses:\n- summary: No direct dealings bypassing Traive\n  text: O Usuário compromete-se a não contornar a Plataforma e a Traive para realizar transações diretamente com\n    outros Usuários da Plataforma\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A Traive poderá, a qualquer tempo e a seu único critério, solicitar o envio de documentação extraordinária\n    para validação de sua conta.\nminimum_age:\n  value: '18'\n  text: Caso seja pessoa física, você declara ser maior de 18 (dezoito) anos\n"
source_yaml_url: https://artifacts.apis.io/traive/eligibility/traive-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Traive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agriculture
- Fintech
- Credit
- Risk Analysis
- Lending
- AgTech
- Brazil
- Artificial Intelligence
- Data
---
