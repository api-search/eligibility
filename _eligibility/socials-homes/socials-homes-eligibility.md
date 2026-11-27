---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To use our Services, you must: Be at least 18 years old Be a current or prospective student'
    type: individual
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No spam or unsolicited messages
    text: Send spam, unsolicited messages, or commercial communications
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
name: socials-homes
provenance_date: '2026-11-10'
provider_name: socials-homes
provider_slug: socials-homes
slug: socials-homes-eligibility
source_date: '2026-11-10'
source_filename: socials-homes-eligibility.yml
source_heading: Eligibility
source_page: https://www.socials.homes/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: socials-homes\naid: socials-homes\nurl: https://www.socials.homes/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To use our Services, you must: Be at least 18 years old Be a current or prospective student'\nrestricted_uses:\n- summary: No spam or unsolicited messages\n  text: Send spam, unsolicited messages, or commercial communications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/socials-homes/eligibility/socials-homes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from socials-homes's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Housing
- Rentals
- International
- WhatsApp
- Real Estate
---
