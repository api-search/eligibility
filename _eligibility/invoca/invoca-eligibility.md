---
api_specs:
- filename: invoca-messages-api-openapi.yml
  format: yaml
  label: Invoca Messages API
  slug: invoca-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoca/openapi/invoca-messages-api-openapi.yml
- filename: invoca-phone-numbers-api-openapi.yml
  format: yaml
  label: Invoca Phone Numbers API
  slug: invoca-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoca/openapi/invoca-phone-numbers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Services are offered only to parties that can legally enter into and sign binding contracts.
    type: business
  minimum_age:
    text: you represent and warrant to us that you are age eighteen (18) or older and the authorized signatory.
    value: '18'
  restricted_uses:
  - summary: No calls to 911 via the Services
    text: EMERGENCY SERVICES CANNOT BE ACCESSED BY ORIGINATING CALLS TO 911 USING THE SERVICES.
  - summary: No content offering products to children under 13
    text: You shall not use the Services to offer products or services to, or to collect information from, any child under the age of 13.
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
name: Invoca
provenance_date: '2026-11-09'
provider_name: Invoca
provider_slug: invoca
slug: invoca-eligibility
source_date: '2026-11-09'
source_filename: invoca-eligibility.yml
source_heading: Eligibility
source_page: https://www.invoca.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Invoca\naid: invoca\nurl: https://www.invoca.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Services are offered only to parties that can legally enter into and sign binding contracts.\nrestricted_uses:\n- summary: No calls to 911 via the Services\n  text: EMERGENCY SERVICES CANNOT BE ACCESSED BY ORIGINATING CALLS TO 911 USING THE SERVICES.\n- summary: No content offering products to children under 13\n  text: You shall not use the Services to offer products or services to, or to collect information from,\
  \ any child\n    under the age of 13.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant to us that you are age eighteen (18) or older and the authorized signatory.\n"
source_yaml_url: https://artifacts.apis.io/invoca/eligibility/invoca-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Invoca's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Call Tracking
- Conversation Intelligence
- Marketing
- Attribution
- Revenue
- Telephony
- Analytics
---
