---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MY
    text: Payments are limited to domestic (Malaysia) Billers and must be made in Ringgit Malaysia.
  entity_types:
  - text: To register for the CIDB Bayo Prepaid Card, the Customer must be at least eighteen (18) years of age.
    type: individual
  minimum_age:
    text: the Customer must be at least eighteen (18) years of age. Anyone below eighteen (18) years old may still register subject to his/her parent’s or legal guardian’s written consent
    value: '18'
  restricted_uses:
  - summary: Illegal activities
    text: not use CIDB Bayo Prepaid Card for illegal and/or unlawful activities
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: BPSB reserves the right to refuse and to reject any application for the CIDB Bayo Prepaid Card and/or to decline to issue a CIDB Bayo Prepaid Card at BPSB’ssole and absolute discretion without assigning any reasons whatsoever
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bayo Pay
provenance_date: '2026-11-09'
provider_name: Bayo Pay
provider_slug: bayo
slug: bayo-eligibility
source_date: '2026-11-09'
source_filename: bayo-eligibility.yml
source_heading: Eligibility
source_page: https://bayo.my/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bayo Pay\naid: bayo\nurl: https://bayo.my/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MY\n  excluded: []\n  text: Payments are limited to domestic (Malaysia) Billers and must be made in Ringgit Malaysia.\nentity_types:\n- type: individual\n  text: To register for the CIDB Bayo Prepaid Card, the Customer must be at least eighteen (18) years of age.\nrestricted_uses:\n- summary: Illegal activities\n  text: not use CIDB Bayo Prepaid Card for illegal and/or unlawful activities\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: BPSB reserves the right to refuse\
  \ and to reject any application for the CIDB Bayo Prepaid Card and/or to\n    decline to issue a CIDB Bayo Prepaid Card at BPSB’ssole and absolute discretion without assigning any reasons\n    whatsoever\nminimum_age:\n  value: '18'\n  text: the Customer must be at least eighteen (18) years of age. Anyone below eighteen (18) years old may still\n    register subject to his/her parent’s or legal guardian’s written consent\n"
source_yaml_url: https://artifacts.apis.io/bayo/eligibility/bayo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bayo Pay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Malaysia
---
