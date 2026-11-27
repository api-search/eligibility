---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: Considerando o nosso tipo de Serviço, Você só poderá se cadastrar, acessá-lo e utilizá-lo se tiver mais de 18 (dezoito) anos e residir no Brasil.
  entity_types:
  - text: 'Você ou Usuário: significa a pessoa física que realiza o seu cadastro'
    type: individual
  minimum_age:
    text: Você só poderá se cadastrar, acessá-lo e utilizá-lo se tiver mais de 18 (dezoito) anos e residir no Brasil.
    value: '18'
  restricted_uses:
  - summary: No fraud, illicit or money-laundering use
    text: não utilizar ou tentar utilizar a plataforma para fins ilícitos, inclusive fraudulentos ou de ocultação ou lavagem de bens, direitos ou valores
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Uma vez criada a conta do Usuário, será necessário fornecer informações e documentos para validação de sua identidade.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Noh
provenance_date: '2026-11-10'
provider_name: Noh
provider_slug: noh
slug: noh-eligibility
source_date: '2026-11-10'
source_filename: noh-eligibility.yml
source_heading: Eligibility
source_page: https://www.noh.com.br/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noh\naid: noh\nurl: https://www.noh.com.br/termos-de-uso\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: Considerando o nosso tipo de Serviço, Você só poderá se cadastrar, acessá-lo e utilizá-lo se tiver mais\n    de 18 (dezoito) anos e residir no Brasil.\nentity_types:\n- type: individual\n  text: 'Você ou Usuário: significa a pessoa física que realiza o seu cadastro'\nrestricted_uses:\n- summary: No fraud, illicit or money-laundering use\n  text: não utilizar ou tentar utilizar a plataforma para fins ilícitos, inclusive fraudulentos ou de ocultação\n   \
  \ ou lavagem de bens, direitos ou valores\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Uma vez criada a conta do Usuário, será necessário fornecer informações e documentos para validação de sua\n    identidade.\nminimum_age:\n  value: '18'\n  text: Você só poderá se cadastrar, acessá-lo e utilizá-lo se tiver mais de 18 (dezoito) anos e residir no Brasil.\n"
source_yaml_url: https://artifacts.apis.io/noh/eligibility/noh-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Noh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Neobank
- Payments
- Banking
- Consumer Finance
- Brazil
- Couples
---
