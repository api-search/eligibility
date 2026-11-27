---
api_specs:
- filename: bountyoperator-com-openapi-generated.yml
  format: yaml
  label: Bounty Operator API
  slug: bountyoperator-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bountyoperator-com/openapi/_ae-authored/bountyoperator-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One person per account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No attacks on targets
    text: Do not use the service to attack a target.
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
name: Bounty Operator
provenance_date: '2026-11-09'
provider_name: Bounty Operator
provider_slug: bountyoperator-com
slug: bountyoperator-com-eligibility
source_date: '2026-11-09'
source_filename: bountyoperator-com-eligibility.yml
source_heading: Eligibility
source_page: https://bountyoperator.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bounty Operator\naid: bountyoperator-com\nurl: https://bountyoperator.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One person per account.\nrestricted_uses:\n- summary: No attacks on targets\n  text: Do not use the service to attack a target.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bountyoperator-com/eligibility/bountyoperator-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Bounty Operator's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Bug Bounty
- Review
- Artificial Intelligence
---
