---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Você deve ter pelo menos 18 anos de idade e ser autorizado pela sua empresa para usar nossa Plataforma.
    type: individual
  - text: Se você estiver utilizando nossa Plataforma em nome de uma empresa, confirma que possui a autoridade para vincular essa entidade a estes Termos.
    type: business
  minimum_age:
    text: Você deve ter pelo menos 18 anos de idade e ser autorizado pela sua empresa para usar nossa Plataforma.
    value: '18'
  restricted_uses:
  - summary: Illegal or unethical content
    text: Usar a Plataforma para gerar conteúdo ilegal ou antiético.
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
name: Enter
provenance_date: '2026-11-09'
provider_name: Enter
provider_slug: getenter-ai
slug: getenter-ai-eligibility
source_date: '2026-11-09'
source_filename: getenter-ai-eligibility.yml
source_heading: Eligibility
source_page: https://getenter.ai/en/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enter\naid: getenter-ai\nurl: https://getenter.ai/en/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Você deve ter pelo menos 18 anos de idade e ser autorizado pela sua empresa para usar nossa Plataforma.\n- type: business\n  text: Se você estiver utilizando nossa Plataforma em nome de uma empresa, confirma que possui a autoridade para\n    vincular essa entidade a estes Termos.\nrestricted_uses:\n- summary: Illegal or unethical content\n  text: Usar a Plataforma para gerar conteúdo ilegal ou antiético.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Você deve ter pelo menos 18 anos de idade e ser autorizado pela sua empresa para usar nossa Plataforma.\n"
source_yaml_url: https://artifacts.apis.io/getenter-ai/eligibility/getenter-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Enter's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Litigation
- Brazil
- Legal Tech
- Enterprise
---
