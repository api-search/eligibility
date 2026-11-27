---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our services are for businesses and this site is directed at businesses not consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse of site
    text: use our site in any way that is unlawful, illegal, fraudulent or harmful
  - summary: Probing or circumventing security
    text: probe, scan or test the vulnerability of our site without our permission; circumvent any authentication or security systems or processes on or relating to our site
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
name: Harbr
provenance_date: '2026-11-09'
provider_name: Harbr
provider_slug: harbr
slug: harbr-eligibility
source_date: '2026-11-09'
source_filename: harbr-eligibility.yml
source_heading: Eligibility
source_page: https://harbrdata.com/security-center/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harbr\naid: harbr\nurl: https://harbrdata.com/security-center/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our services are for businesses and this site is directed at businesses not consumers.\nrestricted_uses:\n- summary: Misuse of site\n  text: use our site in any way that is unlawful, illegal, fraudulent or harmful\n- summary: Probing or circumventing security\n  text: probe, scan or test the vulnerability of our site without our permission; circumvent any authentication\n    or security systems or processes\
  \ on or relating to our site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/harbr/eligibility/harbr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Harbr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Sharing
- Data Marketplace
- Data Exchange
- Data Governance
- Data Collaboration
- External Data
- Data Products
---
