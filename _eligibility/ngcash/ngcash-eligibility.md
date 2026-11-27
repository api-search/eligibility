---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: os nossos Serviços são oferecidos apenas no Brasil
  entity_types:
  - text: Para se cadastrar, você deve compartilhar conosco um conjunto de dados pessoais, bem como, uma selfie para verificação e validação da sua identidade
    type: individual
  - text: Caso você seja menor de 18 (dezoito) anos, você poderá utilizar a NG.CASH, desde que com a autorização e supervisão dos seus pais ou responsáveis legais.
    type: other
  minimum_age:
    text: Caso você seja menor de 18 (dezoito) anos, você poderá utilizar a NG.CASH, desde que com a autorização e supervisão dos seus pais ou responsáveis legais.
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: utilizar o Aplicativo e/ou Site para fins ilícitos, ilegais, ofensivos, contrários ao disposto nestes Termos de Uso
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
name: NG.Cash
provenance_date: '2026-11-10'
provider_name: NG.Cash
provider_slug: ngcash
slug: ngcash-eligibility
source_date: '2026-11-10'
source_filename: ngcash-eligibility.yml
source_heading: Eligibility
source_page: https://www.ng.cash/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NG.Cash\naid: ngcash\nurl: https://www.ng.cash/termos-de-uso\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: os nossos Serviços são oferecidos apenas no Brasil\nentity_types:\n- type: individual\n  text: Para se cadastrar, você deve compartilhar conosco um conjunto de dados pessoais, bem como, uma selfie para\n    verificação e validação da sua identidade\n- type: other\n  text: Caso você seja menor de 18 (dezoito) anos, você poderá utilizar a NG.CASH, desde que com a autorização e\n    supervisão dos seus pais ou responsáveis legais.\nrestricted_uses:\n- summary: Illegal or\
  \ fraudulent use\n  text: utilizar o Aplicativo e/ou Site para fins ilícitos, ilegais, ofensivos, contrários ao disposto nestes Termos\n    de Uso\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Caso você seja menor de 18 (dezoito) anos, você poderá utilizar a NG.CASH, desde que com a autorização e\n    supervisão dos seus pais ou responsáveis legais.\n"
source_yaml_url: https://artifacts.apis.io/ngcash/eligibility/ngcash-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from NG.Cash's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Digital Banking
- Payments
- Pix
- Prepaid Cards
- Brazil
- Consumer Finance
- Generation Z
---
