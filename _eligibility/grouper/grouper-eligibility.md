---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Platform and all Offerings.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Platform and all Offerings.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: You may use the Platform and Offerings only for your individual and personal use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All Accounts are issued at the sole discretion of Grouper.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Grouper
provenance_date: '2026-11-09'
provider_name: Grouper
provider_slug: grouper
slug: grouper-eligibility
source_date: '2026-11-09'
source_filename: grouper-eligibility.yml
source_heading: Eligibility
source_page: https://hellogrouper.com/app-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grouper\naid: grouper\nurl: https://hellogrouper.com/app-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Platform and all Offerings.\nrestricted_uses:\n- summary: Personal use only\n  text: You may use the Platform and Offerings only for your individual and personal use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All Accounts are issued at the sole discretion of Grouper.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years\
  \ of age to use the Platform and all Offerings.\n"
source_yaml_url: https://artifacts.apis.io/grouper/eligibility/grouper-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Grouper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthy Aging
- Health and Wellness
- Older Adults
- Medicare Advantage
- Social Connection
- Membership
- Consumer Health
---
