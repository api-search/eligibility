---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Accessing the Service is prohibited from territories where the Content is illegal.
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old (and at least the legal age in your jurisdiction).
    type: individual
  - text: If you are registering an Account on behalf of a company, you represent that you have the authority to enter into the Terms of Use on behalf of the company you have named as the User
    type: business
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old (and at least the legal age in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: The Service is provided only for your own personal, non-commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Watsi may, in its sole discretion, refuse to offer the Service to any person or entity and change its eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Watsi
provenance_date: '2026-11-10'
provider_name: Watsi
provider_slug: watsi
slug: watsi-eligibility
source_date: '2026-11-10'
source_filename: watsi-eligibility.yml
source_heading: Eligibility
source_page: https://watsi.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Watsi\naid: watsi\nurl: https://watsi.org/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Accessing the Service is prohibited from territories where the Content is illegal.\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old (and at least the legal age in\n    your jurisdiction).\n- type: business\n  text: If you are registering an Account on behalf of a company, you represent that you have the authority to enter\n    into the Terms of Use on behalf of the company you have named as the User\nrestricted_uses:\n\
  - summary: Personal, non-commercial use only\n  text: The Service is provided only for your own personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Watsi may, in its sole discretion, refuse to offer the Service to any person or entity and change its eligibility\n    criteria at any time.\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years old (and at least the legal age in\n    your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/watsi/eligibility/watsi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Watsi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Non-Profit
- Healthcare
- Crowdfunding
- Donations
- Global Health
---
