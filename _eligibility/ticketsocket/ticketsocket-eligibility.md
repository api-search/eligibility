---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not eligible to use the Website or Services if doing so would violate any applicable law or regulation, including but not limited to U.S. export controls or restrictions.
  entity_types:
  - text: The Website is intended for use by Merchant Users.
    type: business
  - text: 'Visitor : any individual who visits the Website.'
    type: individual
  minimum_age:
    text: You must be over the age of 18 to register an account on the Website or use the Services.
    value: '18'
  restricted_uses:
  - summary: Not for consumers
    text: The Website is intended for use by Merchant Users. It is not intended for use by Consumers.
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
name: TicketSocket
provenance_date: '2026-11-10'
provider_name: TicketSocket
provider_slug: ticketsocket
slug: ticketsocket-eligibility
source_date: '2026-11-10'
source_filename: ticketsocket-eligibility.yml
source_heading: Eligibility
source_page: https://ticketsocket.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TicketSocket\naid: ticketsocket\nurl: https://ticketsocket.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not eligible to use the Website or Services if doing so would violate any applicable law or regulation,\n    including but not limited to U.S. export controls or restrictions.\nentity_types:\n- type: business\n  text: The Website is intended for use by Merchant Users.\n- type: individual\n  text: 'Visitor : any individual who visits the Website.'\nrestricted_uses:\n- summary: Not for consumers\n  text: The Website is intended for use by Merchant Users.\
  \ It is not intended for use by Consumers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be over the age of 18 to register an account on the Website or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/ticketsocket/eligibility/ticketsocket-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TicketSocket's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Event
- Ticketing
- Marketing
---
