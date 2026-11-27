---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Lawful use only; no spam or purchased leads
    text: Importing or in any way using purchased leads with a RetainIQ account is strictly prohibited.
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
name: RetainIQ
provenance_date: '2026-11-10'
provider_name: RetainIQ
provider_slug: retainiq
slug: retainiq-eligibility
source_date: '2026-11-10'
source_filename: retainiq-eligibility.yml
source_heading: Eligibility
source_page: https://retainiq.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RetainIQ\naid: retainiq\nurl: https://retainiq.io/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only; no spam or purchased leads\n  text: Importing or in any way using purchased leads with a RetainIQ account is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/retainiq/eligibility/retainiq-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from RetainIQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Retention Marketing
- Email Marketing
- SMS
- E-Commerce
- Personalization
- Consumer
- Klaviyo
- Direct to Consumer
---
