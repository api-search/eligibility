---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be of legal age to enter into a binding agreement in order to accept the Terms.
    type: individual
  - text: If You are agreeing on behalf of Your business, You will be responsible for the compliance of other users on the account with this agreement.
    type: business
  minimum_age:
    text: You must be of legal age to enter into a binding agreement in order to accept the Terms.
    value: legal age
  restricted_uses:
  - summary: Competitor access prohibited
    text: Employees or affiliates of businesses offering Services that directly compete with any of Vtiger’s Services are expressly prohibited from accessing any Vtiger Services for competitive research or related activities.
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
name: Vtiger
provenance_date: '2026-11-10'
provider_name: Vtiger
provider_slug: vtiger
slug: vtiger-eligibility
source_date: '2026-11-10'
source_filename: vtiger-eligibility.yml
source_heading: Eligibility
source_page: https://www.vtiger.com/policy-legal-center/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vtiger\naid: vtiger\nurl: https://www.vtiger.com/policy-legal-center/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be of legal age to enter into a binding agreement in order to accept the Terms.\n- type: business\n  text: If You are agreeing on behalf of Your business, You will be responsible for the compliance of other users\n    on the account with this agreement.\nrestricted_uses:\n- summary: Competitor access prohibited\n  text: Employees or affiliates of businesses offering Services that directly compete\
  \ with any of Vtiger’s Services\n    are expressly prohibited from accessing any Vtiger Services for competitive research or related activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You must be of legal age to enter into a binding agreement in order to accept the Terms.\n"
source_yaml_url: https://artifacts.apis.io/vtiger/eligibility/vtiger-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vtiger's own page on 2026-11-10.
synthetic: false
tags:
- Company
- CRM
- Artificial Intelligence
- Sales
- Automation
---
