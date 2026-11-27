---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Platform is intended to be used by legal, accounting, other client-based professionals located in the United States and Canada.
  minimum_age:
    text: You are at least 18 years of age and are capable of entering into a binding contract;
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: Use the Platform to engage in illegal, fraudulent, or deceptive practices;
  - summary: Sanctioned countries or export violations
    text: access the Platform from a country listed on any sanctions or export restriction lists maintained by the U.S.
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
name: Docketwise
provenance_date: '2026-11-09'
provider_name: Docketwise
provider_slug: docketwise
slug: docketwise-eligibility
source_date: '2026-11-09'
source_filename: docketwise-eligibility.yml
source_heading: Eligibility
source_page: https://www.8am.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docketwise\naid: docketwise\nurl: https://www.8am.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Platform is intended to be used by legal, accounting, other client-based professionals located in the\n    United States and Canada.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: Use the Platform to engage in illegal, fraudulent, or deceptive practices;\n- summary: Sanctioned countries or export violations\n  text: access the Platform from a country listed on any sanctions or export restriction\
  \ lists maintained by the\n    U.S.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age and are capable of entering into a binding contract;\n"
source_yaml_url: https://artifacts.apis.io/docketwise/eligibility/docketwise-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Docketwise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Immigration
- Law
- Software-as-a-Service
- Software
- Management
---
