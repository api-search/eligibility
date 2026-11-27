---
api_specs:
- filename: secondfactor-openapi-generated.yml
  format: yaml
  label: SecondFactor API
  slug: secondfactor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secondfactor/openapi/_ae-authored/secondfactor-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of a company or other legal entity, you represent that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Emergency or life-critical use
    text: The Services are not designed or intended for use in connection with emergency services, life-critical systems, or any use case where failure or delay of message delivery could result in death, personal injury, or property damage.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate, current, and complete information when creating an account, and keep it up to date.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SecondFactor
provenance_date: '2026-11-10'
provider_name: SecondFactor
provider_slug: secondfactor
slug: secondfactor-eligibility
source_date: '2026-11-10'
source_filename: secondfactor-eligibility.yml
source_heading: Eligibility
source_page: https://secondfactor.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SecondFactor\naid: secondfactor\nurl: https://secondfactor.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company or other legal entity, you represent that you have the authority\n    to bind that entity\nrestricted_uses:\n- summary: Emergency or life-critical use\n  text: The Services are not designed or intended for use in connection with emergency services, life-critical systems,\n    or any use case where failure or delay of message delivery could result in death, personal injury, or\
  \ property\n    damage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate, current, and complete information when creating an account, and keep it up to\n    date.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/secondfactor/eligibility/secondfactor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from SecondFactor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- OTP
- Authentication
- Multi-Channel
- Messaging
---
