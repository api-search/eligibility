---
api_specs:
- filename: altinity-auth-api-openapi.yml
  format: yaml
  label: Altinity Auth API
  slug: altinity-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altinity/openapi/altinity-auth-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No HIPAA data
    text: Customer agrees not to upload to the Service any HIPAA data.
  - summary: Export control compliance
    text: Customer represents and warrants that it is not listed on any U.S. government list of prohibited or restricted parties
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
name: Altinity
provenance_date: '2026-11-09'
provider_name: Altinity
provider_slug: altinity
slug: altinity-eligibility
source_date: '2026-11-09'
source_filename: altinity-eligibility.yml
source_heading: Eligibility
source_page: https://altinity.com/wp-content/uploads/2022/09/Altinity.Cloud-Terms-of-Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Altinity\naid: altinity\nurl: https://altinity.com/wp-content/uploads/2022/09/Altinity.Cloud-Terms-of-Service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No HIPAA data\n  text: Customer agrees not to upload to the Service any HIPAA data.\n- summary: Export control compliance\n  text: Customer represents and warrants that it is not listed on any U.S. government list of prohibited or restricted\n    parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/altinity/eligibility/altinity-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Altinity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Big Data
- ClickHouse
- Analytics
- Database
- Managed Cloud
- Kubernetes
- Real-Time Analytics
- Open Source
---
