---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Contractor shall not permit any third party to access or use the SaaS in, or export such software to, a country subject to a United States embargo (as of the Effective Date, Cuba, Iran, North Korea, Sudan, and Syria).
  entity_types:
  - text: the corporation, LLC, partnership, sole proprietorship, or other business entity executing this agreement
    type: business
  - text: the sole proprietorship of an individual 18 years or older
    type: individual
  minimum_age:
    text: the sole proprietorship of an individual 18 years or older
    value: '18'
  restricted_uses:
  - summary: No scraping or bots
    text: engage in web scraping or data scraping on or related to the SaaS
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: measureQuick
provenance_date: '2026-11-10'
provider_name: measureQuick
provider_slug: measurequick
slug: measurequick-eligibility
source_date: '2026-11-10'
source_filename: measurequick-eligibility.yml
source_heading: Eligibility
source_page: https://support.measurequick.com/portal/en/kb/articles/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: measureQuick\naid: measurequick\nurl: https://support.measurequick.com/portal/en/kb/articles/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Contractor shall not permit any third party to access or use the SaaS in, or export such software to, a\n    country subject to a United States embargo (as of the Effective Date, Cuba, Iran, North Korea, Sudan, and Syria).\nentity_types:\n- type: business\n  text: the corporation, LLC, partnership, sole proprietorship, or other business entity executing this agreement\n- type: individual\n\
  \  text: the sole proprietorship of an individual 18 years or older\nrestricted_uses:\n- summary: No scraping or bots\n  text: engage in web scraping or data scraping on or related to the SaaS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the sole proprietorship of an individual 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/measurequick/eligibility/measurequick-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from measureQuick's own page on 2026-11-10.
synthetic: false
tags:
- Company
- HVAC
- Diagnostics
- Residential
- Software
---
