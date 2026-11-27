---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - SD
    - SY
    served: []
    text: not resident of, or otherwise domiciled in, any countries set forth on the State Sponsored Terrorism List ... (which currently includes Iran, Sudan and Syria)
  entity_types:
  - text: on behalf of you or your organization (hereinafter, the "Customer")
    type: business
  minimum_age:
    text: the individual creating such Account is (i) at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited export end uses
    text: Customer will not use the Software for a Prohibited Use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Creation of a valid Account requires providing a valid email address
excluded_countries:
- IR
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: APIANT
provenance_date: '2026-11-09'
provider_name: APIANT
provider_slug: apiant
slug: apiant-eligibility
source_date: '2026-11-09'
source_filename: apiant-eligibility.yml
source_heading: Eligibility
source_page: https://apiant.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIANT\naid: apiant\nurl: https://apiant.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - SD\n  - SY\n  text: not resident of, or otherwise domiciled in, any countries set forth on the State Sponsored Terrorism List\n    ... (which currently includes Iran, Sudan and Syria)\nentity_types:\n- type: business\n  text: on behalf of you or your organization (hereinafter, the \"Customer\")\nrestricted_uses:\n- summary: Prohibited export end uses\n  text: Customer will not use the Software for a Prohibited Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: Creation of a valid Account requires providing a valid email address\nminimum_age:\n  value: '18'\n  text: the individual creating such Account is (i) at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/apiant/eligibility/apiant-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from APIANT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- Artificial Intelligence
- Automation
- Software-as-a-Service
---
