---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: you represent that you are (i) at least thirteen (13) years old, (ii) of legal age to form a binding contract
    type: individual
  - text: IF YOU USE THE SERVICES ON BEHALF OF AN ENTITY OR INDIVIDUAL, YOUR ACCEPTANCE OF THE TERMS OF USE WILL BE DEEMED AN ACCEPTANCE BY THAT ENTITY OR INDIVIDUAL
    type: business
  minimum_age:
    text: you represent that you are (i) at least thirteen (13) years old
    value: '13'
  restricted_uses:
  - summary: Prohibited App content and uses
    text: 'Your App must not: (i) be used for fraud, scams, spam, or phishing'
  - summary: Prohibited content
    text: Any Content posted by you may not contain nudity, violence, sexually explicit, dangerous, hateful, harassing, fraudulent, misleading, illegal, offensive subject matter
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
name: Runway Financial
provenance_date: '2026-11-10'
provider_name: Runway Financial
provider_slug: runway-com
slug: runway-com-eligibility
source_date: '2026-11-10'
source_filename: runway-com-eligibility.yml
source_heading: Eligibility
source_page: https://runway.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Runway Financial\naid: runway-com\nurl: https://runway.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you represent that you are (i) at least thirteen (13) years old, (ii) of legal age to form a binding contract\n- type: business\n  text: IF YOU USE THE SERVICES ON BEHALF OF AN ENTITY OR INDIVIDUAL, YOUR ACCEPTANCE OF THE TERMS OF USE WILL BE\n    DEEMED AN ACCEPTANCE BY THAT ENTITY OR INDIVIDUAL\n\
  restricted_uses:\n- summary: Prohibited App content and uses\n  text: 'Your App must not: (i) be used for fraud, scams, spam, or phishing'\n- summary: Prohibited content\n  text: Any Content posted by you may not contain nudity, violence, sexually explicit, dangerous, hateful, harassing,\n    fraudulent, misleading, illegal, offensive subject matter\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you represent that you are (i) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/runway-com/eligibility/runway-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Runway Financial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Payments
---
