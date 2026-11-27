---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Liquidly reserves the right to limit the availability of the Website and/or Services to any person, geographic area, or jurisdiction it so desires at any time and in our sole discretion.
  entity_types:
  - text: You represent that you are (i) at least eighteen (18) years old
    type: individual
  - text: the authority to enter into the agreement personally or on behalf of the company you have named as the user
    type: business
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: No impersonation or unlawful content
    text: Impersonate any person or entity, including, but not limited to, Liquidly personnel
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Liquidly reserves the right to refuse registration for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Liquidly
provenance_date: '2026-11-09'
provider_name: Liquidly
provider_slug: liquidly
slug: liquidly-eligibility
source_date: '2026-11-09'
source_filename: liquidly-eligibility.yml
source_heading: Eligibility
source_page: https://www.liquidly.com/Terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liquidly\naid: liquidly\nurl: https://www.liquidly.com/Terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Liquidly reserves the right to limit the availability of the Website and/or Services to any person, geographic\n    area, or jurisdiction it so desires at any time and in our sole discretion.\nentity_types:\n- type: individual\n  text: You represent that you are (i) at least eighteen (18) years old\n- type: business\n  text: the authority to enter into the agreement personally or on behalf of the company you have named as the user\nrestricted_uses:\n- summary: No impersonation\
  \ or unlawful content\n  text: Impersonate any person or entity, including, but not limited to, Liquidly personnel\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Liquidly reserves the right to refuse registration for any reason.\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/liquidly/eligibility/liquidly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Liquidly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Private Markets
- Secondary Market
- Alternative Assets
- Private Equity
- Venture Capital
- Marketplace
- Broker-Dealer
---
