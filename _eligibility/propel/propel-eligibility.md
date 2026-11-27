---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You agree to use the Services only for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to create and use a Propel Account, you must authenticate yourself using either a verified email address or through a third party Single Sign On provider
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Propel
provenance_date: '2026-11-10'
provider_name: Propel
provider_slug: propel
slug: propel-eligibility
source_date: '2026-11-10'
source_filename: propel-eligibility.yml
source_heading: Eligibility
source_page: https://www.propel.app/propel/en/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Propel\naid: propel\nurl: https://www.propel.app/propel/en/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a terrorist-supporting country\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: You agree to use the Services only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to create and use a Propel Account, you must authenticate yourself using either\
  \ a verified email\n    address or through a third party Single Sign On provider\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/propel/eligibility/propel-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Propel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Government Benefits
- SNAP
- EBT
- Consumer Finance
- Mobile App
- Financial Health
---
