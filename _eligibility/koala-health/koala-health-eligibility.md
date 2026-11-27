---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country or territory that is subject to U.S. sanctions
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and sanctions
    text: You may not use the Koala Services if you are subject to U.S. export control and economic sanctions laws and regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to make purchases on Koala’s website and to use certain Koala Services, you must register for an account with Koala
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Koala Health
provenance_date: '2026-11-09'
provider_name: Koala Health
provider_slug: koala-health
slug: koala-health-eligibility
source_date: '2026-11-09'
source_filename: koala-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.koala.health/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Koala Health\naid: koala-health\nurl: https://www.koala.health/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country or territory that is subject to U.S. sanctions\nentity_types: []\nrestricted_uses:\n- summary: Export control and sanctions\n  text: You may not use the Koala Services if you are subject to U.S. export control and economic sanctions laws\n    and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to make purchases on Koala’s website and to use certain Koala\
  \ Services, you must register for an\n    account with Koala\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/koala-health/eligibility/koala-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Koala Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pet Health
- Veterinary
- Pharmacy
- Healthcare
- E-Commerce
- Prescriptions
- Animal Health
- Direct to Consumer
---
