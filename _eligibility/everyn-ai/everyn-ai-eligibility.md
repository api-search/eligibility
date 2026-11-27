---
api_specs:
- filename: everyn-ai-alert-rules-api-openapi.yml
  format: yaml
  label: Everyn Alert Rules API
  slug: everyn-ai-alert-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-alert-rules-api-openapi.yml
- filename: everyn-ai-billing-api-openapi.yml
  format: yaml
  label: Everyn Billing API
  slug: everyn-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-billing-api-openapi.yml
- filename: everyn-ai-callable-jobs-api-openapi.yml
  format: yaml
  label: Everyn Callable Jobs API
  slug: everyn-ai-callable-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-callable-jobs-api-openapi.yml
- filename: everyn-ai-dataset-uploads-api-openapi.yml
  format: yaml
  label: Everyn Dataset Uploads API
  slug: everyn-ai-dataset-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-dataset-uploads-api-openapi.yml
- filename: everyn-ai-datasets-api-openapi.yml
  format: yaml
  label: Everyn Datasets API
  slug: everyn-ai-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-datasets-api-openapi.yml
- filename: everyn-ai-exports-api-openapi.yml
  format: yaml
  label: Everyn Exports API
  slug: everyn-ai-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-exports-api-openapi.yml
- filename: everyn-ai-health-api-openapi.yml
  format: yaml
  label: Everyn Health API
  slug: everyn-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-health-api-openapi.yml
- filename: everyn-ai-job-specs-api-openapi.yml
  format: yaml
  label: Everyn Job Specs API
  slug: everyn-ai-job-specs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-job-specs-api-openapi.yml
- filename: everyn-ai-models-api-openapi.yml
  format: yaml
  label: Everyn Models API
  slug: everyn-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-models-api-openapi.yml
- filename: everyn-ai-organization-admin-api-openapi.yml
  format: yaml
  label: Everyn Organization Admin API
  slug: everyn-ai-organization-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-organization-admin-api-openapi.yml
- filename: everyn-ai-runs-api-openapi.yml
  format: yaml
  label: Everyn Runs API
  slug: everyn-ai-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-runs-api-openapi.yml
- filename: everyn-ai-usage-api-openapi.yml
  format: yaml
  label: Everyn Usage API
  slug: everyn-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-usage-api-openapi.yml
- filename: everyn-ai-webhooks-api-openapi.yml
  format: yaml
  label: Everyn Webhooks API
  slug: everyn-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-webhooks-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended solely for businesses and other organizations located in the United States.
  entity_types:
  - text: The Services are intended solely for businesses and other organizations located in the United States.
    type: business
  - text: If you accept these Terms for an organization, you represent that you have authority to bind that organization
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST 18 YEARS OLD AND LEGALLY CAPABLE OF ENTERING INTO A CONTRACT TO USE THE SERVICES.
    value: '18'
  restricted_uses:
  - summary: No personal/household use
    text: YOU MAY NOT USE THE SERVICES AS A CONSUMER OR FOR PERSONAL, FAMILY, OR HOUSEHOLD PURPOSES.
  - summary: Restricted data submission
    text: Customer must not submit protected health information; payment-card data; financial-account credentials; government identification numbers; authentication secrets; children’s personal information; biometric or genetic identifiers; precise geolocation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide complete and accurate registration and billing information and keep it current.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Everyn
provenance_date: '2026-11-09'
provider_name: Everyn
provider_slug: everyn-ai
slug: everyn-ai-eligibility
source_date: '2026-11-09'
source_filename: everyn-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.everyn.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everyn\naid: everyn-ai\nurl: https://www.everyn.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended solely for businesses and other organizations located in the United States.\nentity_types:\n- type: business\n  text: The Services are intended solely for businesses and other organizations located in the United States.\n- type: individual\n  text: If you accept these Terms for an organization, you represent that you have authority to bind that organization\nrestricted_uses:\n- summary: No personal/household use\n  text: YOU MAY NOT USE THE SERVICES\
  \ AS A CONSUMER OR FOR PERSONAL, FAMILY, OR HOUSEHOLD PURPOSES.\n- summary: Restricted data submission\n  text: Customer must not submit protected health information; payment-card data; financial-account credentials;\n    government identification numbers; authentication secrets; children’s personal information; biometric or genetic\n    identifiers; precise geolocation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide complete and accurate registration and billing information and keep it current.\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST 18 YEARS OLD AND LEGALLY CAPABLE OF ENTERING INTO A CONTRACT TO USE THE SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/everyn-ai/eligibility/everyn-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Everyn's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Productivity
- Agents
- Platform
---
