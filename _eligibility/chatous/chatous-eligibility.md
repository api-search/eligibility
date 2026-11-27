---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Accessing the Services from territories where its use is illegal is prohibited.
  entity_types:
  - text: If you are under 13 years of age, you are not authorized to use the Service, without registering. If you are under the age of 18, you may use the Service, with or without registering, only with the approval of your parent or guardian.
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, without registering.
    value: '13'
  verification:
    approval_required: false
    kyb: null
    kyc: false
    text: Chatous does not screen or inquire into the background of any users of the site or services, nor does Chatous make any attempt to verify the statements of users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: chatous
provenance_date: '2026-11-09'
provider_name: chatous
provider_slug: chatous
slug: chatous-eligibility
source_date: '2026-11-09'
source_filename: chatous-eligibility.yml
source_heading: Eligibility
source_page: https://chatous.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: chatous\naid: chatous\nurl: https://chatous.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Accessing the Services from territories where its use is illegal is prohibited.\nentity_types:\n- type: individual\n  text: If you are under 13 years of age, you are not authorized to use the Service, without registering. If you\n    are under the age of 18, you may use the Service, with or without registering, only with the approval of your\n    parent or guardian.\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: false\n  text: Chatous does not\
  \ screen or inquire into the background of any users of the site or services, nor does Chatous\n    make any attempt to verify the statements of users\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, without registering.\n"
source_yaml_url: https://artifacts.apis.io/chatous/eligibility/chatous-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from chatous's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Messaging
- Chat
- Social
- Consumer
- Video Chat
- Mobile
---
