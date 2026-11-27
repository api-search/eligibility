---
api_specs:
- filename: 3shake-accounts-api-openapi.yml
  format: yaml
  label: 3-shake Accounts API
  slug: 3shake-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3shake/openapi/3shake-accounts-api-openapi.yml
- filename: 3shake-auth-api-openapi.yml
  format: yaml
  label: 3-shake Auth API
  slug: 3shake-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3shake/openapi/3shake-auth-api-openapi.yml
- filename: 3shake-integrations-api-openapi.yml
  format: yaml
  label: 3-shake Integrations API
  slug: 3shake-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3shake/openapi/3shake-integrations-api-openapi.yml
- filename: 3shake-projects-api-openapi.yml
  format: yaml
  label: 3-shake Projects API
  slug: 3shake-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3shake/openapi/3shake-projects-api-openapi.yml
- filename: 3shake-workflows-api-openapi.yml
  format: yaml
  label: 3-shake Workflows API
  slug: 3shake-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3shake/openapi/3shake-workflows-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 本サービスの利用を申し込める者は法人に限るものとします。
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited conduct under Article 14
    text: 本サービス利用者は、本サービスの利用にあたり、以下の行為またはそれに類する行為をしてはならず、第三者にさせてはならないものとします。
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社はその申込みを承諾しない場合があります。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 3-shake
provenance_date: '2026-11-09'
provider_name: 3-shake
provider_slug: 3shake
slug: 3shake-eligibility
source_date: '2026-11-09'
source_filename: 3shake-eligibility.yml
source_heading: Eligibility
source_page: https://reckoner.io/term/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 3-shake\naid: 3shake\nurl: https://reckoner.io/term/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 本サービスの利用を申し込める者は法人に限るものとします。\nrestricted_uses:\n- summary: Prohibited conduct under Article 14\n  text: 本サービス利用者は、本サービスの利用にあたり、以下の行為またはそれに類する行為をしてはならず、第三者にさせてはならないものとします。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社はその申込みを承諾しない場合があります。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/3shake/eligibility/3shake-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from 3-shake's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SRE
- Data Integration
- ETL
- iPaaS
- Workflow Automation
- Vulnerability Scanning
- Attack Surface Management
- Cloud Security
- DevSecOps
- SBOM
- Kubernetes
- Japan
---
