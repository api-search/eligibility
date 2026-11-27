---
api_specs:
- filename: hookdeploy-openapi-generated.yml
  format: yaml
  label: HookDeploy API
  slug: hookdeploy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hookdeploy/openapi/_ae-authored/hookdeploy-openapi-generated.yml
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents that it is not named on any U.S. government denied-party list and is not located in, under the control of, or a national or resident of any country subject to U.S. embargo or trade sanctions.
  entity_types:
  - text: The Service is intended for business and developer use.
    type: business
  - text: You must be at least eighteen (18) years of age and have the legal capacity to enter into contracts in your jurisdiction.
    type: individual
  - text: If Customer is a U.S. government entity or agency, the Service qualifies as
    type: government
  minimum_age:
    text: You must be at least eighteen (18) years of age and have the legal capacity to enter into contracts in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: Involves high-risk activities where failure could cause death, serious personal injury, or severe property or environmental damage.
  - summary: Sensitive regulated data
    text: 'Customer acknowledges that the Service is not designed or certified for the storage or processing of: (a) protected health information subject to HIPAA;'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: SnapStack reserves the right to request proof of age or authority at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HookDeploy
provenance_date: '2026-11-09'
provider_name: HookDeploy
provider_slug: hookdeploy
slug: hookdeploy-eligibility
source_date: '2026-11-09'
source_filename: hookdeploy-eligibility.yml
source_heading: Eligibility
source_page: https://hookdeploy.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HookDeploy\naid: hookdeploy\nurl: https://hookdeploy.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents that it is not named on any U.S. government denied-party list and is not located in,\n    under the control of, or a national or resident of any country subject to U.S. embargo or trade sanctions.\nentity_types:\n- type: business\n  text: The Service is intended for business and developer use.\n- type: individual\n  text: You must be at least eighteen (18) years of age and have the legal capacity to enter into contracts in your\n    jurisdiction.\n-\
  \ type: government\n  text: If Customer is a U.S. government entity or agency, the Service qualifies as\nrestricted_uses:\n- summary: High-risk activities\n  text: Involves high-risk activities where failure could cause death, serious personal injury, or severe property\n    or environmental damage.\n- summary: Sensitive regulated data\n  text: 'Customer acknowledges that the Service is not designed or certified for the storage or processing of: (a)\n    protected health information subject to HIPAA;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: SnapStack reserves the right to request proof of age or authority at any time.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age and have the legal capacity to enter into contracts in your\n    jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/hookdeploy/eligibility/hookdeploy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from HookDeploy's own page on 2026-11-09.
synthetic: false
tags:
- Webhook
- PrivateInfrastructure
- Security
- Integration
- Developer Tools
---
