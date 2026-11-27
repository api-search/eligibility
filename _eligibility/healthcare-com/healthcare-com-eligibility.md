---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD OR DO NOT RESIDE IN THE UNITED STATES OF AMERICA.
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your own personal, noncommercial use
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
name: Healthcare.com
provenance_date: '2026-11-09'
provider_name: Healthcare.com
provider_slug: healthcare-com
slug: healthcare-com-eligibility
source_date: '2026-11-09'
source_filename: healthcare-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.healthcare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Healthcare.com\naid: healthcare-com\nurl: https://www.healthcare.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD OR DO NOT RESIDE\n    IN THE UNITED STATES OF AMERICA.\nentity_types: []\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your own personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS\
  \ IF YOU ARE NOT AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/healthcare-com/eligibility/healthcare-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Healthcare.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Insurance
- Insurance
- Healthcare
- Medicare
- Insurtech
- Marketplace
- Consumer
- Lead Generation
- Insurance Distribution
---
