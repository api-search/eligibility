---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of an entity, this Agreement shall be expressly binding on all employees, directors and officers, agents, and assigns who access or use the SaaS Services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export compliance
    text: Customer shall not permit Users to access or use Services in violation of any U. S. export embargo, prohibition or restriction.
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
name: Appviewx
provenance_date: '2026-11-09'
provider_name: Appviewx
provider_slug: appviewx
slug: appviewx-eligibility
source_date: '2026-11-09'
source_filename: appviewx-eligibility.yml
source_heading: Eligibility
source_page: https://www.appviewx.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appviewx\naid: appviewx\nurl: https://www.appviewx.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of an entity, this Agreement shall be expressly binding\n    on all employees, directors and officers, agents, and assigns who access or use the SaaS Services.\nrestricted_uses:\n- summary: Export compliance\n  text: Customer shall not permit Users to access or use Services in violation of any U. S. export embargo, prohibition\n    or restriction.\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appviewx/eligibility/appviewx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Appviewx's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Identity
- PKI
- Certificate Management
- Artificial Intelligence
---
