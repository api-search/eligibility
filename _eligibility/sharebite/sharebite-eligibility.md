---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The captured text says Passport may only be used in certain territories as agreed, but the list is cut off.
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  - text: If you are agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization's or entity's behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract.
    value: legal age
  restricted_uses:
  - summary: Internal use only
    text: You will only use the Services for your authorized internal use, not on behalf of or for the benefit of any third party
  - summary: Passport business use only
    text: You will only use Sharebite Passport for your authorized internal business purposes, and not for any personal, family or household use.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Before you are authorized to be issued a Sharebite Passport, Sharebite and Issuer must determine whether you are eligible to access and use Sharebite Passport.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sharebite
provenance_date: '2026-11-10'
provider_name: Sharebite
provider_slug: sharebite
slug: sharebite-eligibility
source_date: '2026-11-10'
source_filename: sharebite-eligibility.yml
source_heading: Eligibility
source_page: https://sharebite.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sharebite\naid: sharebite\nurl: https://sharebite.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The captured text says Passport may only be used in certain territories as agreed, but the list is cut off.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n- type: business\n  text: If you are agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization's\
  \ or entity's behalf\nrestricted_uses:\n- summary: Internal use only\n  text: You will only use the Services for your authorized internal use, not on behalf of or for the benefit of\n    any third party\n- summary: Passport business use only\n  text: You will only use Sharebite Passport for your authorized internal business purposes, and not for any personal,\n    family or household use.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Before you are authorized to be issued a Sharebite Passport, Sharebite and Issuer must determine whether\n    you are eligible to access and use Sharebite Passport.\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/sharebite/eligibility/sharebite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Sharebite's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food
- Employee Benefits
- Corporate Meal Benefits
- Human Resources
- Workplace
- Food Delivery
- Catering
- Prepaid Cards
- Food Tech
- Software-as-a-Service
---
