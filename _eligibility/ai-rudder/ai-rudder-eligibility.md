---
api_specs:
- filename: ai-rudder-openapi-generated.yml
  format: yaml
  label: AI Rudder API
  slug: ai-rudder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-rudder/openapi/_ae-authored/ai-rudder-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: currently Cuba, Iran, North Korea, Sudan and Syria
  entity_types:
  - text: If you open a user account on behalf of, or are otherwise using the Services on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  - text: If you are an individual using the Services for non-commercial purposes
    type: individual
  minimum_age:
    text: Any use or access to the Services by anyone under eighteen (18) years of age is strictly prohibited
    value: '18'
  restricted_uses:
  - summary: Emergency calling
    text: THE SERVICES ARE NOT INTENDED TO SUPPORT OR CARRY EMERGENCY CALLS TO ANY EMERGENCY SERVICES SUCH AS PUBLIC SAFETY ANSWERING POINTS
  - summary: Spam and unsolicited marketing
    text: engage in spamming or other unsolicited advertising, marketing or other activities, including, without limitation, any activities that violate the Calling Laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AI Rudder
provenance_date: '2026-11-09'
provider_name: AI Rudder
provider_slug: ai-rudder
slug: ai-rudder-eligibility
source_date: '2026-11-09'
source_filename: ai-rudder-eligibility.yml
source_heading: Eligibility
source_page: https://airudder.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Rudder\naid: ai-rudder\nurl: https://airudder.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: currently Cuba, Iran, North Korea, Sudan and Syria\nentity_types:\n- type: business\n  text: If you open a user account on behalf of, or are otherwise using the Services on behalf of an organization,\n    you are agreeing to these Terms for that organization\n- type: individual\n  text: If you are an individual using the Services for non-commercial purposes\nrestricted_uses:\n- summary: Emergency calling\n  text: THE SERVICES\
  \ ARE NOT INTENDED TO SUPPORT OR CARRY EMERGENCY CALLS TO ANY EMERGENCY SERVICES SUCH AS PUBLIC\n    SAFETY ANSWERING POINTS\n- summary: Spam and unsolicited marketing\n  text: engage in spamming or other unsolicited advertising, marketing or other activities, including, without limitation,\n    any activities that violate the Calling Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Services by anyone under eighteen (18) years of age is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/ai-rudder/eligibility/ai-rudder-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from AI Rudder's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Conversational AI
- Enterprise
- Automation
- Platform
---
