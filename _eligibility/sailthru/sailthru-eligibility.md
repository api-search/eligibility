---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You enter into this Agreement or acquire the Services on behalf of an entity, You represent and warrant that You have the authority to accept this Agreement on the entity's behalf.
    type: business
  minimum_age:
    text: be at least 18 years old (or the age of majority in your state of residence, if greater)
    value: '18'
  restricted_uses:
  - summary: Sensitive PII
    text: Customer understands and acknowledges that the Services are not configured to process, receive, and/or store Sensitive PII.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: complete the registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sailthru
provenance_date: '2026-11-10'
provider_name: Sailthru
provider_slug: sailthru
slug: sailthru-eligibility
source_date: '2026-11-10'
source_filename: sailthru-eligibility.yml
source_heading: Eligibility
source_page: https://www.zetaglobal.com/former-marigold-now-zeta-services-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sailthru\naid: sailthru\nurl: https://www.zetaglobal.com/former-marigold-now-zeta-services-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You enter into this Agreement or acquire the Services on behalf of an entity, You represent and warrant\n    that You have the authority to accept this Agreement on the entity's behalf.\nrestricted_uses:\n- summary: Sensitive PII\n  text: Customer understands and acknowledges that the Services are not configured to process, receive, and/or store\n    Sensitive PII.\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: complete the registration process\nminimum_age:\n  value: '18'\n  text: be at least 18 years old (or the age of majority in your state of residence, if greater)\n"
source_yaml_url: https://artifacts.apis.io/sailthru/eligibility/sailthru-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Sailthru's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email Marketing
- Marketing Automation
- Personalization
- Customer Data Platform
- Transactional Email
- SMS
- Push Notifications
- Retail
- Media and Publishing
---
