---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: no todos los Servicios y Contenidos están disponibles en todas las áreas geográficas de la República Mexicana
  entity_types:
  - text: Cualquier persona física o moral, está última a través de su representante o persona autorizada, que acceda al Portal y servicio de Banca por Internet de Banco Covalto.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use only
    text: El Portal y el servicio de Banca por Internet es para el uso personal del Usuario
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
name: Covalto
provenance_date: '2026-11-09'
provider_name: Covalto
provider_slug: covalto
slug: covalto-eligibility
source_date: '2026-11-09'
source_filename: covalto-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/6943e39b4d24698bfcffdd87/69aa9027022514e9b97de74e_Covalto%20Te%CC%81rminos%20y%20Condiciones%20Banca%20por%20Internet.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Covalto\naid: covalto\nurl: https://cdn.prod.website-files.com/6943e39b4d24698bfcffdd87/69aa9027022514e9b97de74e_Covalto%20Te%CC%81rminos%20y%20Condiciones%20Banca%20por%20Internet.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: no todos los Servicios y Contenidos están disponibles en todas las áreas geográficas de la República Mexicana\nentity_types:\n- type: individual\n  text: Cualquier persona física o moral, está última a través de su representante o persona autorizada, que acceda\n    al Portal y servicio de Banca por Internet de Banco Covalto.\nrestricted_uses:\n\
  - summary: Personal use only\n  text: El Portal y el servicio de Banca por Internet es para el uso personal del Usuario\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/covalto/eligibility/covalto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Covalto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Mexico
- Fintech
- SME Lending
- Digital Bank
- Factoring
- Leasing
- Business Accounts
- Investment
---
