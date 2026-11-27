---
api_specs:
- filename: loft-labs-healthz-api-openapi.yml
  format: yaml
  label: Loft Labs Healthz API
  slug: loft-labs-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loft-labs/openapi/loft-labs-healthz-api-openapi.yml
- filename: loft-labs-kubernetes-api-openapi.yml
  format: yaml
  label: Loft Labs Kubernetes API
  slug: loft-labs-kubernetes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loft-labs/openapi/loft-labs-kubernetes-api-openapi.yml
- filename: loft-labs-loft-labs-api-api-openapi.yml
  format: yaml
  label: Loft Labs Loft Labs API
  slug: loft-labs-loft-labs-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loft-labs/openapi/loft-labs-loft-labs-api-api-openapi.yml
- filename: loft-labs-loft-sh-api-openapi.yml
  format: yaml
  label: Loft Labs Loft Sh API
  slug: loft-labs-loft-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loft-labs/openapi/loft-labs-loft-sh-api-openapi.yml
- filename: loft-labs-node-api-openapi.yml
  format: yaml
  label: Loft Labs Node API
  slug: loft-labs-node-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loft-labs/openapi/loft-labs-node-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Service is intended only for access and use by individuals at least eighteen (18) years old.
    type: individual
  minimum_age:
    text: at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Harm to minors
    text: For the purpose of exploiting, harming, or attempting to exploit or harm minors in any way by exposing them to inappropriate content or otherwise.
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
name: Loft Labs
provenance_date: '2026-11-09'
provider_name: Loft Labs
provider_slug: loft-labs
slug: loft-labs-eligibility
source_date: '2026-11-09'
source_filename: loft-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.vcluster.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loft Labs\naid: loft-labs\nurl: https://www.vcluster.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our Service is intended only for access and use by individuals at least eighteen (18) years old.\nrestricted_uses:\n- summary: Harm to minors\n  text: For the purpose of exploiting, harming, or attempting to exploit or harm minors in any way by exposing them\n    to inappropriate content or otherwise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/loft-labs/eligibility/loft-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Loft Labs's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Cloud
- Kubernetes
- Multi-Tenant
- Infrastructure
---
