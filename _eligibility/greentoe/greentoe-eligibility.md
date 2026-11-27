---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your access to certain content or features may be limited if you are not 18 years of age or older, or the legal age in your jurisdiction to form a legally binding agreement, or for other reasons.
    type: individual
  - text: We may also impose restrictions on your ability to establish an account (e.g., age limits, restrict business entities from setting up accounts, limitations on the number of accounts, etc.).
    type: business
  minimum_age:
    text: Your access to certain content or features may be limited if you are not 18 years of age or older, or the legal age in your jurisdiction to form a legally binding agreement
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or impersonation use
    text: use our Site or Service in an unlawful or fraudulent manner or for such purposes, to collect personally identifiable information, or to impersonate other users
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
name: Greentoe
provenance_date: '2026-11-09'
provider_name: Greentoe
provider_slug: greentoe
slug: greentoe-eligibility
source_date: '2026-11-09'
source_filename: greentoe-eligibility.yml
source_heading: Eligibility
source_page: https://www.greentoe.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Greentoe\naid: greentoe\nurl: https://www.greentoe.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Your access to certain content or features may be limited if you are not 18 years of age or older, or the\n    legal age in your jurisdiction to form a legally binding agreement, or for other reasons.\n- type: business\n  text: We may also impose restrictions on your ability to establish an account (e.g., age limits, restrict business\n    entities from setting up accounts, limitations on the number of accounts, etc.).\nrestricted_uses:\n\
  - summary: Unlawful, fraudulent or impersonation use\n  text: use our Site or Service in an unlawful or fraudulent manner or for such purposes, to collect personally\n    identifiable information, or to impersonate other users\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Your access to certain content or features may be limited if you are not 18 years of age or older, or the\n    legal age in your jurisdiction to form a legally binding agreement\n"
source_yaml_url: https://artifacts.apis.io/greentoe/eligibility/greentoe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Greentoe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Marketplace
- Consumer
- Electronics
- Price Negotiation
- Shopping
---
