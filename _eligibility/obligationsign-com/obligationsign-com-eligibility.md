---
api_specs:
- filename: obligationsign-com-openapi-generated.yml
  format: yaml
  label: obligationsign-com API
  slug: obligationsign-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/obligationsign-com/openapi/_ae-authored/obligationsign-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Commercial deployment (self-hosted) Commercial licence required
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competing clearinghouse services
    text: Use of the codebase or protocol implementation to build a competing clearinghouse service is not permitted without a separate agreement
  - summary: Internal enterprise evaluation limited to trial
    text: Internal enterprise evaluation Trial only
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
name: obligationsign-com
provenance_date: '2026-11-10'
provider_name: obligationsign-com
provider_slug: obligationsign-com
slug: obligationsign-com-eligibility
source_date: '2026-11-10'
source_filename: obligationsign-com-eligibility.yml
source_heading: Eligibility
source_page: https://obligationsign.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: obligationsign-com\naid: obligationsign-com\nurl: https://obligationsign.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Commercial deployment (self-hosted) Commercial licence required\nrestricted_uses:\n- summary: Competing clearinghouse services\n  text: Use of the codebase or protocol implementation to build a competing clearinghouse service is not permitted\n    without a separate agreement\n- summary: Internal enterprise evaluation limited to trial\n  text: Internal enterprise evaluation Trial only\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/obligationsign-com/eligibility/obligationsign-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from obligationsign-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Governance
- Security
- Infrastructure
---
