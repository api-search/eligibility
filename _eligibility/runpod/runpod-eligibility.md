---
api_specs:
- filename: runpod-billing-api-openapi.yml
  format: yaml
  label: RunPod Billing API
  slug: runpod-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runpod/openapi/runpod-billing-api-openapi.yml
- filename: runpod-containerregistryauth-api-openapi.yml
  format: yaml
  label: RunPod Containerregistryauth API
  slug: runpod-containerregistryauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runpod/openapi/runpod-containerregistryauth-api-openapi.yml
- filename: runpod-docs-api-openapi.yml
  format: yaml
  label: RunPod Docs API
  slug: runpod-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runpod/openapi/runpod-docs-api-openapi.yml
- filename: runpod-endpoints-api-openapi.yml
  format: yaml
  label: RunPod Endpoints API
  slug: runpod-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runpod/openapi/runpod-endpoints-api-openapi.yml
- filename: runpod-openapi-json-api-openapi.yml
  format: yaml
  label: RunPod Openapi.json API
  slug: runpod-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runpod/openapi/runpod-openapi-json-api-openapi.yml
- filename: runpod-pods-api-openapi.yml
  format: yaml
  label: RunPod Pods API
  slug: runpod-pods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runpod/openapi/runpod-pods-api-openapi.yml
- filename: runpod-templates-api-openapi.yml
  format: yaml
  label: RunPod Templates API
  slug: runpod-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runpod/openapi/runpod-templates-api-openapi.yml
- filename: runpod-network-volumes-api-openapi.yml
  format: yaml
  label: RunPod Network Volumes API
  slug: runpod-network-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runpod/openapi/runpod-network-volumes-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - VE
    served: []
    text: The Service may not be used by or in, or exported or re-exported to, Prohibited Parties, Embargoed Countries, persons owned or otherwise controlled..., or the Government of Venezuela. Embargoed Countries currently being Cuba, Iran, North Korea, Syria, and the Crimea, so-called Donetsk People's Republic, and so-called Luhansk People's Republic regions of Ukraine.
  entity_types:
  - text: you are of legal age to form a binding contract with Runpod
    type: individual
  minimum_age:
    text: you are of legal age to form a binding contract with Runpod
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use the Site or the Service for any illegal or unauthorized purpose
  - summary: Unauthorized content types
    text: intoxicants of any sort; illegal drugs or other illegal products; alcoholic beverages; games of chance; and pornography or graphic adult content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- VE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RunPod
provenance_date: '2026-11-10'
provider_name: RunPod
provider_slug: runpod
slug: runpod-eligibility
source_date: '2026-11-10'
source_filename: runpod-eligibility.yml
source_heading: Eligibility
source_page: https://www.runpod.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RunPod\naid: runpod\nurl: https://www.runpod.io/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - VE\n  text: The Service may not be used by or in, or exported or re-exported to, Prohibited Parties, Embargoed Countries,\n    persons owned or otherwise controlled..., or the Government of Venezuela. Embargoed Countries currently being\n    Cuba, Iran, North Korea, Syria, and the Crimea, so-called Donetsk People's Republic, and so-called Luhansk People's\n    Republic regions of Ukraine.\nentity_types:\n- type: individual\n\
  \  text: you are of legal age to form a binding contract with Runpod\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use the Site or the Service for any illegal or unauthorized purpose\n- summary: Unauthorized content types\n  text: intoxicants of any sort; illegal drugs or other illegal products; alcoholic beverages; games of chance;\n    and pornography or graphic adult content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract with Runpod\n"
source_yaml_url: https://artifacts.apis.io/runpod/eligibility/runpod-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from RunPod's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Cloud
- Compute
- GPU
- Inference
- Machine Learning
- Serverless
---
