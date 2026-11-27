---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of an entity, organization, or company (a "Subscribing Organization"), you represent and warrant that you have the authority to bind such Subscribing Organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: sell, sublicense, or otherwise transfer the access granted herein or any Materials (as defined in Section 12 below) other than to Affiliates
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
name: Qubole
provenance_date: '2026-11-10'
provider_name: Qubole
provider_slug: qubole
slug: qubole-eligibility
source_date: '2026-11-10'
source_filename: qubole-eligibility.yml
source_heading: Eligibility
source_page: https://us.qubole.com/TOS.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qubole\naid: qubole\nurl: https://us.qubole.com/TOS.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of an entity, organization, or company (a \"Subscribing Organization\"),\n    you represent and warrant that you have the authority to bind such Subscribing Organization\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: sell, sublicense, or otherwise transfer the access granted herein or any Materials (as defined in Section\n    12 below) other than to Affiliates\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qubole/eligibility/qubole-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Qubole's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Data Lake
- Big Data
- Analytics
- Spark
- Presto
- Hive
- Airflow
- Machine Learning
- Cloud
- Data Engineering
---
