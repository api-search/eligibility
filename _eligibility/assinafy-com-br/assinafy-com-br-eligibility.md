---
api_specs:
- filename: assinafy-com-br-accounts-api-openapi.yml
  format: yaml
  label: Assinafy Accounts API
  slug: assinafy-com-br-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-accounts-api-openapi.yml
- filename: assinafy-com-br-assignments-api-openapi.yml
  format: yaml
  label: Assinafy Assignments API
  slug: assinafy-com-br-assignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-assignments-api-openapi.yml
- filename: assinafy-com-br-authentication-api-openapi.yml
  format: yaml
  label: Assinafy Authentication API
  slug: assinafy-com-br-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-authentication-api-openapi.yml
- filename: assinafy-com-br-contracts-api-openapi.yml
  format: yaml
  label: Assinafy Contracts API
  slug: assinafy-com-br-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-contracts-api-openapi.yml
- filename: assinafy-com-br-documents-api-openapi.yml
  format: yaml
  label: Assinafy Documents API
  slug: assinafy-com-br-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-documents-api-openapi.yml
- filename: assinafy-com-br-fields-api-openapi.yml
  format: yaml
  label: Assinafy Fields API
  slug: assinafy-com-br-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-fields-api-openapi.yml
- filename: assinafy-com-br-oauth-api-openapi.yml
  format: yaml
  label: Assinafy OAuth API
  slug: assinafy-com-br-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-oauth-api-openapi.yml
- filename: assinafy-com-br-signers-api-openapi.yml
  format: yaml
  label: Assinafy Signers API
  slug: assinafy-com-br-signers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-signers-api-openapi.yml
- filename: assinafy-com-br-signing-api-openapi.yml
  format: yaml
  label: Assinafy Signing API
  slug: assinafy-com-br-signing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-signing-api-openapi.yml
- filename: assinafy-com-br-tags-api-openapi.yml
  format: yaml
  label: Assinafy Tags API
  slug: assinafy-com-br-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-tags-api-openapi.yml
- filename: assinafy-com-br-templates-api-openapi.yml
  format: yaml
  label: Assinafy Templates API
  slug: assinafy-com-br-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-templates-api-openapi.yml
- filename: assinafy-com-br-users-api-openapi.yml
  format: yaml
  label: Assinafy Users API
  slug: assinafy-com-br-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-users-api-openapi.yml
- filename: assinafy-com-br-webhook-payloads-api-openapi.yml
  format: yaml
  label: Assinafy Webhook Payloads API
  slug: assinafy-com-br-webhook-payloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-webhook-payloads-api-openapi.yml
- filename: assinafy-com-br-webhooks-api-openapi.yml
  format: yaml
  label: Assinafy Webhooks API
  slug: assinafy-com-br-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assinafy-com-br/openapi/assinafy-com-br-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: O Usuário que utiliza a Plataforma em nome de empresa, órgão público ou outra organização declara possuir poderes para vincular essa organização a estes Termos.
    type: business
  - text: O Usuário que utiliza a Plataforma em nome de empresa, órgão público ou outra organização declara possuir poderes para vincular essa organização a estes Termos.
    type: government
  minimum_age:
    text: O Usuário declara ter pelo menos 18 anos e capacidade legal para aceitar estes Termos.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent content
    text: É proibido utilizar a Plataforma para armazenar, distribuir, transmitir ou reproduzir conteúdo ilícito, difamatório, fraudulento, violento, discriminatório, pornográfico ilegal ou contrário a direitos de terceiros.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A ASSINAFY poderá solicitar confirmação de informações e suspender o acesso enquanto divergências relevantes forem verificadas.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Assinafy
provenance_date: '2026-11-09'
provider_name: Assinafy
provider_slug: assinafy-com-br
slug: assinafy-com-br-eligibility
source_date: '2026-11-09'
source_filename: assinafy-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://www.assinafy.com.br/termos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Assinafy\naid: assinafy-com-br\nurl: https://www.assinafy.com.br/termos-de-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: O Usuário que utiliza a Plataforma em nome de empresa, órgão público ou outra organização declara possuir\n    poderes para vincular essa organização a estes Termos.\n- type: government\n  text: O Usuário que utiliza a Plataforma em nome de empresa, órgão público ou outra organização declara possuir\n    poderes para vincular essa organização a estes Termos.\nrestricted_uses:\n- summary: Unlawful or fraudulent\
  \ content\n  text: É proibido utilizar a Plataforma para armazenar, distribuir, transmitir ou reproduzir conteúdo ilícito,\n    difamatório, fraudulento, violento, discriminatório, pornográfico ilegal ou contrário a direitos de terceiros.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A ASSINAFY poderá solicitar confirmação de informações e suspender o acesso enquanto divergências relevantes\n    forem verificadas.\nminimum_age:\n  value: '18'\n  text: O Usuário declara ter pelo menos 18 anos e capacidade legal para aceitar estes Termos.\n"
source_yaml_url: https://artifacts.apis.io/assinafy-com-br/eligibility/assinafy-com-br-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Assinafy's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Document Management
- Brazil
- Free
---
