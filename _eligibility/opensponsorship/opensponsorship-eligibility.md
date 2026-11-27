---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Brands may sign up for a subscription plan offering support from an account manager
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Promoting competing services
    text: use the Service to advertise or promote a competing website, product, or service
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
name: OpenSponsorship
provenance_date: '2026-11-10'
provider_name: OpenSponsorship
provider_slug: opensponsorship
slug: opensponsorship-eligibility
source_date: '2026-11-10'
source_filename: opensponsorship-eligibility.yml
source_heading: Eligibility
source_page: https://opensponsorship.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenSponsorship\naid: opensponsorship\nurl: https://opensponsorship.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Brands may sign up for a subscription plan offering support from an account manager\nrestricted_uses:\n- summary: Promoting competing services\n  text: use the Service to advertise or promote a competing website, product, or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opensponsorship/eligibility/opensponsorship-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from OpenSponsorship's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sponsorship
- Sports
- Influencer Marketing
- Marketplace
- Athletes
- Advertising
---
