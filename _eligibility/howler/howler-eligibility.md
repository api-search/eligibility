---
api_specs:
- filename: howler-artists-api-openapi.yml
  format: yaml
  label: Howler Artists API
  slug: howler-artists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-artists-api-openapi.yml
- filename: howler-assign-ticket-api-openapi.yml
  format: yaml
  label: Howler Assign Ticket API
  slug: howler-assign-ticket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-assign-ticket-api-openapi.yml
- filename: howler-bank-account-api-openapi.yml
  format: yaml
  label: Howler Bank Account API
  slug: howler-bank-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-bank-account-api-openapi.yml
- filename: howler-basic-authentication-api-openapi.yml
  format: yaml
  label: Howler Basic Authentication API
  slug: howler-basic-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-basic-authentication-api-openapi.yml
- filename: howler-cashless-tags-api-openapi.yml
  format: yaml
  label: Howler Cashless Tags API
  slug: howler-cashless-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-cashless-tags-api-openapi.yml
- filename: howler-cashout-api-openapi.yml
  format: yaml
  label: Howler Cashout API
  slug: howler-cashout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-cashout-api-openapi.yml
- filename: howler-email-otp-api-openapi.yml
  format: yaml
  label: Howler Email OTP API
  slug: howler-email-otp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-email-otp-api-openapi.yml
- filename: howler-events-api-openapi.yml
  format: yaml
  label: Howler Events API
  slug: howler-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-events-api-openapi.yml
- filename: howler-third-party-oauth-api-openapi.yml
  format: yaml
  label: Howler Third Party OAuth API
  slug: howler-third-party-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-third-party-oauth-api-openapi.yml
- filename: howler-tickets-api-openapi.yml
  format: yaml
  label: Howler Tickets API
  slug: howler-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-tickets-api-openapi.yml
- filename: howler-top-up-api-openapi.yml
  format: yaml
  label: Howler Top Up API
  slug: howler-top-up-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-top-up-api-openapi.yml
- filename: howler-top-up-cashless-tag-api-openapi.yml
  format: yaml
  label: Howler Top Up Cashless Tag API
  slug: howler-top-up-cashless-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-top-up-cashless-tag-api-openapi.yml
- filename: howler-top-up-ticket-api-openapi.yml
  format: yaml
  label: Howler Top Up Ticket API
  slug: howler-top-up-ticket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-top-up-ticket-api-openapi.yml
- filename: howler-topupables-api-openapi.yml
  format: yaml
  label: Howler Topupables API
  slug: howler-topupables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-topupables-api-openapi.yml
- filename: howler-transfer-ticket-api-openapi.yml
  format: yaml
  label: Howler Transfer Ticket API
  slug: howler-transfer-ticket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-transfer-ticket-api-openapi.yml
- filename: howler-user-api-openapi.yml
  format: yaml
  label: Howler User API
  slug: howler-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-user-api-openapi.yml
- filename: howler-oauth-api-openapi.yml
  format: yaml
  label: Howler O Auth API
  slug: howler-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howler/openapi/howler-oauth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: only users above the age of 18 (eighteen) may use the Services or provide their personal information to us for processing.
    type: individual
  - text: if you are a business, such as a Howler merchant who has subscribed for any of our payment solutions (“ Howler Products ”) and any of our merchant services (“ Merchant Services ”), our General Service Terms will apply;
    type: business
  minimum_age:
    text: only users above the age of 18 (eighteen) may use the Services or provide their personal information to us for processing.
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: You must not use this Website for any illegal activity or if you do not agree to the Website Terms.
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
name: Howler
provenance_date: '2026-11-09'
provider_name: Howler
provider_slug: howler
slug: howler-eligibility
source_date: '2026-11-09'
source_filename: howler-eligibility.yml
source_heading: Eligibility
source_page: https://www.howler.co.za/terms_and_conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Howler\naid: howler\nurl: https://www.howler.co.za/terms_and_conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: only users above the age of 18 (eighteen) may use the Services or provide their personal information to\n    us for processing.\n- type: business\n  text: if you are a business, such as a Howler merchant who has subscribed for any of our payment solutions (“\n    Howler Products ”) and any of our merchant services (“ Merchant Services ”), our General Service Terms will\n    apply;\nrestricted_uses:\n- summary: Illegal\
  \ activity\n  text: You must not use this Website for any illegal activity or if you do not agree to the Website Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: only users above the age of 18 (eighteen) may use the Services or provide their personal information to\n    us for processing.\n"
source_yaml_url: https://artifacts.apis.io/howler/eligibility/howler-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Howler's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Event
- Ticketing
- Payments
- Cashless
- RFID
- Event Management
- Fintech
- South Africa
---
