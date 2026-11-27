---
api_specs:
- filename: openenvoy-job-api-openapi.yml
  format: yaml
  label: OpenEnvoy Job API
  slug: openenvoy-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openenvoy/openapi/openenvoy-job-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ANY INDIVIDUAL THAT ACCEPTS THIS AGREEMENT OR OTHERWISE ACCESSES OR USES ANY OPENENVOY PRODUCT ON BEHALF OF OR FOR A COMPANY, BUSINESS OR LEGAL ENTITY
    type: business
  - text: If Customer is an agency, department, or other entity of any government, the use, duplication, reproduction, release, modification, disclosure, or transfer of any OpenEnvoy Products, or any related documentation of any kind, including technical data, software, and manuals, is restricted by the terms of this Agreement.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business purposes only
    text: for its internal business purposes only
  - summary: No personal data upload
    text: upload any personal data or personally identifiable information to any of the OpenEnvoy Products.
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
name: OpenEnvoy
provenance_date: '2026-11-10'
provider_name: OpenEnvoy
provider_slug: openenvoy
slug: openenvoy-eligibility
source_date: '2026-11-10'
source_filename: openenvoy-eligibility.yml
source_heading: Eligibility
source_page: https://www.openenvoy.com/services-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenEnvoy\naid: openenvoy\nurl: https://www.openenvoy.com/services-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: ANY INDIVIDUAL THAT ACCEPTS THIS AGREEMENT OR OTHERWISE ACCESSES OR USES ANY OPENENVOY PRODUCT ON BEHALF\n    OF OR FOR A COMPANY, BUSINESS OR LEGAL ENTITY\n- type: government\n  text: If Customer is an agency, department, or other entity of any government, the use, duplication, reproduction,\n    release, modification, disclosure, or transfer of any OpenEnvoy Products, or any related documentation of any\n   \
  \ kind, including technical data, software, and manuals, is restricted by the terms of this Agreement.\nrestricted_uses:\n- summary: Internal business purposes only\n  text: for its internal business purposes only\n- summary: No personal data upload\n  text: upload any personal data or personally identifiable information to any of the OpenEnvoy Products.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openenvoy/eligibility/openenvoy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from OpenEnvoy's own page on 2026-11-10.
synthetic: false
tags:
- Accounts Payable
- Accounts Receivable
- Invoice Processing
- Finance Automation
- Accounting
- Procure-to-Pay
- Document Processing
- Artificial Intelligence
- ERP Integration
- Spend Management
- Procurement
---
