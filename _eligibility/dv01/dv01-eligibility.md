---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: The Services are available only to individuals aged 18 years or older.
    type: individual
  - text: If you agree to the Agreement on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to the Agreement
    type: business
  minimum_age:
    text: The Services are available only to individuals aged 18 years or older.
    value: '18'
  restricted_uses:
  - summary: Illegal or abusive AI use
    text: You are prohibited from using the AI Features for any illegal, harmful, or abusive activity, including, without limitation, insider trading
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registered Users may be required to submit a request for access to such Platform Data to dv01 in our capacity as loan data agent for the applicable transaction.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: dv01
provenance_date: '2026-11-09'
provider_name: dv01
provider_slug: dv01
slug: dv01-eligibility
source_date: '2026-11-09'
source_filename: dv01-eligibility.yml
source_heading: Eligibility
source_page: https://www.dv01.co/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dv01\naid: dv01\nurl: https://www.dv01.co/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo or that has been designated\n    by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: The Services are available only to individuals aged 18 years or older.\n- type: business\n  text: If you agree to the Agreement on behalf of a company or other legal entity, you represent and warrant that\n    you have the authority to bind that company or other\
  \ legal entity to the Agreement\nrestricted_uses:\n- summary: Illegal or abusive AI use\n  text: You are prohibited from using the AI Features for any illegal, harmful, or abusive activity, including,\n    without limitation, insider trading\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registered Users may be required to submit a request for access to such Platform Data to dv01 in our capacity\n    as loan data agent for the applicable transaction.\nminimum_age:\n  value: '18'\n  text: The Services are available only to individuals aged 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/dv01/eligibility/dv01-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from dv01's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Structured Finance
- Consumer Lending
- Loan-Level Data
- Data Analytics
- Securitization
- Portfolio Surveillance
---
