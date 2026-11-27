---
api_specs:
- filename: dbt-accounts-api-openapi.yml
  format: yaml
  label: dbt Accounts API
  slug: dbt-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-accounts-api-openapi.yml
- filename: dbt-environments-api-openapi.yml
  format: yaml
  label: dbt Environments API
  slug: dbt-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-environments-api-openapi.yml
- filename: dbt-jobs-api-openapi.yml
  format: yaml
  label: dbt Jobs API
  slug: dbt-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-jobs-api-openapi.yml
- filename: dbt-metrics-api-openapi.yml
  format: yaml
  label: dbt Metrics API
  slug: dbt-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-metrics-api-openapi.yml
- filename: dbt-projects-api-openapi.yml
  format: yaml
  label: dbt Projects API
  slug: dbt-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-projects-api-openapi.yml
- filename: dbt-runs-api-openapi.yml
  format: yaml
  label: dbt Runs API
  slug: dbt-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-runs-api-openapi.yml
- filename: dbt-fastapi-api-openapi.yml
  format: yaml
  label: dbt Fast API
  slug: dbt-fastapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-fastapi-api-openapi.yml
- filename: dbt-private-api-openapi.yml
  format: yaml
  label: dbt Private API
  slug: dbt-private-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-private-api-openapi.yml
- filename: dbt-ready-api-openapi.yml
  format: yaml
  label: dbt Ready API
  slug: dbt-ready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-ready-api-openapi.yml
- filename: dbt-graph-ql-api-openapi.yml
  format: yaml
  label: dbt Graph QL API
  slug: dbt-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-graph-ql-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: will not access the Services from a country or territory that is itself the subject or target of comprehensive trade or economic sanctions (currently Cuba, Iran, North Korea, Syria, the Crimea region of Ukraine
  entity_types:
  - text: '"CLIENT" MEANS THE LEGAL ENTITY ON WHOSE BEHALF YOU ARE ENTERING INTO THESE TERMS'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PHI
    text: Client promises to not transfer to or request processing by dbt Labs or use with respect to the Services any protected health information (PHI)
  - summary: Sanctions and export compliance
    text: Client agrees to comply with, and shall not permit Authorized Users or any third parties to access or use the Services in violation of, U.S. export controls and economic and trade sanctions laws and regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: dbt Labs reserves the right to verify Authorized Users' relationship to Client
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: dbt
provenance_date: '2026-11-09'
provider_name: dbt
provider_slug: dbt
slug: dbt-eligibility
source_date: '2026-11-09'
source_filename: dbt-eligibility.yml
source_heading: Eligibility
source_page: https://www.getdbt.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dbt\naid: dbt\nurl: https://www.getdbt.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: will not access the Services from a country or territory that is itself the subject or target of comprehensive\n    trade or economic sanctions (currently Cuba, Iran, North Korea, Syria, the Crimea region of Ukraine\nentity_types:\n- type: business\n  text: '\"CLIENT\" MEANS THE LEGAL ENTITY ON WHOSE BEHALF YOU ARE ENTERING INTO THESE TERMS'\nrestricted_uses:\n- summary: No PHI\n  text: Client promises to not transfer to or request processing by dbt\
  \ Labs or use with respect to the Services\n    any protected health information (PHI)\n- summary: Sanctions and export compliance\n  text: Client agrees to comply with, and shall not permit Authorized Users or any third parties to access or use\n    the Services in violation of, U.S. export controls and economic and trade sanctions laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: dbt Labs reserves the right to verify Authorized Users' relationship to Client\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dbt/eligibility/dbt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from dbt's own page on 2026-11-09.
synthetic: false
tags:
- Analytics Engineering
- Data
- ELT
- Metrics
- Project
- SQL
- Transformation
---
