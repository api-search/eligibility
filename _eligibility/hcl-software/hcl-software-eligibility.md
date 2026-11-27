---
api_specs:
- filename: hcl-software-stwebapi-api-openapi.yml
  format: yaml
  label: HCLSoftware Stwebapi API
  slug: hcl-software-stwebapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hcl-software/openapi/hcl-software-stwebapi-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The membership of this Website is available to all filling the website Contact Us, Event Registration or Information Download form(s).
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Impersonation or misrepresentation
    text: Falsely state, impersonate or otherwise misrepresent your identity in any manner whatsoever
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: HCL may refuse membership to any user for any or no reason without prior notice.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HCLSoftware
provenance_date: '2026-11-09'
provider_name: HCLSoftware
provider_slug: hcl-software
slug: hcl-software-eligibility
source_date: '2026-11-09'
source_filename: hcl-software-eligibility.yml
source_heading: Eligibility
source_page: https://www.hcl-software.com/legal/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HCLSoftware\naid: hcl-software\nurl: https://www.hcl-software.com/legal/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: The membership of this Website is available to all filling the website Contact Us, Event Registration or\n    Information Download form(s).\nrestricted_uses:\n- summary: Impersonation or misrepresentation\n  text: Falsely state, impersonate or otherwise misrepresent your identity in any manner whatsoever\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: HCL may refuse membership to\
  \ any user for any or no reason without prior notice.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hcl-software/eligibility/hcl-software-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from HCLSoftware's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software
- Enterprise
- Artificial Intelligence
- Cloud
---
