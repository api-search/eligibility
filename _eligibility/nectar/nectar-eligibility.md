---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The prices displayed are quoted in U.S. currency and are valid only in the United States.
  entity_types:
  - text: You represent that you are eighteen (18) years of age or older if you are providing a blood sample or accessing your Test Information through our website.
    type: individual
  minimum_age:
    text: You represent that you are eighteen (18) years of age or older if you are providing a blood sample or accessing your Test Information through our website.
    value: '18'
  restricted_uses:
  - summary: No insurer or employer use
    text: You are warranting that you are not an insurance company or an employer attempting to obtain Test Information about an insured person or an employee.
  - summary: No impersonation or account transfer
    text: You may not transfer your account to anyone else without our prior written permission.
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
name: Nectar
provenance_date: '2026-11-10'
provider_name: Nectar
provider_slug: nectar
slug: nectar-eligibility
source_date: '2026-11-10'
source_filename: nectar-eligibility.yml
source_heading: Eligibility
source_page: https://www.mynectar.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nectar\naid: nectar\nurl: https://www.mynectar.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The prices displayed are quoted in U.S. currency and are valid only in the United States.\nentity_types:\n- type: individual\n  text: You represent that you are eighteen (18) years of age or older if you are providing a blood sample or accessing\n    your Test Information through our website.\nrestricted_uses:\n- summary: No insurer or employer use\n  text: You are warranting that you are not an insurance company or an employer attempting to obtain Test Information\n   \
  \ about an insured person or an employee.\n- summary: No impersonation or account transfer\n  text: You may not transfer your account to anyone else without our prior written permission.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are eighteen (18) years of age or older if you are providing a blood sample or accessing\n    your Test Information through our website.\n"
source_yaml_url: https://artifacts.apis.io/nectar/eligibility/nectar-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nectar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Tech
- Allergy
- Telehealth
- Immunotherapy
- Consumer Health
---
