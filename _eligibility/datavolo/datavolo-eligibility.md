---
claim_count: 1
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
  - summary: Non-commercial use of responses
    text: All service responses are provided only for your personal use for non-commercial purposes, without any additional rights.
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
name: Datavolo
provenance_date: '2026-11-09'
provider_name: Datavolo
provider_slug: datavolo
slug: datavolo-eligibility
source_date: '2026-11-09'
source_filename: datavolo-eligibility.yml
source_heading: Eligibility
source_page: https://datavolo.io/terms-of-use-agreement-for-the-datavolo-flow-generator-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datavolo\naid: datavolo\nurl: https://datavolo.io/terms-of-use-agreement-for-the-datavolo-flow-generator-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use of responses\n  text: All service responses are provided only for your personal use for non-commercial purposes, without any additional\n    rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datavolo/eligibility/datavolo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Datavolo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Pipeline
- Dataflows
- Apache NiFi
- Unstructured Data
- Generative AI
- Data Engineering
- Data Lineage
- ETL
- Snowflake
---
