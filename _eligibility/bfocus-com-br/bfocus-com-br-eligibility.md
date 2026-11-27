---
api_specs:
- filename: bfocus-com-br-openapi.json
  format: json
  label: bFocus API
  slug: bfocus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bfocus-com-br/openapi/bfocus-com-br-openapi.json
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam, illegal content, rights violations
    text: Você concorda em não usar o bFocus para envio de spam, conteúdo ilegal, violação de direitos de terceiros ou qualquer atividade que comprometa a integridade da plataforma.
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
name: bFocus
provenance_date: '2026-11-09'
provider_name: bFocus
provider_slug: bfocus-com-br
slug: bfocus-com-br-eligibility
source_date: '2026-11-09'
source_filename: bfocus-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://www.bfocus.com.br/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: bFocus\naid: bfocus-com-br\nurl: https://www.bfocus.com.br/termos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spam, illegal content, rights violations\n  text: Você concorda em não usar o bFocus para envio de spam, conteúdo ilegal, violação de direitos de terceiros\n    ou qualquer atividade que comprometa a integridade da plataforma.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bfocus-com-br/eligibility/bfocus-com-br-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from bFocus's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Lead Management
- Customer Service
- Software-as-a-Service
- Brazil
---
