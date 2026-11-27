---
api_specs:
- filename: clawdcall-com-cc-api-openapi.yml
  format: yaml
  label: ClawdCall Cc API
  slug: clawdcall-com-cc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdcall-com/openapi/clawdcall-com-cc-api-openapi.yml
- filename: clawdcall-com-external-api-openapi.yml
  format: yaml
  label: ClawdCall External API
  slug: clawdcall-com-external-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdcall-com/openapi/clawdcall-com-external-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - NZ
    - AU
    text: Permitted launch regions United States, New Zealand, Australia
  entity_types:
  - text: 'You must: be at least 18 years old have legal authority to enter into these Terms'
    type: individual
  minimum_age:
    text: Minimum user age 18
    value: '18'
  restricted_uses:
  - summary: Bulk outreach and telemarketing
    text: The Service is not intended for bulk outreach, telemarketing, sales campaigns, political messaging, or automated contact lists.
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
name: ClawdCall
provenance_date: '2026-11-09'
provider_name: ClawdCall
provider_slug: clawdcall-com
slug: clawdcall-com-eligibility
source_date: '2026-11-09'
source_filename: clawdcall-com-eligibility.yml
source_heading: Eligibility
source_page: https://clawdcall.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClawdCall\naid: clawdcall-com\nurl: https://clawdcall.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - NZ\n  - AU\n  excluded: []\n  text: Permitted launch regions United States, New Zealand, Australia\nentity_types:\n- type: individual\n  text: 'You must: be at least 18 years old have legal authority to enter into these Terms'\nrestricted_uses:\n- summary: Bulk outreach and telemarketing\n  text: The Service is not intended for bulk outreach, telemarketing, sales campaigns, political messaging, or automated\n    contact lists.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Minimum user age 18\n"
source_yaml_url: https://artifacts.apis.io/clawdcall-com/eligibility/clawdcall-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ClawdCall's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Voice
- Automation
- Agents
- Telephony
---
