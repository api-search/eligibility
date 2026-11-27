---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CO
    text: Los operadores de transporte realizarán el transporte de pedidos exclusivamente dentro del territorio colombiano.
  minimum_age:
    text: Para obtener una cuenta el Usuario debe tener mínimo dieciocho (18) años.
    value: '18'
  restricted_uses:
  - summary: No pyramid schemes or franchise recruitment
    text: Incluir en la Plataforma cualquier derecho de franquicia, esquema de pirámide, membresía a un club o grupo, representación de ventas, agencia comercial o cualquier oportunidad de negocios que requiera un pago anticipado o pagos periódicos, solicitando el reclutamiento de otros miembros, sub-distribuidores o sub-agentes.
  - summary: No false product or user information
    text: Incluir en la Plataforma información falsa, inexacta, incompleta, incorrecta o engañosa.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Branddu examinará la solicitud presentada por el Usuario y se reservará la facultad de verificar los datos comunicados por cada uno de los Usuarios.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Branddu
provenance_date: '2026-11-09'
provider_name: Branddu
provider_slug: branddu
slug: branddu-eligibility
source_date: '2026-11-09'
source_filename: branddu-eligibility.yml
source_heading: Eligibility
source_page: https://branddu.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Branddu\naid: branddu\nurl: https://branddu.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CO\n  excluded: []\n  text: Los operadores de transporte realizarán el transporte de pedidos exclusivamente dentro del territorio colombiano.\nentity_types: []\nrestricted_uses:\n- summary: No pyramid schemes or franchise recruitment\n  text: Incluir en la Plataforma cualquier derecho de franquicia, esquema de pirámide, membresía a un club o grupo,\n    representación de ventas, agencia comercial o cualquier oportunidad de negocios que requiera un pago anticipado\n    o pagos periódicos,\
  \ solicitando el reclutamiento de otros miembros, sub-distribuidores o sub-agentes.\n- summary: No false product or user information\n  text: Incluir en la Plataforma información falsa, inexacta, incompleta, incorrecta o engañosa.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Branddu examinará la solicitud presentada por el Usuario y se reservará la facultad de verificar los datos\n    comunicados por cada uno de los Usuarios.\nminimum_age:\n  value: '18'\n  text: Para obtener una cuenta el Usuario debe tener mínimo dieciocho (18) años.\n"
source_yaml_url: https://artifacts.apis.io/branddu/eligibility/branddu-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Branddu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Merchandising
- Promotional Products
- Procurement
- MerchTech
- E-Commerce
- B2B
- Shopify
- Colombia
---
