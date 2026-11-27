---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: HumanQ controls and operates the Platform from the state of California. HumanQ does not represent that the Platform or any materials on the Platform are appropriate or available for use in other locations outside of the United States.
  entity_types:
  - text: You represent and certify that you are of legal age to form a binding contract
    type: individual
  minimum_age:
    text: To register an Account with HumanQ, you must be 18 years or over.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons and terror/hate groups
    text: You may not create an Account if you are a member of a terror or hate group. You may not purchase any goods or services from us if you reside in a country subject to a comprehensive U.S. sanctions program or are a Specifically Designated National (SDN)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To do so, you must provide an email address and a valid payment method.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HumanQ
provenance_date: '2026-11-09'
provider_name: HumanQ
provider_slug: humanq
slug: humanq-eligibility
source_date: '2026-11-09'
source_filename: humanq-eligibility.yml
source_heading: Eligibility
source_page: https://humanq.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HumanQ\naid: humanq\nurl: https://humanq.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: HumanQ controls and operates the Platform from the state of California. HumanQ does not represent that the\n    Platform or any materials on the Platform are appropriate or available for use in other locations outside of\n    the United States.\nentity_types:\n- type: individual\n  text: You represent and certify that you are of legal age to form a binding contract\nrestricted_uses:\n- summary: Sanctioned persons and terror/hate groups\n  text: You may not create an Account\
  \ if you are a member of a terror or hate group. You may not purchase any goods\n    or services from us if you reside in a country subject to a comprehensive U.S. sanctions program or are a Specifically\n    Designated National (SDN)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To do so, you must provide an email address and a valid payment method.\nminimum_age:\n  value: '18'\n  text: To register an Account with HumanQ, you must be 18 years or over.\n"
source_yaml_url: https://artifacts.apis.io/humanq/eligibility/humanq-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from HumanQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Execution
- Facilitation
- Team Productivity
- Leadership Development
- Enterprise Software
- Coaching
---
