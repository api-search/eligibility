---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: To use the Early Investor feature, you must (i) be at least 18 years of age; (ii) be a U.S. person; and (iii) meet any additional eligibility requirements imposed by the ASP or the applicable 529 plan.
  entity_types:
  - text: You must be 18 years of age or older and have a valid credit card to purchase any Babylist Products on Our Website.
    type: individual
  - text: If You are accessing and accepting these Terms on behalf of a company or other legal entity, You represent that You have the authority to bind that company or legal entity to these Terms.
    type: business
  minimum_age:
    text: You must be 18 years of age or older and have a valid credit card to purchase any Babylist Products on Our Website.
    value: '18'
  restricted_uses:
  - summary: Early Investor availability by state
    text: Babylist makes no representation that the Early Investor feature is available or appropriate for residents of all states.
  - summary: AI Chatbots for minors
    text: The AI Chatbots are intended for use by persons 18 years of age or older. If You are under 18, You may use them only with the involvement and supervision of a parent or legal guardian who accepts these Terms on Your behalf.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Babylist reserves the right to accept or refuse Your application for an account (in Our absolute and sole discretion).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BabyList
provenance_date: '2026-11-09'
provider_name: BabyList
provider_slug: babylist
slug: babylist-eligibility
source_date: '2026-11-09'
source_filename: babylist-eligibility.yml
source_heading: Eligibility
source_page: https://www.babylist.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BabyList\naid: babylist\nurl: https://www.babylist.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: To use the Early Investor feature, you must (i) be at least 18 years of age; (ii) be a U.S. person; and\n    (iii) meet any additional eligibility requirements imposed by the ASP or the applicable 529 plan.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older and have a valid credit card to purchase any Babylist Products on Our\n    Website.\n- type: business\n  text: If You are accessing and accepting these Terms on behalf of\
  \ a company or other legal entity, You represent\n    that You have the authority to bind that company or legal entity to these Terms.\nrestricted_uses:\n- summary: Early Investor availability by state\n  text: Babylist makes no representation that the Early Investor feature is available or appropriate for residents\n    of all states.\n- summary: AI Chatbots for minors\n  text: The AI Chatbots are intended for use by persons 18 years of age or older. If You are under 18, You may use\n    them only with the involvement and supervision of a parent or legal guardian who accepts these Terms on Your\n    behalf.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Babylist reserves the right to accept or refuse Your application for an account (in Our absolute and sole\n    discretion).\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and have a valid credit card to purchase any Babylist Products on Our\n    Website.\n"
source_yaml_url: https://artifacts.apis.io/babylist/eligibility/babylist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from BabyList's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Baby Registry
- E-Commerce
- Retail
- Family
- Parenting
- Health
- Shopping
---
