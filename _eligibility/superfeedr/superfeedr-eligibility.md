---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Service is not authorized in any jurisdiction that does not give effect to all provisions of the Terms of Service
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Spamming and unsolicited advertising
    text: constitutes unauthorized or unsolicited advertising, junk or bulk e-mail ("spamming")
  - summary: Running mailing lists or auto-responders
    text: (iv) run Maillist, Listserv, any form of auto-responder or "spam" on the Service
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Superfeedr may, in its sole discretion, refuse to offer the Service to any person or entity and change its eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Superfeedr
provenance_date: '2026-11-10'
provider_name: Superfeedr
provider_slug: superfeedr
slug: superfeedr-eligibility
source_date: '2026-11-10'
source_filename: superfeedr-eligibility.yml
source_heading: Eligibility
source_page: https://superfeedr.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Superfeedr\naid: superfeedr\nurl: https://superfeedr.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Service is not authorized in any jurisdiction that does not give effect to all provisions of\n    the Terms of Service\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old.\nrestricted_uses:\n- summary: Spamming and unsolicited advertising\n  text: constitutes unauthorized or unsolicited advertising, junk or bulk e-mail (\"spamming\")\n- summary: Running mailing lists or auto-responders\n  text:\
  \ (iv) run Maillist, Listserv, any form of auto-responder or \"spam\" on the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Superfeedr may, in its sole discretion, refuse to offer the Service to any person or entity and change its\n    eligibility criteria at any time.\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/superfeedr/eligibility/superfeedr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Superfeedr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real-Time
- Feed
- PubSubHubbub
---
