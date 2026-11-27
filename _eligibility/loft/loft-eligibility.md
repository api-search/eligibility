---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: impulsionando o setor em todo o Brasil
  entity_types:
  - text: Esse selo tem a única e exclusiva finalidade de certificar que a Imobiliária é parceira da LOFT
    type: business
  minimum_age:
    text: deve ser maior de 18 anos e ter poderes de representação do PARCEIRO
    value: '18'
  restricted_uses:
  - summary: Loft seal restricted to accepting partners
    text: sendo vedado o uso por terceiros ou por PARCEIROS que não tenham aceitado estes T&C
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: desde que a LOFT aprove as informações de cadastro.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Loft
provenance_date: '2026-11-09'
provider_name: Loft
provider_slug: loft
slug: loft-eligibility
source_date: '2026-11-09'
source_filename: loft-eligibility.yml
source_heading: Eligibility
source_page: https://loft.com.br/institucional/termos-e-condicoes-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loft\naid: loft\nurl: https://loft.com.br/institucional/termos-e-condicoes-de-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: impulsionando o setor em todo o Brasil\nentity_types:\n- type: business\n  text: Esse selo tem a única e exclusiva finalidade de certificar que a Imobiliária é parceira da LOFT\nrestricted_uses:\n- summary: Loft seal restricted to accepting partners\n  text: sendo vedado o uso por terceiros ou por PARCEIROS que não tenham aceitado estes T&C\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: desde que a LOFT aprove as informações\
  \ de cadastro.\nminimum_age:\n  value: '18'\n  text: deve ser maior de 18 anos e ter poderes de representação do PARCEIRO\n"
source_yaml_url: https://artifacts.apis.io/loft/eligibility/loft-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Loft's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Fintech
- Marketplace
- Brazil
- Property Management
- CRM
---
