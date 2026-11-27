---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: the material on the Platform is presented solely for the purpose of sale in India. Urbanic makes no representation that materials in the Platform are appropriate or available for use in other locations/Countries other than India.
  minimum_age:
    text: If you are a minor i.e. under the age of 18 years, you shall not register as a User of the Platform and shall not transact on or use the Platform.
    value: '18'
  restricted_uses:
  - summary: Fraudulent or unlawful use
    text: You shall not use the Platform for any unlawful and fraudulent purposes, which may cause annoyance and inconvenience
  - summary: Resale of products bought via Platform
    text: Products ordered are not for self-consumption but for commercial resale
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
name: Urbanic
provenance_date: '2026-11-10'
provider_name: Urbanic
provider_slug: urbanic
slug: urbanic-eligibility
source_date: '2026-11-10'
source_filename: urbanic-eligibility.yml
source_heading: Eligibility
source_page: https://in.urbanic.com/help-center/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Urbanic\naid: urbanic\nurl: https://in.urbanic.com/help-center/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: the material on the Platform is presented solely for the purpose of sale in India. Urbanic makes no representation\n    that materials in the Platform are appropriate or available for use in other locations/Countries other than\n    India.\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or unlawful use\n  text: You shall not use the Platform for any unlawful and fraudulent purposes, which may cause annoyance and inconvenience\n- summary:\
  \ Resale of products bought via Platform\n  text: Products ordered are not for self-consumption but for commercial resale\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are a minor i.e. under the age of 18 years, you shall not register as a User of the Platform and\n    shall not transact on or use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/urbanic/eligibility/urbanic-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Urbanic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Fashion
- Apparel
- Retail
- Consumer
---
