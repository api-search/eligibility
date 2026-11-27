---
api_specs:
- filename: docsmint-com-admin-api-openapi.yml
  format: yaml
  label: docsmint-com Admin API
  slug: docsmint-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-admin-api-openapi.yml
- filename: docsmint-com-attachments-api-openapi.yml
  format: yaml
  label: docsmint-com Attachments API
  slug: docsmint-com-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-attachments-api-openapi.yml
- filename: docsmint-com-auth-api-openapi.yml
  format: yaml
  label: docsmint-com Auth API
  slug: docsmint-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-auth-api-openapi.yml
- filename: docsmint-com-categories-api-openapi.yml
  format: yaml
  label: docsmint-com Categories API
  slug: docsmint-com-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-categories-api-openapi.yml
- filename: docsmint-com-csrf-token-api-openapi.yml
  format: yaml
  label: docsmint-com Csrf Token API
  slug: docsmint-com-csrf-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-csrf-token-api-openapi.yml
- filename: docsmint-com-documents-api-openapi.yml
  format: yaml
  label: docsmint-com Documents API
  slug: docsmint-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-documents-api-openapi.yml
- filename: docsmint-com-folders-api-openapi.yml
  format: yaml
  label: docsmint-com Folders API
  slug: docsmint-com-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-folders-api-openapi.yml
- filename: docsmint-com-graph-api-openapi.yml
  format: yaml
  label: docsmint-com Graph API
  slug: docsmint-com-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-graph-api-openapi.yml
- filename: docsmint-com-health-api-openapi.yml
  format: yaml
  label: docsmint-com Health API
  slug: docsmint-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-health-api-openapi.yml
- filename: docsmint-com-keys-api-openapi.yml
  format: yaml
  label: docsmint-com Keys API
  slug: docsmint-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-keys-api-openapi.yml
- filename: docsmint-com-plugins-api-openapi.yml
  format: yaml
  label: docsmint-com Plugins API
  slug: docsmint-com-plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-plugins-api-openapi.yml
- filename: docsmint-com-search-api-openapi.yml
  format: yaml
  label: docsmint-com Search API
  slug: docsmint-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-search-api-openapi.yml
- filename: docsmint-com-share-api-openapi.yml
  format: yaml
  label: docsmint-com Share API
  slug: docsmint-com-share-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-share-api-openapi.yml
- filename: docsmint-com-tags-api-openapi.yml
  format: yaml
  label: docsmint-com Tags API
  slug: docsmint-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-tags-api-openapi.yml
- filename: docsmint-com-trash-api-openapi.yml
  format: yaml
  label: docsmint-com Trash API
  slug: docsmint-com-trash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-trash-api-openapi.yml
- filename: docsmint-com-webhooks-api-openapi.yml
  format: yaml
  label: docsmint-com Webhooks API
  slug: docsmint-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into this contract.
    type: individual
  - text: If you use DocsMint for an organisation, you confirm that you can bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into this contract.
    value: '18'
  restricted_uses:
  - summary: Illegal surveillance, fraud, prohibited decisions
    text: You must not use DocsMint for illegal surveillance, exploitation, fraud, or prohibited decisions about individuals.
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
name: docsmint-com
provenance_date: '2026-11-09'
provider_name: docsmint-com
provider_slug: docsmint-com
slug: docsmint-com-eligibility
source_date: '2026-11-09'
source_filename: docsmint-com-eligibility.yml
source_heading: Eligibility
source_page: https://docsmint.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: docsmint-com\naid: docsmint-com\nurl: https://docsmint.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into this contract.\n- type: business\n  text: If you use DocsMint for an organisation, you confirm that you can bind it.\nrestricted_uses:\n- summary: Illegal surveillance, fraud, prohibited decisions\n  text: You must not use DocsMint for illegal surveillance, exploitation, fraud, or prohibited decisions about individuals.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into this contract.\n"
source_yaml_url: https://artifacts.apis.io/docsmint-com/eligibility/docsmint-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from docsmint-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Document Management
- Knowledge Base
- Software-as-a-Service
- Collaboration
---
