---
api_specs:
- filename: openrelay-account-api-openapi.yml
  format: yaml
  label: OpenRelay Account API
  slug: openrelay-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-account-api-openapi.yml
- filename: openrelay-api-keys-api-openapi.yml
  format: yaml
  label: OpenRelay API Keys API
  slug: openrelay-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-api-keys-api-openapi.yml
- filename: openrelay-batches-api-openapi.yml
  format: yaml
  label: OpenRelay Batches API
  slug: openrelay-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-batches-api-openapi.yml
- filename: openrelay-billing-api-openapi.yml
  format: yaml
  label: OpenRelay Billing API
  slug: openrelay-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-billing-api-openapi.yml
- filename: openrelay-catalog-api-openapi.yml
  format: yaml
  label: OpenRelay Catalog API
  slug: openrelay-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-catalog-api-openapi.yml
- filename: openrelay-clusters-api-openapi.yml
  format: yaml
  label: OpenRelay Clusters API
  slug: openrelay-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-clusters-api-openapi.yml
- filename: openrelay-files-api-openapi.yml
  format: yaml
  label: OpenRelay Files API
  slug: openrelay-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-files-api-openapi.yml
- filename: openrelay-internal-api-openapi.yml
  format: yaml
  label: OpenRelay Internal API
  slug: openrelay-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-internal-api-openapi.yml
- filename: openrelay-organizations-api-openapi.yml
  format: yaml
  label: OpenRelay Organizations API
  slug: openrelay-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-organizations-api-openapi.yml
- filename: openrelay-provider-api-openapi.yml
  format: yaml
  label: OpenRelay Provider API
  slug: openrelay-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-provider-api-openapi.yml
- filename: openrelay-registry-credentials-api-openapi.yml
  format: yaml
  label: OpenRelay Registry Credentials API
  slug: openrelay-registry-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-registry-credentials-api-openapi.yml
- filename: openrelay-runners-api-openapi.yml
  format: yaml
  label: OpenRelay Runners API
  slug: openrelay-runners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-runners-api-openapi.yml
- filename: openrelay-snapshots-api-openapi.yml
  format: yaml
  label: OpenRelay Snapshots API
  slug: openrelay-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-snapshots-api-openapi.yml
- filename: openrelay-ssh-keys-api-openapi.yml
  format: yaml
  label: OpenRelay SSH Keys API
  slug: openrelay-ssh-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-ssh-keys-api-openapi.yml
- filename: openrelay-transfers-api-openapi.yml
  format: yaml
  label: OpenRelay Transfers API
  slug: openrelay-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-transfers-api-openapi.yml
- filename: openrelay-usage-api-openapi.yml
  format: yaml
  label: OpenRelay Usage API
  slug: openrelay-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-usage-api-openapi.yml
- filename: openrelay-webhooks-api-openapi.yml
  format: yaml
  label: OpenRelay Webhooks API
  slug: openrelay-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-webhooks-api-openapi.yml
- filename: openrelay-vms-api-openapi.yml
  format: yaml
  label: OpenRelay V Ms API
  slug: openrelay-vms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-vms-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of a company or other organization, you represent that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction, to use the Services.
    value: '18'
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
name: OpenRelay
provenance_date: '2026-11-10'
provider_name: OpenRelay
provider_slug: openrelay
slug: openrelay-eligibility
source_date: '2026-11-10'
source_filename: openrelay-eligibility.yml
source_heading: Eligibility
source_page: https://openrelay.inc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenRelay\naid: openrelay\nurl: https://openrelay.inc/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other organization, you represent that you have authority\n    to bind that entity to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/openrelay/eligibility/openrelay-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from OpenRelay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- GPU
- Inference
- Artificial Intelligence
- Machine Learning
- Cloud Compute
- Infrastructure
- OpenAI-Compatible
- GPU Cloud
- LLM
---
