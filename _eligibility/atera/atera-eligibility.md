---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether individually or on behalf of your employer or another legal entity
    type: individual
  - text: If you are entering into these Terms on behalf of your employer or another legal entity, you represent and warrant that you have full authority to bind said employer or other legal entity to these Terms.
    type: business
  minimum_age:
    text: (b) are at least eighteen (18) years old or of the legal age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Sensitive data submission
    text: you represent, warrant, and covenant not to Provide (or cause to be Provided), Atera and/or the Services with, any special categories of personal data
  - summary: Competitors
    text: represent and warrant that you are not, a competitor of Atera
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
name: Atera
provenance_date: '2026-11-09'
provider_name: Atera
provider_slug: atera
slug: atera-eligibility
source_date: '2026-11-09'
source_filename: atera-eligibility.yml
source_heading: Eligibility
source_page: https://www.atera.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atera\naid: atera\nurl: https://www.atera.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: whether individually or on behalf of your employer or another legal entity\n- type: business\n  text: If you are entering into these Terms on behalf of your employer or another legal entity, you represent and\n    warrant that you have full authority to bind said employer or other legal entity to these Terms.\nrestricted_uses:\n- summary: Sensitive data submission\n  text: you represent, warrant, and covenant\
  \ not to Provide (or cause to be Provided), Atera and/or the Services\n    with, any special categories of personal data\n- summary: Competitors\n  text: represent and warrant that you are not, a competitor of Atera\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (b) are at least eighteen (18) years old or of the legal age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/atera/eligibility/atera-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Atera's own page on 2026-11-09.
synthetic: false
tags:
- IT Management
- RMM
- PSA
- Help Desk
- Ticketing
- Patch Management
- Remote Monitoring
- Endpoint Management
- MSP
- Network Discovery
- Alerts
- Devices
- Billing
- Webhook
- Artificial Intelligence
---
