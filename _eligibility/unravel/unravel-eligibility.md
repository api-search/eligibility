---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the person or entity on behalf of which the terms and conditions of these Terms are being accepted ( “Customer” )
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law compliance
    text: Customer agrees to comply strictly with all U.S. export laws and assume sole responsibility for obtaining United States government export licenses to export or re-export as may be required.
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
name: Unravel
provenance_date: '2026-11-10'
provider_name: Unravel
provider_slug: unravel
slug: unravel-eligibility
source_date: '2026-11-10'
source_filename: unravel-eligibility.yml
source_heading: Eligibility
source_page: https://www.unraveldata.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unravel\naid: unravel\nurl: https://www.unraveldata.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the person or entity on behalf of which the terms and conditions of these Terms are being accepted ( “Customer”\n    )\nrestricted_uses:\n- summary: Export law compliance\n  text: Customer agrees to comply strictly with all U.S. export laws and assume sole responsibility for obtaining\n    United States government export licenses to export or re-export as may be required.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unravel/eligibility/unravel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Unravel's own page on 2026-11-10.
synthetic: false
tags:
- Data Observability
- FinOps
- DataOps
- Cost Optimization
- Databricks
- Snowflake
- BigQuery
- Monitoring
- Company
---
