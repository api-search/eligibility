---
api_specs:
- filename: auxen-ai-billing-api-openapi.yml
  format: yaml
  label: Auxen Billing API
  slug: auxen-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-billing-api-openapi.yml
- filename: auxen-ai-deployments-api-openapi.yml
  format: yaml
  label: Auxen Deployments API
  slug: auxen-ai-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-deployments-api-openapi.yml
- filename: auxen-ai-deprecated-api-openapi.yml
  format: yaml
  label: Auxen Deprecated API
  slug: auxen-ai-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-deprecated-api-openapi.yml
- filename: auxen-ai-inference-api-openapi.yml
  format: yaml
  label: Auxen Inference API
  slug: auxen-ai-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-inference-api-openapi.yml
- filename: auxen-ai-models-api-openapi.yml
  format: yaml
  label: Auxen Models API
  slug: auxen-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-models-api-openapi.yml
- filename: auxen-ai-pay-with-usdc-api-openapi.yml
  format: yaml
  label: Auxen Pay with USDC API
  slug: auxen-ai-pay-with-usdc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-pay-with-usdc-api-openapi.yml
- filename: auxen-ai-scheduling-api-openapi.yml
  format: yaml
  label: Auxen Scheduling API
  slug: auxen-ai-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-scheduling-api-openapi.yml
- filename: auxen-ai-webhooks-api-openapi.yml
  format: yaml
  label: Auxen Webhooks API
  slug: auxen-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-webhooks-api-openapi.yml
- filename: auxen-ai-workers-api-openapi.yml
  format: yaml
  label: Auxen Workers API
  slug: auxen-ai-workers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-workers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You confirm that you aren't a person or entity on a sanctions list
  minimum_age:
    text: You must be at least [ AGE, e.g. 18 ] years old (or the age of majority in your jurisdiction) to use the Service.
    value: null
  restricted_uses:
  - summary: No regulated data without DPA
    text: Submit content that constitutes protected health information, payment-card data, or other regulated data unless you have a signed Data Processing Agreement with us that specifically permits it.
  - summary: No collecting or tracking people
    text: Collect personal information about people, or track or monitor a person.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: One-time codes sent to that address authenticate access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Auxen
provenance_date: '2026-11-09'
provider_name: Auxen
provider_slug: auxen-ai
slug: auxen-ai-eligibility
source_date: '2026-11-09'
source_filename: auxen-ai-eligibility.yml
source_heading: Eligibility
source_page: https://auxen.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Auxen\naid: auxen-ai\nurl: https://auxen.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You confirm that you aren't a person or entity on a sanctions list\nentity_types: []\nrestricted_uses:\n- summary: No regulated data without DPA\n  text: Submit content that constitutes protected health information, payment-card data, or other regulated data\n    unless you have a signed Data Processing Agreement with us that specifically permits it.\n- summary: No collecting or tracking people\n  text: Collect personal information about people, or track or monitor a person.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: One-time codes sent to that address authenticate access.\nminimum_age:\n  value: null\n  text: You must be at least [ AGE, e.g. 18 ] years old (or the age of majority in your jurisdiction) to use the\n    Service.\n"
source_yaml_url: https://artifacts.apis.io/auxen-ai/eligibility/auxen-ai-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Auxen's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Platform
- Workers
- Productivity
---
