---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Platform is offered and available to users who are 18 years of age or older, and reside in the United States or any of its territories or possessions.
  entity_types:
  - text: if you are using the Platform on behalf of an organization, that you have the right, authority and capacity to bind such organization to these Terms of Use
    type: business
  minimum_age:
    text: This Platform is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties
    text: If you reside in any of these sanctioned countries or represent a sanctioned organization, are a sanctioned individual, you may not access the Platform.
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
name: RapidFort
provenance_date: '2026-11-10'
provider_name: RapidFort
provider_slug: rapidfort
slug: rapidfort-eligibility
source_date: '2026-11-10'
source_filename: rapidfort-eligibility.yml
source_heading: Eligibility
source_page: https://www.rapidfort.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RapidFort\naid: rapidfort\nurl: https://www.rapidfort.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Platform is offered and available to users who are 18 years of age or older, and reside in the United\n    States or any of its territories or possessions.\nentity_types:\n- type: business\n  text: if you are using the Platform on behalf of an organization, that you have the right, authority and capacity\n    to bind such organization to these Terms of Use\nrestricted_uses:\n- summary: Sanctioned parties\n  text: If you reside in any of these sanctioned\
  \ countries or represent a sanctioned organization, are a sanctioned\n    individual, you may not access the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Platform is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/rapidfort/eligibility/rapidfort-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from RapidFort's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Container Security
- Software Supply Chain
- Vulnerability Management
- DevSecOps
- Compliance
- Containers
---
