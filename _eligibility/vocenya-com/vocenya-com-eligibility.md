---
api_specs:
- filename: api.json
  format: json
  label: Vocenya API
  slug: vocenya-api
  spec_type: OpenAPI
  url: https://vocenya.com/docs/api.json
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Serving New Jersey, New York City and businesses across the US.
  entity_types:
  - text: If you use the Services for a business, you confirm you are authorized to accept these Terms for that business, and "you" means the business.
    type: business
  - text: By creating an account, starting a trial or using the Services, you agree to these Terms.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Protected health information
    text: until then, and whenever you have not accepted it, you must not use the Services to process protected health information.
  - summary: Emergencies
    text: The Services are not an emergency service and must not be relied on for emergencies.
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
name: vocenya-com
provenance_date: '2026-11-10'
provider_name: vocenya-com
provider_slug: vocenya-com
slug: vocenya-com-eligibility
source_date: '2026-11-10'
source_filename: vocenya-com-eligibility.yml
source_heading: Eligibility
source_page: https://vocenya.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: vocenya-com\naid: vocenya-com\nurl: https://vocenya.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Serving New Jersey, New York City and businesses across the US.\nentity_types:\n- type: business\n  text: If you use the Services for a business, you confirm you are authorized to accept these Terms for that business,\n    and \"you\" means the business.\n- type: individual\n  text: By creating an account, starting a trial or using the Services, you agree to these Terms.\nrestricted_uses:\n- summary: Protected health information\n  text: until then, and whenever you\
  \ have not accepted it, you must not use the Services to process protected health\n    information.\n- summary: Emergencies\n  text: The Services are not an emergency service and must not be relied on for emergencies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vocenya-com/eligibility/vocenya-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from vocenya-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Communications
- Customer Service
- Automation
- Voice
---
