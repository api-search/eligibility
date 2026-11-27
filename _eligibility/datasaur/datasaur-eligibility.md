---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Service on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: US export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations of the United States Department of Commerce
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
name: Datasaur
provenance_date: '2026-11-09'
provider_name: Datasaur
provider_slug: datasaur
slug: datasaur-eligibility
source_date: '2026-11-09'
source_filename: datasaur-eligibility.yml
source_heading: Eligibility
source_page: https://datasaur.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datasaur\naid: datasaur\nurl: https://datasaur.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Service on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company\nrestricted_uses:\n- summary: US export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software or anything related thereto, or any direct product thereof in violation of any\
  \ restrictions, laws or\n    regulations of the United States Department of Commerce\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datasaur/eligibility/datasaur-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Datasaur's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Saas
- Data Labeling
- Artificial Intelligence
- Machine Learning
- LLM
- Natural Language Processing
- Data Annotation
- GraphQL
---
