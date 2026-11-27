---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a binding agreement.
    type: individual
  - text: If you accept these Terms for a business or other organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a binding agreement.
    value: '18'
  restricted_uses:
  - summary: Unlawful or unsolicited communications
    text: You may not use the Services to send unlawful, deceptive, harassing, abusive, or unsolicited communications.
  - summary: Sensitive data not designed for processing
    text: Do not submit sensitive information that the Services are not designed to process, such as full payment-card data, protected health information, government identification numbers, or account passwords belonging to third-party services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require identity or authority verification before changing ownership, billing, or administrator access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ResponsiBid
provenance_date: '2026-11-10'
provider_name: ResponsiBid
provider_slug: responsibid
slug: responsibid-eligibility
source_date: '2026-11-10'
source_filename: responsibid-eligibility.yml
source_heading: Eligibility
source_page: https://responsibid.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ResponsiBid\naid: responsibid\nurl: https://responsibid.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a binding agreement.\n- type: business\n  text: If you accept these Terms for a business or other organization, you represent that you have authority to\n    bind that organization.\nrestricted_uses:\n- summary: Unlawful or unsolicited communications\n  text: You may not use the Services to send unlawful, deceptive, harassing, abusive, or unsolicited\
  \ communications.\n- summary: Sensitive data not designed for processing\n  text: Do not submit sensitive information that the Services are not designed to process, such as full payment-card\n    data, protected health information, government identification numbers, or account passwords belonging to third-party\n    services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require identity or authority verification before changing ownership, billing, or administrator access.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/responsibid/eligibility/responsibid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from ResponsiBid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pricing
- Sales Software
- Home Services
- Software-as-a-Service
---
