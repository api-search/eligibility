---
api_specs:
- filename: nizlo-com-nizlo-rmm-api-openapi.yml
  format: yaml
  label: Nizlo RMM API
  slug: nizlo-rmm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nizlo-com/openapi/nizlo-com-nizlo-rmm-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating or using a workspace, you agree to these terms on behalf of yourself and the organization you represent.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Malicious or unauthorized activity
    text: You must not use the service to conceal malicious activity, gain unauthorized access, collect credentials, evade security controls, or violate law or third-party rights.
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
name: Nizlo
provenance_date: '2026-11-10'
provider_name: Nizlo
provider_slug: nizlo-com
slug: nizlo-com-eligibility
source_date: '2026-11-10'
source_filename: nizlo-com-eligibility.yml
source_heading: Eligibility
source_page: https://nizlo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nizlo\naid: nizlo-com\nurl: https://nizlo.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By creating or using a workspace, you agree to these terms on behalf of yourself and the organization you\n    represent.\nrestricted_uses:\n- summary: Malicious or unauthorized activity\n  text: You must not use the service to conceal malicious activity, gain unauthorized access, collect credentials,\n    evade security controls, or violate law or third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nizlo-com/eligibility/nizlo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Nizlo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- RMM
- Remote Monitoring
- MSP
- Windows
---
