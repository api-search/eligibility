---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If our Services are prohibited by law where you live, then you may not use our Site or our Services
  entity_types:
  - text: Kickstarter is for your personal, non-commercial use, except as explained in section 4 and section 5 below.
    type: individual
  minimum_age:
    text: You must be 18 years old or over to sign up for a Kickstarter account.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We have the right to verify your identity and investigate your account details at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kickstarter
provenance_date: '2026-11-09'
provider_name: Kickstarter
provider_slug: kickstarter
slug: kickstarter-eligibility
source_date: '2026-11-09'
source_filename: kickstarter-eligibility.yml
source_heading: Eligibility
source_page: https://legal.kickstarter.com/policies/en/?name=terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kickstarter\naid: kickstarter\nurl: https://legal.kickstarter.com/policies/en/?name=terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If our Services are prohibited by law where you live, then you may not use our Site or our Services\nentity_types:\n- type: individual\n  text: Kickstarter is for your personal, non-commercial use, except as explained in section 4 and section 5 below.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We have the right to verify your identity and investigate your account details at any time.\n\
  minimum_age:\n  value: '18'\n  text: You must be 18 years old or over to sign up for a Kickstarter account.\n"
source_yaml_url: https://artifacts.apis.io/kickstarter/eligibility/kickstarter-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Kickstarter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Crowdfunding
- Fundraising
- Creators
- Payments
- Marketplace
- Public Benefit Corporation
---
