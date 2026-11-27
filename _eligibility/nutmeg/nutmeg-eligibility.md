---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: We will generally only provide a Portfolio or provide services to you if you are resident in the UK.
  entity_types:
  - text: be at least 18 years old
    type: individual
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: US Persons not served
    text: We do not provide Portfolios or services to US Persons.
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
name: Nutmeg (J.P. Morgan Personal Investing)
provenance_date: '2026-11-10'
provider_name: Nutmeg (J.P. Morgan Personal Investing)
provider_slug: nutmeg
slug: nutmeg-eligibility
source_date: '2026-11-10'
source_filename: nutmeg-eligibility.yml
source_heading: Eligibility
source_page: https://www.personalinvesting.jpmorgan.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nutmeg (J.P. Morgan Personal Investing)\naid: nutmeg\nurl: https://www.personalinvesting.jpmorgan.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: We will generally only provide a Portfolio or provide services to you if you are resident in the UK.\nentity_types:\n- type: individual\n  text: be at least 18 years old\nrestricted_uses:\n- summary: US Persons not served\n  text: We do not provide Portfolios or services to US Persons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/nutmeg/eligibility/nutmeg-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nutmeg (J.P. Morgan Personal Investing)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wealth Management
- Robo-Advisor
- Investing
- Fintech
- Pensions
- ISA
- United Kingdom
---
