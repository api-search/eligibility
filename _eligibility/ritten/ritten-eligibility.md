---
api_specs:
- filename: ritten-calendar-api-openapi.yml
  format: yaml
  label: Ritten Calendar API
  slug: ritten-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-calendar-api-openapi.yml
- filename: ritten-cases-api-openapi.yml
  format: yaml
  label: Ritten Cases API
  slug: ritten-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-cases-api-openapi.yml
- filename: ritten-contacts-api-openapi.yml
  format: yaml
  label: Ritten Contacts API
  slug: ritten-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-contacts-api-openapi.yml
- filename: ritten-encounters-api-openapi.yml
  format: yaml
  label: Ritten Encounters API
  slug: ritten-encounters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-encounters-api-openapi.yml
- filename: ritten-facilities-api-openapi.yml
  format: yaml
  label: Ritten Facilities API
  slug: ritten-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-facilities-api-openapi.yml
- filename: ritten-forms-api-openapi.yml
  format: yaml
  label: Ritten Forms API
  slug: ritten-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-forms-api-openapi.yml
- filename: ritten-insights-api-openapi.yml
  format: yaml
  label: Ritten Insights API
  slug: ritten-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-insights-api-openapi.yml
- filename: ritten-insurance-api-openapi.yml
  format: yaml
  label: Ritten Insurance API
  slug: ritten-insurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-insurance-api-openapi.yml
- filename: ritten-organizations-api-openapi.yml
  format: yaml
  label: Ritten Organizations API
  slug: ritten-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-organizations-api-openapi.yml
- filename: ritten-patients-api-openapi.yml
  format: yaml
  label: Ritten Patients API
  slug: ritten-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-patients-api-openapi.yml
- filename: ritten-programs-api-openapi.yml
  format: yaml
  label: Ritten Programs API
  slug: ritten-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-programs-api-openapi.yml
- filename: ritten-tasks-api-openapi.yml
  format: yaml
  label: Ritten Tasks API
  slug: ritten-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-tasks-api-openapi.yml
- filename: ritten-users-api-openapi.yml
  format: yaml
  label: Ritten Users API
  slug: ritten-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-users-api-openapi.yml
- filename: ritten-webhooks-api-openapi.yml
  format: yaml
  label: Ritten Webhooks API
  slug: ritten-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-webhooks-api-openapi.yml
- filename: ritten-oauth-api-openapi.yml
  format: yaml
  label: Ritten OAUTH API
  slug: ritten-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ritten/openapi/ritten-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF THE INDIVIDUAL SIGNING THE ORDER FORM OR SOW FOR PROVIDER IS SIGNING ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE AUTHORITY TO BIND THAT COMPANY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not medical advice
    text: THE RITTEN PLATFORM IS NOT INTENDED TO BE USED AS MEDICAL ADVICE, DIAGNOSIS, OR TREATMENT OF ANY MEDICAL CONDITION OR HEALTH PROBLEM
  - summary: BAA required for PHI
    text: use the Ritten Platform to store or Process any PHI without having first entered into the Business Associate Agreement with Ritten
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
name: Ritten
provenance_date: '2026-11-10'
provider_name: Ritten
provider_slug: ritten
slug: ritten-eligibility
source_date: '2026-11-10'
source_filename: ritten-eligibility.yml
source_heading: Eligibility
source_page: https://www.ritten.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ritten\naid: ritten\nurl: https://www.ritten.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF THE INDIVIDUAL SIGNING THE ORDER FORM OR SOW FOR PROVIDER IS SIGNING ON BEHALF OF A COMPANY OR OTHER\n    LEGAL ENTITY, SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE AUTHORITY TO BIND THAT COMPANY\nrestricted_uses:\n- summary: Not medical advice\n  text: THE RITTEN PLATFORM IS NOT INTENDED TO BE USED AS MEDICAL ADVICE, DIAGNOSIS, OR TREATMENT OF ANY MEDICAL\n    CONDITION OR HEALTH PROBLEM\n- summary: BAA required for\
  \ PHI\n  text: use the Ritten Platform to store or Process any PHI without having first entered into the Business Associate\n    Agreement with Ritten\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ritten/eligibility/ritten-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ritten's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Behavioral Health
- Electronic Health Records
- Healthcare
- Practice Management
- HIPAA
- Revenue Cycle Management
- Clinical Documentation
- Telehealth
- OpenAPI
- Webhook
- Behavioral Health API
- Substance Use Treatment
- 42 CFR Part 2
- Mental Health
---
