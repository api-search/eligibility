---
api_specs:
- filename: tenpace-com-review-router-setup-api-openapi.yml
  format: yaml
  label: tenpace-com Review Router setup API
  slug: tenpace-com-review-router-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenpace-com/openapi/tenpace-com-review-router-setup-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Organization administrators represent that they are authorized to purchase for their organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Health features not medical care
    text: Tenpace Health is a consumer wellness product, not medical care. It does not diagnose, treat, prescribe, or guarantee health outcomes and is not a substitute for a qualified healthcare professional.
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
name: tenpace-com
provenance_date: '2026-11-10'
provider_name: tenpace-com
provider_slug: tenpace-com
slug: tenpace-com-eligibility
source_date: '2026-11-10'
source_filename: tenpace-com-eligibility.yml
source_heading: Eligibility
source_page: https://tenpace.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tenpace-com\naid: tenpace-com\nurl: https://tenpace.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Organization administrators represent that they are authorized to purchase for their organization.\nrestricted_uses:\n- summary: Health features not medical care\n  text: Tenpace Health is a consumer wellness product, not medical care. It does not diagnose, treat, prescribe,\n    or guarantee health outcomes and is not a substitute for a qualified healthcare professional.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tenpace-com/eligibility/tenpace-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from tenpace-com's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Software-as-a-Service
- Productivity
- Workflows
- Integration
- Company
---
