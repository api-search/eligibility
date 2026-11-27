---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical treatment
    text: Services related to medical treatment are not subject of the offering of nilo.
  - summary: Not suitable for suicidal persons
    text: If you have thoughts or even concrete plans to end your own life, the services of nilo are not suitable for you.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to verify that the user is an employee of a company using the services of nilo, the user must register with his/her company e-mail address or a nilo ID provided to the user in advance.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nilo Health
provenance_date: '2026-11-10'
provider_name: Nilo Health
provider_slug: nilo-health
slug: nilo-health-eligibility
source_date: '2026-11-10'
source_filename: nilo-health-eligibility.yml
source_heading: Eligibility
source_page: https://app.nilohealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nilo Health\naid: nilo-health\nurl: https://app.nilohealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No medical treatment\n  text: Services related to medical treatment are not subject of the offering of nilo.\n- summary: Not suitable for suicidal persons\n  text: If you have thoughts or even concrete plans to end your own life, the services of nilo are not suitable\n    for you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to verify that the user is an employee of\
  \ a company using the services of nilo, the user must register\n    with his/her company e-mail address or a nilo ID provided to the user in advance.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nilo-health/eligibility/nilo-health-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Nilo Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Health
- Human Resources
- Employee Benefits
- Wellbeing
- Telehealth
- Software-as-a-Service
---
