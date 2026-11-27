---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if Customer is a corporation, governmental organization, or other legal entity, you have the right, power, and authority to enter into this agreement on behalf of Customer
    type: business
  minimum_age:
    text: (i) YOU ARE OF LEGAL AGE TO ENTER INTO A BINDING AGREEMENT
    value: null
  restricted_uses:
  - summary: No PHI without Business Associate Agreement
    text: Customer will not store or process protected health information using the Software without first entering into a Business Associate Agreement with Momento.
  - summary: Export control compliance
    text: The Software and Documentation may be subject to US export control laws
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
name: Momento
provenance_date: '2026-11-10'
provider_name: Momento
provider_slug: momento
slug: momento-eligibility
source_date: '2026-11-10'
source_filename: momento-eligibility.yml
source_heading: Eligibility
source_page: https://www.gomomento.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Momento\naid: momento\nurl: https://www.gomomento.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if Customer is a corporation, governmental organization, or other legal entity, you have the right, power,\n    and authority to enter into this agreement on behalf of Customer\nrestricted_uses:\n- summary: No PHI without Business Associate Agreement\n  text: Customer will not store or process protected health information using the Software without first entering\n    into a Business Associate Agreement with Momento.\n\
  - summary: Export control compliance\n  text: The Software and Documentation may be subject to US export control laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: (i) YOU ARE OF LEGAL AGE TO ENTER INTO A BINDING AGREEMENT\n"
source_yaml_url: https://artifacts.apis.io/momento/eligibility/momento-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Momento's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Infrastructure
- Caching
- Serverless
- Cache
- Pub/Sub
- Messaging
- Event Bus
- Leaderboards
- Real-Time
- gRPC
- Developer Tools
---
