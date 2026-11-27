---
api_specs:
- filename: hummingdeck-companies-api-openapi.yml
  format: yaml
  label: HummingDeck Companies API
  slug: hummingdeck-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-companies-api-openapi.yml
- filename: hummingdeck-contacts-api-openapi.yml
  format: yaml
  label: HummingDeck Contacts API
  slug: hummingdeck-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-contacts-api-openapi.yml
- filename: hummingdeck-decisions-api-openapi.yml
  format: yaml
  label: HummingDeck Decisions API
  slug: hummingdeck-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-decisions-api-openapi.yml
- filename: hummingdeck-decks-api-openapi.yml
  format: yaml
  label: HummingDeck Decks API
  slug: hummingdeck-decks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-decks-api-openapi.yml
- filename: hummingdeck-emails-api-openapi.yml
  format: yaml
  label: HummingDeck Emails API
  slug: hummingdeck-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-emails-api-openapi.yml
- filename: hummingdeck-hooks-api-openapi.yml
  format: yaml
  label: HummingDeck Hooks API
  slug: hummingdeck-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-hooks-api-openapi.yml
- filename: hummingdeck-me-api-openapi.yml
  format: yaml
  label: HummingDeck Me API
  slug: hummingdeck-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-me-api-openapi.yml
- filename: hummingdeck-room-labels-api-openapi.yml
  format: yaml
  label: HummingDeck Room Labels API
  slug: hummingdeck-room-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-room-labels-api-openapi.yml
- filename: hummingdeck-room-views-api-openapi.yml
  format: yaml
  label: HummingDeck Room Views API
  slug: hummingdeck-room-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-room-views-api-openapi.yml
- filename: hummingdeck-rooms-api-openapi.yml
  format: yaml
  label: HummingDeck Rooms API
  slug: hummingdeck-rooms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-rooms-api-openapi.yml
- filename: hummingdeck-shares-api-openapi.yml
  format: yaml
  label: HummingDeck Shares API
  slug: hummingdeck-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-shares-api-openapi.yml
- filename: hummingdeck-views-api-openapi.yml
  format: yaml
  label: HummingDeck Views API
  slug: hummingdeck-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-views-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, and will not use the service in or for the benefit of, any country or party subject to comprehensive sanctions
  entity_types:
  - text: If you use HummingDeck on behalf of an organization, you represent that you are authorized to bind that organization to these Terms, and in that case "you" refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old, or the age of digital consent in your country if that age is higher, to use HummingDeck.
    value: '16'
  restricted_uses:
  - summary: Spam and bulk unsolicited messaging
    text: send spam or distribute links through bulk unsolicited messaging
  - summary: Phishing pages and credential forms
    text: host phishing pages, credential-harvesting forms, or deceptive landing pages
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
name: HummingDeck
provenance_date: '2026-11-09'
provider_name: HummingDeck
provider_slug: hummingdeck
slug: hummingdeck-eligibility
source_date: '2026-11-09'
source_filename: hummingdeck-eligibility.yml
source_heading: Eligibility
source_page: https://hummingdeck.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HummingDeck\naid: hummingdeck\nurl: https://hummingdeck.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, and will not use the service in or for the benefit of, any country\n    or party subject to comprehensive sanctions\nentity_types:\n- type: business\n  text: If you use HummingDeck on behalf of an organization, you represent that you are authorized to bind that\n    organization to these Terms, and in that case \"you\" refers to that organization.\nrestricted_uses:\n- summary: Spam and bulk unsolicited messaging\n  text: send\
  \ spam or distribute links through bulk unsolicited messaging\n- summary: Phishing pages and credential forms\n  text: host phishing pages, credential-harvesting forms, or deceptive landing pages\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old, or the age of digital consent in your country if that age is higher,\n    to use HummingDeck.\n"
source_yaml_url: https://artifacts.apis.io/hummingdeck/eligibility/hummingdeck-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from HummingDeck's own page on 2026-11-09.
synthetic: false
tags:
- Document Sharing
- Engagement Analytics
- Digital Sales Rooms
- Data Rooms
- Client Portals
- Integration
- Secure Sharing
---
