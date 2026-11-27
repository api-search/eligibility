---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SD
    - SY
    served: []
    text: 'you represent and warrant that you: 1. Will not use the Services to directly or indirectly conduct, promote, or facilitate business in countries and with nationals that are prohibited by U.S. embargoes or trade sanctions (these embargoed and sanctioned countries are: Cuba, North Korea, Iran, Sudan, and Syria)'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export/sanctions restrictions
    text: Will not use the Services to export items, content, or materials to or for military, nuclear, missile, chemical, or biological weaponry end users or end uses.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: OnlineNIC may elect to accept or reject your application for registration or renewal for any reason at its sole discretion.
excluded_countries:
- CU
- KP
- IR
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OnlineNIC
provenance_date: '2026-11-10'
provider_name: OnlineNIC
provider_slug: onlinenic
slug: onlinenic-eligibility
source_date: '2026-11-10'
source_filename: onlinenic-eligibility.yml
source_heading: Eligibility
source_page: https://www.onlinenic.com/en/Content/content/118.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OnlineNIC\naid: onlinenic\nurl: https://www.onlinenic.com/en/Content/content/118.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SD\n  - SY\n  text: 'you represent and warrant that you: 1. Will not use the Services to directly or indirectly conduct, promote,\n    or facilitate business in countries and with nationals that are prohibited by U.S. embargoes or trade sanctions\n    (these embargoed and sanctioned countries are: Cuba, North Korea, Iran, Sudan, and Syria)'\nentity_types: []\nrestricted_uses:\n- summary: Export/sanctions restrictions\n  text: Will\
  \ not use the Services to export items, content, or materials to or for military, nuclear, missile, chemical,\n    or biological weaponry end users or end uses.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: OnlineNIC may elect to accept or reject your application for registration or renewal for any reason at its\n    sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onlinenic/eligibility/onlinenic-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from OnlineNIC's own page on 2026-11-10.
synthetic: false
tags:
- Domains
- Domain Registration
- Registrar
- DNS
- SSL Certificates
- Certificates
- Reseller
- Hosting
- Security
---
