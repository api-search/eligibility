---
api_specs:
- filename: clawpost-net-api-openapi.json
  format: json
  label: Claw Post API API
  slug: claw-post-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawpost-net/openapi/_original/clawpost-net-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least 18 years old and have the full legal capacity to enter into this agreement.
    type: individual
  - text: If you use the Service on behalf of a company or organization, you further represent that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You represent and warrant that you are at least 18 years old and have the full legal capacity to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: Spam and unsolicited messaging
    text: 'Spam or Unwanted Messaging: Sending unsolicited bulk or harassing messages, ads, or promotions via social networks.'
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
name: Claw Post
provenance_date: '2026-11-09'
provider_name: Claw Post
provider_slug: clawpost-net
slug: clawpost-net-eligibility
source_date: '2026-11-09'
source_filename: clawpost-net-eligibility.yml
source_heading: Eligibility
source_page: https://clawpost.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claw Post\naid: clawpost-net\nurl: https://clawpost.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years old and have the full legal capacity to enter into\n    this agreement.\n- type: business\n  text: If you use the Service on behalf of a company or organization, you further represent that you have the authority\n    to bind that entity to these Terms.\nrestricted_uses:\n- summary: Spam and unsolicited messaging\n  text: 'Spam or Unwanted Messaging: Sending unsolicited\
  \ bulk or harassing messages, ads, or promotions via social\n    networks.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years old and have the full legal capacity to enter into\n    this agreement.\n"
source_yaml_url: https://artifacts.apis.io/clawpost-net/eligibility/clawpost-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Claw Post's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Social Media
- Automation
- Posting
- Agents
---
