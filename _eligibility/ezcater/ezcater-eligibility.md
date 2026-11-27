---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Platform on behalf of an entity or organization, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use of the Platform for any illegal purpose—or for any other purpose not expressly permitted in these Terms—is strictly prohibited.
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
name: ezCater
provenance_date: '2026-11-09'
provider_name: ezCater
provider_slug: ezcater
slug: ezcater-eligibility
source_date: '2026-11-09'
source_filename: ezcater-eligibility.yml
source_heading: Eligibility
source_page: https://www.ezcater.com/terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ezCater\naid: ezcater\nurl: https://www.ezcater.com/terms_of_use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Platform on behalf of an entity or organization, you represent and warrant that you have\n    the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use of the Platform for any illegal purpose—or for any other purpose not expressly permitted in these Terms—is\n    strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/ezcater/eligibility/ezcater-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ezCater's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Catering
- Food
- Food Delivery
- Corporate Catering
- Restaurant
- Workplace
- E-Commerce
---
