---
api_specs:
- filename: pontofato-apis-json-api-openapi.yml
  format: yaml
  label: PontoFato Apis.json API
  slug: pontofato-apis-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-apis-json-api-openapi.yml
- filename: pontofato-buscar-api-openapi.yml
  format: yaml
  label: PontoFato Buscar API
  slug: pontofato-buscar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-buscar-api-openapi.yml
- filename: pontofato-cep-api-openapi.yml
  format: yaml
  label: PontoFato Cep API
  slug: pontofato-cep-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-cep-api-openapi.yml
- filename: pontofato-contact-api-openapi.yml
  format: yaml
  label: PontoFato Contact API
  slug: pontofato-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-contact-api-openapi.yml
- filename: pontofato-credito-api-openapi.yml
  format: yaml
  label: PontoFato Credito API
  slug: pontofato-credito-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-credito-api-openapi.yml
- filename: pontofato-empresas-api-openapi.yml
  format: yaml
  label: PontoFato Empresas API
  slug: pontofato-empresas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-empresas-api-openapi.yml
- filename: pontofato-health-api-openapi.yml
  format: yaml
  label: PontoFato Health API
  slug: pontofato-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-health-api-openapi.yml
- filename: pontofato-local-api-openapi.yml
  format: yaml
  label: PontoFato Local API
  slug: pontofato-local-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-local-api-openapi.yml
- filename: pontofato-mcp-api-openapi.yml
  format: yaml
  label: PontoFato MCP API
  slug: pontofato-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-mcp-api-openapi.yml
- filename: pontofato-metrics-api-openapi.yml
  format: yaml
  label: PontoFato Metrics API
  slug: pontofato-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-metrics-api-openapi.yml
- filename: pontofato-okf-api-openapi.yml
  format: yaml
  label: PontoFato Okf API
  slug: pontofato-okf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-okf-api-openapi.yml
- filename: pontofato-pontofato-api-openapi.yml
  format: yaml
  label: PontoFato Ponto Fato API
  slug: pontofato-pontofato-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-pontofato-api-openapi.yml
- filename: pontofato-proximo-api-openapi.yml
  format: yaml
  label: PontoFato Proximo API
  slug: pontofato-proximo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-proximo-api-openapi.yml
- filename: pontofato-raio-api-openapi.yml
  format: yaml
  label: PontoFato Raio API
  slug: pontofato-raio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-raio-api-openapi.yml
- filename: pontofato-vizinhanca-api-openapi.yml
  format: yaml
  label: PontoFato Vizinhanca API
  slug: pontofato-vizinhanca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-vizinhanca-api-openapi.yml
- filename: pontofato-well-known-api-openapi.yml
  format: yaml
  label: PontoFato .well Known API
  slug: pontofato-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pontofato/openapi/pontofato-well-known-api-openapi.yml
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
  - summary: Atividade ilegal, assédio, falsa identidade
    text: Não use o serviço para atividade ilegal, para assediar ou para se passar por outra pessoa.
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
name: PontoFato
provenance_date: '2026-11-10'
provider_name: PontoFato
provider_slug: pontofato
slug: pontofato-eligibility
source_date: '2026-11-10'
source_filename: pontofato-eligibility.yml
source_heading: Eligibility
source_page: https://pontofato.com/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PontoFato\naid: pontofato\nurl: https://pontofato.com/termos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Atividade ilegal, assédio, falsa identidade\n  text: Não use o serviço para atividade ilegal, para assediar ou para se passar por outra pessoa.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pontofato/eligibility/pontofato-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from PontoFato's own page on 2026-11-10.
synthetic: false
tags:
- Brazilian CEP
- address geocoding
- IBGE CNEFE
- Geospatial
- latitude/longitude
- CNPJ
- Receita Federal
- Business Registry
- Location Intelligence
- proximity search
- radius search
- Open Government Data
- Agent-Native
- MCP
- x402-micropayments
---
