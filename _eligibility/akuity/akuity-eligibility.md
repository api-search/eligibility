---
api_specs:
- filename: akuity-argocdservice-api-openapi.yml
  format: yaml
  label: Akuity Argo CD Service API
  slug: akuity-argocdservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-argocdservice-api-openapi.yml
- filename: akuity-customroleservice-api-openapi.yml
  format: yaml
  label: Akuity Custom Role Service API
  slug: akuity-customroleservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-customroleservice-api-openapi.yml
- filename: akuity-extensionservice-api-openapi.yml
  format: yaml
  label: Akuity Extension Service API
  slug: akuity-extensionservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-extensionservice-api-openapi.yml
- filename: akuity-kargoservice-api-openapi.yml
  format: yaml
  label: Akuity Kargo Service API
  slug: akuity-kargoservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-kargoservice-api-openapi.yml
- filename: akuity-organizationservice-api-openapi.yml
  format: yaml
  label: Akuity Organization Service API
  slug: akuity-organizationservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-organizationservice-api-openapi.yml
- filename: akuity-systemservice-api-openapi.yml
  format: yaml
  label: Akuity System Service API
  slug: akuity-systemservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-systemservice-api-openapi.yml
- filename: akuity-api-key-service-api-openapi.yml
  format: yaml
  label: Akuity Api Key Service API
  slug: akuity-api-key-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-api-key-service-api-openapi.yml
- filename: akuity-auth-service-api-openapi.yml
  format: yaml
  label: Akuity Auth Service API
  slug: akuity-auth-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-auth-service-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if the Service is to be used by or on behalf of a company or other organization, the individual accepting this Agreement represents and warrants that he or she has the authority to bind that company or other organization to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and weapons restrictions
    text: used for any purposes prohibited by the such export laws and regulations, including but not limited to nuclear, chemical, or biological weapons proliferation
  - summary: No unlawful use
    text: (v) use the Service in any unlawful manner, for any unlawful purpose, or in any manner inconsistent with this Agreement or applicable documentation
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
name: Akuity
provenance_date: '2026-11-09'
provider_name: Akuity
provider_slug: akuity
slug: akuity-eligibility
source_date: '2026-11-09'
source_filename: akuity-eligibility.yml
source_heading: Eligibility
source_page: https://akuity.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Akuity\naid: akuity\nurl: https://akuity.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if the Service is to be used by or on behalf of a company or other organization, the individual accepting\n    this Agreement represents and warrants that he or she has the authority to bind that company or other organization\n    to this Agreement\nrestricted_uses:\n- summary: Export and weapons restrictions\n  text: used for any purposes prohibited by the such export laws and regulations, including but not limited to nuclear,\n\
  \    chemical, or biological weapons proliferation\n- summary: No unlawful use\n  text: (v) use the Service in any unlawful manner, for any unlawful purpose, or in any manner inconsistent with\n    this Agreement or applicable documentation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/akuity/eligibility/akuity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Akuity's own page on 2026-11-09.
synthetic: false
tags:
- GitOps
- Continuous Delivery
- Kubernetes
- ArgoCD
- Kargo
- Platform Engineering
- DevOps
- Progressive Delivery
- Cloud-Native
- AIOps
- Developer Tools
---
