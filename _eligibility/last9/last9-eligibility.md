---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This TOS is based upon the subscription agreement executed between Licensor and Your Employer (herein referred to as “Employer”) for the use of services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No breach of law or HIPAA violations
    text: use the Platform in breach or violation of any applicable laws, including laws related to data privacy, like the Health Insurance Portability and Accountability Act (“HIPAA”), as applicable.
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
name: Last9
provenance_date: '2026-11-09'
provider_name: Last9
provider_slug: last9
slug: last9-eligibility
source_date: '2026-11-09'
source_filename: last9-eligibility.yml
source_heading: Eligibility
source_page: https://last9.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Last9\naid: last9\nurl: https://last9.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This TOS is based upon the subscription agreement executed between Licensor and Your Employer (herein referred\n    to as “Employer”) for the use of services\nrestricted_uses:\n- summary: No breach of law or HIPAA violations\n  text: use the Platform in breach or violation of any applicable laws, including laws related to data privacy,\n    like the Health Insurance Portability and Accountability Act (“HIPAA”), as applicable.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/last9/eligibility/last9-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Last9's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Observability
- Monitoring
- DevOps
- Artificial Intelligence
---
