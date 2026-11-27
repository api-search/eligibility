---
api_specs:
- filename: cast-ai-ai-enabler-api-openapi.yml
  format: yaml
  label: CAST AI AI Enabler API
  slug: cast-ai-ai-enabler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-ai-enabler-api-openapi.yml
- filename: cast-ai-allocation-groups-api-openapi.yml
  format: yaml
  label: CAST AI Allocation Groups API
  slug: cast-ai-allocation-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-allocation-groups-api-openapi.yml
- filename: cast-ai-autoscaler-api-openapi.yml
  format: yaml
  label: CAST AI Autoscaler API
  slug: cast-ai-autoscaler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-autoscaler-api-openapi.yml
- filename: cast-ai-cluster-actions-api-openapi.yml
  format: yaml
  label: CAST AI Cluster Actions API
  slug: cast-ai-cluster-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-cluster-actions-api-openapi.yml
- filename: cast-ai-cost-reports-api-openapi.yml
  format: yaml
  label: CAST AI Cost Reports API
  slug: cast-ai-cost-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-cost-reports-api-openapi.yml
- filename: cast-ai-external-clusters-api-openapi.yml
  format: yaml
  label: CAST AI External Clusters API
  slug: cast-ai-external-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-external-clusters-api-openapi.yml
- filename: cast-ai-hibernation-schedules-api-openapi.yml
  format: yaml
  label: CAST AI Hibernation Schedules API
  slug: cast-ai-hibernation-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-hibernation-schedules-api-openapi.yml
- filename: cast-ai-insights-api-openapi.yml
  format: yaml
  label: CAST AI Insights API
  slug: cast-ai-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-insights-api-openapi.yml
- filename: cast-ai-inventory-api-openapi.yml
  format: yaml
  label: CAST AI Inventory API
  slug: cast-ai-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-inventory-api-openapi.yml
- filename: cast-ai-node-configuration-api-openapi.yml
  format: yaml
  label: CAST AI Node Configuration API
  slug: cast-ai-node-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-node-configuration-api-openapi.yml
- filename: cast-ai-node-templates-api-openapi.yml
  format: yaml
  label: CAST AI Node Templates API
  slug: cast-ai-node-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-node-templates-api-openapi.yml
- filename: cast-ai-operations-api-openapi.yml
  format: yaml
  label: CAST AI Operations API
  slug: cast-ai-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-operations-api-openapi.yml
- filename: cast-ai-policies-api-openapi.yml
  format: yaml
  label: CAST AI Policies API
  slug: cast-ai-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-policies-api-openapi.yml
- filename: cast-ai-pricing-api-openapi.yml
  format: yaml
  label: CAST AI Pricing API
  slug: cast-ai-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-pricing-api-openapi.yml
- filename: cast-ai-scheduled-rebalancing-api-openapi.yml
  format: yaml
  label: CAST AI Scheduled Rebalancing API
  slug: cast-ai-scheduled-rebalancing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-scheduled-rebalancing-api-openapi.yml
- filename: cast-ai-settings-api-openapi.yml
  format: yaml
  label: CAST AI Settings API
  slug: cast-ai-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-settings-api-openapi.yml
- filename: cast-ai-workload-optimization-api-openapi.yml
  format: yaml
  label: CAST AI Workload Optimization API
  slug: cast-ai-workload-optimization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cast-ai/openapi/cast-ai-workload-optimization-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU USE THE SERVICES ACTING AS THE AGENT FOR A COMPANY OR OTHER ENTITY, YOU REPRESENT THAT YOU HAVE THE LEGAL AUTHORITY TO BIND SUCH COMPANY OR ENTITY AS THE “CUSTOMER” HEREUNDER
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No HIPAA protected health information
    text: Customer shall not provide, transmit, disclose, or otherwise make available to Cast AI any “Protected Health Information” as defined under the Health Insurance Portability and Accountability Act of 1996
  - summary: Export compliance
    text: Customer shall not permit its Users to access or use Services in violation of any U.S. export embargo, prohibition or restriction.
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
name: CAST AI
provenance_date: '2026-11-09'
provider_name: CAST AI
provider_slug: cast-ai
slug: cast-ai-eligibility
source_date: '2026-11-09'
source_filename: cast-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cast.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CAST AI\naid: cast-ai\nurl: https://cast.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU USE THE SERVICES ACTING AS THE AGENT FOR A COMPANY OR OTHER ENTITY, YOU REPRESENT THAT YOU HAVE THE\n    LEGAL AUTHORITY TO BIND SUCH COMPANY OR ENTITY AS THE “CUSTOMER” HEREUNDER\nrestricted_uses:\n- summary: No HIPAA protected health information\n  text: Customer shall not provide, transmit, disclose, or otherwise make available to Cast AI any “Protected Health\n    Information” as defined under the\
  \ Health Insurance Portability and Accountability Act of 1996\n- summary: Export compliance\n  text: Customer shall not permit its Users to access or use Services in violation of any U.S. export embargo, prohibition\n    or restriction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cast-ai/eligibility/cast-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CAST AI's own page on 2026-11-09.
synthetic: false
tags:
- Auto-Scaling
- Cloud Infrastructure
- Cost Optimization
- DevOps
- FinOps
- Kubernetes
- Observability
---
