---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to use the Service.
    type: individual
  - text: If you are using TryWired on behalf of a company or other organization, you represent that you have authority to bind that organization to these Terms, and "you" refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use the Service.
    value: '18'
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
name: TryWired
provenance_date: '2026-11-10'
provider_name: TryWired
provider_slug: trywired
slug: trywired-eligibility
source_date: '2026-11-10'
source_filename: trywired-eligibility.yml
source_heading: Eligibility
source_page: https://trywired.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TryWired\naid: trywired\nurl: https://trywired.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Service.\n- type: business\n  text: If you are using TryWired on behalf of a company or other organization, you represent that you have authority\n    to bind that organization to these Terms, and \"you\" refers to that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/trywired/eligibility/trywired-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from TryWired's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Integration
- HubSpot
- Telegram
- Twilio
- SMS
---
