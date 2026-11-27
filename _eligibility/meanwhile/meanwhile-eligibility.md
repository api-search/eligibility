---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The material on this website should not be construed as any solicitation to buy ... any insurance product in any jurisdiction other than Bermuda.
  entity_types:
  - text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    type: individual
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: No insurance solicitation outside Bermuda
    text: The Company or Meanwhile Bermuda do not conduct insurance business in any other jurisdiction.
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
name: Meanwhile
provenance_date: '2026-11-10'
provider_name: Meanwhile
provider_slug: meanwhile
slug: meanwhile-eligibility
source_date: '2026-11-10'
source_filename: meanwhile-eligibility.yml
source_heading: Eligibility
source_page: https://meanwhile.bm/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meanwhile\naid: meanwhile\nurl: https://meanwhile.bm/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The material on this website should not be construed as any solicitation to buy ... any insurance product\n    in any jurisdiction other than Bermuda.\nentity_types:\n- type: individual\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\nrestricted_uses:\n- summary: No insurance solicitation outside Bermuda\n  text: The Company or Meanwhile Bermuda do not conduct insurance business in any other jurisdiction.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/meanwhile/eligibility/meanwhile-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Meanwhile's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Bitcoin
- Insurance
- Life Insurance
- Fintech
- Bermuda
---
