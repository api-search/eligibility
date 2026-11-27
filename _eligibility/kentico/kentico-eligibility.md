---
claim_count: 1
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
  - summary: Non-production installs must not display content to audience
    text: that are not used for displaying content to the website audience.
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
name: Kentico
provenance_date: '2026-11-09'
provider_name: Kentico
provider_slug: kentico
slug: kentico-eligibility
source_date: '2026-11-09'
source_filename: kentico-eligibility.yml
source_heading: Eligibility
source_page: https://www.kentico.com/end-user-license-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kentico\naid: kentico\nurl: https://www.kentico.com/end-user-license-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-production installs must not display content to audience\n  text: that are not used for displaying content to the website audience.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kentico/eligibility/kentico-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Kentico's own page on 2026-11-09.
synthetic: false
tags:
- CMS
- Content Management
- Digital Experience Platform
- GraphQL
- REST
- .NET
- Headless
- E-Commerce
- Digital Marketing
- Personalization
- Headless CMS
---
