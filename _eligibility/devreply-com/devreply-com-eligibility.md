---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: DevReply is for businesses and developers, not consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use limits
    text: 'Don''t use DevReply to: send spam, unsolicited marketing, or messages your users didn''t ask for'
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
name: devreply-com
provenance_date: '2026-11-09'
provider_name: devreply-com
provider_slug: devreply-com
slug: devreply-com-eligibility
source_date: '2026-11-09'
source_filename: devreply-com-eligibility.yml
source_heading: Eligibility
source_page: https://devreply.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: devreply-com\naid: devreply-com\nurl: https://devreply.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: DevReply is for businesses and developers, not consumers.\nrestricted_uses:\n- summary: Acceptable use limits\n  text: 'Don''t use DevReply to: send spam, unsolicited marketing, or messages your users didn''t ask for'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/devreply-com/eligibility/devreply-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from devreply-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Chat
- Customer Service
- Mobile
- Web
- Developer Tools
---
