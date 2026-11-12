---
api_specs:
- filename: cnpj-ai-cat-logo-api-openapi.yml
  format: yaml
  label: cnpj.ai Catálogo API
  slug: cnpj-ai-cat-logo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-cat-logo-api-openapi.yml
- filename: cnpj-ai-consulta-de-cnpj-api-openapi.yml
  format: yaml
  label: cnpj.ai Consulta de CNPJ API
  slug: cnpj-ai-consulta-de-cnpj-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-consulta-de-cnpj-api-openapi.yml
- filename: cnpj-ai-empresas-api-openapi.yml
  format: yaml
  label: cnpj.ai Empresas API
  slug: cnpj-ai-empresas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-empresas-api-openapi.yml
- filename: cnpj-ai-empresas-fontes-api-openapi.yml
  format: yaml
  label: cnpj.ai empresas — fontes API
  slug: cnpj-ai-empresas-fontes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-empresas-fontes-api-openapi.yml
- filename: cnpj-ai-estabelecimentos-api-openapi.yml
  format: yaml
  label: cnpj.ai Estabelecimentos API
  slug: cnpj-ai-estabelecimentos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-estabelecimentos-api-openapi.yml
- filename: cnpj-ai-estabelecimentos-fontes-api-openapi.yml
  format: yaml
  label: cnpj.ai estabelecimentos — fontes API
  slug: cnpj-ai-estabelecimentos-fontes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-estabelecimentos-fontes-api-openapi.yml
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
  - summary: Harassment, fraud, unlawful purposes
    text: Não é permitido usar o cnpj.ai para assediar, perseguir ou discriminar pessoas, para praticar fraude ou para qualquer finalidade ilícita.
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
name: cnpj.ai
provenance_date: '2026-11-09'
provider_name: cnpj.ai
provider_slug: cnpj-ai
slug: cnpj-ai-eligibility
source_date: '2026-11-09'
source_filename: cnpj-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cnpj.ai/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cnpj.ai\naid: cnpj-ai\nurl: https://cnpj.ai/termos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment, fraud, unlawful purposes\n  text: Não é permitido usar o cnpj.ai para assediar, perseguir ou discriminar pessoas, para praticar fraude ou\n    para qualquer finalidade ilícita.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cnpj-ai/eligibility/cnpj-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from cnpj.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Brazil
- CNPJ
- Open Data
- Public Records
- Business Registry
- Compliance
- MCP
---
