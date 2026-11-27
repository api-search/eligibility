---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Individuals who are legal residents of the United States (including its territories and possessions) and at least 17 years or older who provide and maintain a valid email address are eligible to become members.
  entity_types:
  - text: The program is available to individuals for their personal use only
    type: individual
  - text: Corporations, associations or other groups may not participate in Beam Rewards.
    type: business
  minimum_age:
    text: This product is not for use by or sale to persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Sales limits by region or person
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region or jurisdiction.
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
name: Beam
provenance_date: '2026-11-09'
provider_name: Beam
provider_slug: beamtlc-com
slug: beamtlc-com-eligibility
source_date: '2026-11-09'
source_filename: beamtlc-com-eligibility.yml
source_heading: Eligibility
source_page: https://shopbeam.com/pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beam\naid: beamtlc-com\nurl: https://shopbeam.com/pages/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Individuals who are legal residents of the United States (including its territories and possessions) and\n    at least 17 years or older who provide and maintain a valid email address are eligible to become members.\nentity_types:\n- type: individual\n  text: The program is available to individuals for their personal use only\n- type: business\n  text: Corporations, associations or other groups may not participate in Beam Rewards.\nrestricted_uses:\n- summary:\
  \ Sales limits by region or person\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region or jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This product is not for use by or sale to persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/beamtlc-com/eligibility/beamtlc-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Beam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wellness
- Supplements
- Health
- E-Commerce
---
