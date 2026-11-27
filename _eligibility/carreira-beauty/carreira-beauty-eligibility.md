---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: O uso é gratuito para profissionais.
    type: individual
  - text: 'Empresas: a assinatura é mensal e renovada automaticamente.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Contact data limited to hiring
    text: Os contatos obtidos na plataforma só podem ser usados para fins de contratação.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Toda vaga passa por análise da nossa equipe antes de ir ao ar, e pode ser recusada se não atender a estes termos.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carreira Beauty
provenance_date: '2026-11-09'
provider_name: Carreira Beauty
provider_slug: carreira-beauty
slug: carreira-beauty-eligibility
source_date: '2026-11-09'
source_filename: carreira-beauty-eligibility.yml
source_heading: Eligibility
source_page: https://carreirabeauty.com/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carreira Beauty\naid: carreira-beauty\nurl: https://carreirabeauty.com/termos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: O uso é gratuito para profissionais.\n- type: business\n  text: 'Empresas: a assinatura é mensal e renovada automaticamente.'\nrestricted_uses:\n- summary: Contact data limited to hiring\n  text: Os contatos obtidos na plataforma só podem ser usados para fins de contratação.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Toda vaga passa por análise da nossa equipe antes de ir ao\
  \ ar, e pode ser recusada se não atender a estes\n    termos.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carreira-beauty/eligibility/carreira-beauty-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Carreira Beauty's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beauty
- Wellness
- Aesthetics
- Job
- Employment
- Marketplace
- Brazil
---
