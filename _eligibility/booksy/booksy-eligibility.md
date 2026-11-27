---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are based or reside in the United States or one of its territories.
  entity_types:
  - text: you are at least 18 years old
    type: individual
  - text: If you are a Service Provider or act on behalf of a Service Provider, these Terms of Service do not apply to you.
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Non-business use only
    text: You may use the Booksy for Customers App only for non-business, non-professional purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid, verified mobile phone number during Registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Booksy
provenance_date: '2026-11-09'
provider_name: Booksy
provider_slug: booksy
slug: booksy-eligibility
source_date: '2026-11-09'
source_filename: booksy-eligibility.yml
source_heading: Eligibility
source_page: https://booksy.com/en-us/p/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Booksy\naid: booksy\nurl: https://booksy.com/en-us/p/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are based or reside in the United States or one of its territories.\nentity_types:\n- type: individual\n  text: you are at least 18 years old\n- type: business\n  text: If you are a Service Provider or act on behalf of a Service Provider, these Terms of Service do not apply\n    to you.\nrestricted_uses:\n- summary: Non-business use only\n  text: You may use the Booksy for Customers App only for non-business, non-professional purposes.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid, verified mobile phone number during Registration.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/booksy/eligibility/booksy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Booksy's own page on 2026-11-09.
synthetic: false
tags:
- Beauty
- Wellness
- Booking
- Appointments
- Scheduling
- Marketplace
- Salon
- Barbershops
- Spas
- Payments
- Small Business
- Webhook
---
