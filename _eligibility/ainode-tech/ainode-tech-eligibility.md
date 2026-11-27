---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Baseada em Portugal, servindo a União Europeia.
  entity_types:
  - text: Consumidores finais B2C EU (sem NIF) pagam IVA ao país de residência através do regime OSS (One Stop Shop).
    type: individual
  - text: Subscrições ou pagamentos agregados a pedido de B2B com NIF válido seguem o regime de auto-liquidação (reverse charge) da EU.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful data processing or sanctions
    text: Usar o BotStore para tratamento de dados que violem a legislação aplicável ao seu caso — nomeadamente RGPD, lei portuguesa, e sanções EU
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: 'Sem contas, sem aceitação explícita: o pagamento é a aceitação.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ainode-tech
provenance_date: '2026-11-09'
provider_name: ainode-tech
provider_slug: ainode-tech
slug: ainode-tech-eligibility
source_date: '2026-11-09'
source_filename: ainode-tech-eligibility.yml
source_heading: Eligibility
source_page: https://ainode.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ainode-tech\naid: ainode-tech\nurl: https://ainode.tech/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Baseada em Portugal, servindo a União Europeia.\nentity_types:\n- type: individual\n  text: Consumidores finais B2C EU (sem NIF) pagam IVA ao país de residência através do regime OSS (One Stop Shop).\n- type: business\n  text: Subscrições ou pagamentos agregados a pedido de B2B com NIF válido seguem o regime de auto-liquidação (reverse\n    charge) da EU.\nrestricted_uses:\n- summary: Unlawful data processing or sanctions\n  text: Usar o BotStore para tratamento de dados\
  \ que violem a legislação aplicável ao seu caso — nomeadamente RGPD,\n    lei portuguesa, e sanções EU\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: 'Sem contas, sem aceitação explícita: o pagamento é a aceitação.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ainode-tech/eligibility/ainode-tech-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from ainode-tech's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wearables
- Artificial Intelligence
- Privacy
- Portugal
---
