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
  - summary: Not for hazardous fail-safe environments
    text: CUSTOMER ACKNOWLEDGES THAT THE SOFTWARE IS NOT DESIGNED OR INTENDED FOR USE IN HAZARDOUS ENVIRONMENTS REQUIRING FAIL-SAFE PERFORMANCE.
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
name: Tensor9
provenance_date: '2026-11-10'
provider_name: Tensor9
provider_slug: tensor9
slug: tensor9-eligibility
source_date: '2026-11-10'
source_filename: tensor9-eligibility.yml
source_heading: Eligibility
source_page: https://www.tensor9.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tensor9\naid: tensor9\nurl: https://www.tensor9.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for hazardous fail-safe environments\n  text: CUSTOMER ACKNOWLEDGES THAT THE SOFTWARE IS NOT DESIGNED OR INTENDED FOR USE IN HAZARDOUS ENVIRONMENTS REQUIRING\n    FAIL-SAFE PERFORMANCE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tensor9/eligibility/tensor9-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Tensor9's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Deployment
- BYOC
- Cloud Portability
- Infrastructure as Code
- Kubernetes
- On-Premises
- Security
- DevOps
- CLI
---
